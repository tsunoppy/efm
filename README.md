# efm

equivalent frame method

# Features
- to calculate the moment and shear by equivalent method

# Souse Code

## how to run
move your dir, then

``` shell
>python3 emf.py
```
# Input parameter

``` text
ly(m)     : equivalent width
fc(N/mm2) : compressive concrete strength
wd(kN/m2) : uniform load

span(m)   : span
tsslab(m) : slab thickness
tdrop(m)  : drop panel thickness
htop(m)   : column height above plate
hbot(m)   : column height bellow plate
cx(m)     : column depth to the analysis direction
cy(m)     : column width to perpendicular dimention
x(m)      : tortional member depth
```

# Calculation parameter

``` text
df(-)      : distribution factor
coef(-)    : carry over factor
fem(kN.m)  : fixed moment
dist(kN.m) : distribution moment at each step
co(kN.m)   : carry over moment at each step
cal        : dist and co
md(kN.m)   : moment result
vl(kN)     : initial shear force
ve(kN)     : shear force by ef
v(kN)      : shear force resultant by vl+ve
```
