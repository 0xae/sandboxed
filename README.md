# Sandboxed Vm
Sandboxed is a small footprint virtual machine with the goal 

of running insecure programs on a secury platform.


# Building
        
        git clone https://github.com/0xae/sandboxed
        cd sandboxed && make


# Beginning

After building you can start by playing with tinyvm like so:

        bin/tvmi programs/tinyvm/fact.vm


# About this project

This project aims to build a virtual machine capable of running 

insecure applications on an expected to be secure platforms.

Hence the name `Sandboxed` all programs are running inside a sandbox

built on top of the tinyvm.

We also aim to maintain full compatibility with tinyvm programs.

The changes are mainly on a security perspective
