# rpipico_c
A repo to test the C/C++ SDK for the Raspberry Pi Pico

How to build the projects:
````shell
# Choose a dir
cd ./blink
# move to ./build
cd ./build
# Set env Variable PICO_SDK_PATH to the pico-sdk location
export PICO_SDK_PATH=/path/to/pico-sdk
# execute cmake
cmake ..
# make with 8 simultaneous processes
make -j8
````