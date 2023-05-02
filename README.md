# Mosaic5G-FlexRan

### 1. Clone this repository:  
```
git clone http://gitlab.eurecom.fr/mosaic5g/mosaic5g.git
```

### 2. Build all the platforms from source or Snap
From Source: 
```
./build_m5g -m 
```

From Snap:   
```
./build_m5g -M 
```

### 3. Build specific platform from source (lowercase option letter) or Snap (uppercase option letter, when available)
FlexRAN: 
```
./build_m5g -f  or ./build_m5g -F 
```
LL-MEC: 
```
./build_m5g -l   or ./build_m5g -L 
```
JOX: 
```
./build_m5g -j 
```
STORE: 
```
./build_m5g -s 
```
OAI-RAN: 
```
./build_m5g -r   or ./build_m5g -R 
```
OAI-CN: 
```
./build_m5g -c   or ./build_m5g -C 
```

Check the help of build_m5g:
```
./build_m5g -h 
```
