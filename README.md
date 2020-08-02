bgfx-shaderc-makefile

Going into bgfx, I wanted a makefile to speed up having to compile shader files.. 
I wanted to plan ahead for adding more shader files to compile automatically and by-platform without having to get my hands greasy 
I created this and it works like a charm - reccomended learning how GNUmake syntax works to tailor it to your needs as it's very barebones - compared to how in-depth bgfx example makefile for shader compilation does it

all vertex and fragment files must be accompanied with a varying .def file of same name (see source-shader for example) - exports .bin binary files to platform/
