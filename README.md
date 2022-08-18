# Microsoft.Z3.OSX.ARM64
Dotnet build of Z3 for Mac OSX and ARM64.

## Build Z3 Mac OS X ARM64

    In repo directory:
    git clone git@github.com:Z3Prover/z3.git

    git checkout tags/z3-4.8.11 

    CXX=clang++ CC=clang FPMATH_ENABLED=False python3 scripts/mk_make.py --dotnet --dotnet-key=./resources/z3.snk

    cd build

    make

    dotnet build z3.csproj