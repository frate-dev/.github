## Frate Package Manager 📦 & Project Templating System 📐 **In Alpha**

For many years C/C++ developers have fought with build system after build system with promises of simplicity and the ability to scale your project to any scale. We aim to create a ecosystem that values **actual simplicity** while also having the ability to maintain compatiablility with any editor/IDE which supports CMake. While there are times in C/C++ where you need fine grained control over your project, we don't take this away, we simply extend it.

### Our template system
We provide default project templates which you can extend with the power of **lua** along with automatic depedency management. Once a project is initialized it renders template files to your project. Then you run the project, **at this point, there is no need to modify the CMakeList.txt or Makefile** . But if need be you do have the ability to modify your cmake template in templates/CMakeLists.txt.inja.

### Our package manager
The package manager side of this project allows you to manage dependecies in the same way tools like _cargo_ or _npm_

`frate add p SDL2`
or
`frate add p cxxopts`

This manages the linking of targets automatically so you can simply run `frate run` to begin building the dependecies

more information can be found at [Frate Official Docs](https://docs.frate.dev)







