# Time Racer

< just a dummy project right now >

current build instructions
### desktop 
clion (normal cmake process)

### web
on mac homebrew install dependencies like emscripten then
```
for example, from the root of time racer
mkdir cmake-build-web1
cd cmake-build-web1
emcmake cmake -S .. -B . -DWITH_EMSCRIPTENAPPLICATION=ON
```

### made using
magnum engine and its dependencies
https://magnum.graphics