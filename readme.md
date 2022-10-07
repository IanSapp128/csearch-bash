# csearch bash
Wanted to familiarize myself with bash so I decide to port my [Go](https://github.com/IanSapp128/Census-Search) and [C++](https://github.com/IanSapp128/csearch) to it. It is a utility that pulls up the API documentation for the census table you provide it. Supported tables are **Detailed Tables**, **Subject Tables**, and **Data Profiles** for ACS 5 year survey data. I use this application almost daily for my job and figured I'd share it.

I initially created this project as a Python script but startup time was pretty slow. Currently works on Linux and Mac. This version won't work on Windows unless you use cygwin and honestly, that's outside the scope of this quick utility. I made this version so I could share it among other users who don't want to compile the C++ or Go versions. They can just paste it and run it on their systems. 

This should have all of the functionality that the Go and C++ versions have (other than working on Windows). To optimize use, just place the script in your bin directory or create a path to it in your bash/zsh configs. This way you can just open a terminal and type csearch *table_name*. 