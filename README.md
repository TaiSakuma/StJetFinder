StJetFinder
===========

A stand-alone version of the jet clustering algorithms used for the STAR experiment

### How to download, compile, and install

Checkout

    git clone git@github.com:TaiSakuma/StJetFinder.git
    cd StJetFinder

Run Autotools

    aclocal -I ./m4
    glibtoolize --copy --force
    autoconf
    automake --add-missing --copy --foreign

Configure (replace PREFIX with the path to which you want to install files, e.g., $HOME)

    ./configure --prefix=PREFIX

Compile

    make

Install

    make install

this will install files in PREFIX/include and PREFIX/lib
