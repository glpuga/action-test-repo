## C++ L2 Challenge

![CI master](https://github.com/glpuga/action-test-repo/workflows/CI/badge.svg?branch=master)
![CI devel](https://github.com/glpuga/action-test-repo/workflows/CI/badge.svg?branch=devel)
![CI this branch](https://github.com/glpuga/action-test-repo/workflows/CI/badge.svg)

This repo contains a solution to the CPP L2 challenge that proposed to reimplement a C++11 standard library container. The *std::vector* container was chosen for reimplementation.

The code can be found in the *include* folder, in header only form, along with test cases for it in the *test* folder.


### Build instructions

Download the source:

> git clone git@github.com:glpuga/ekucontainers.git

Build the code:

> cd ekucontainers

> mkdir build

> cd build

> cmake ..

> make

Run the tests:
> ./test/ekuvector_test

