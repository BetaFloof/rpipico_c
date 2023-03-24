Following the tutorial on electronicshub to get started

[https://www.electronicshub.org/program-raspberry-pi-pico-using-c/](https://www.electronicshub.org/program-raspberry-pi-pico-using-c/)

How to build:
````shell
# Set env Variable PICO_SDK_PATH to the pico-sdk location
export PICO_SDK_PATH=/path/to/pico-sdk
# move to ./build
cd ./build
# execute cmake
cmake ..
# make with 8 simultaneous processes
make -j8
````
