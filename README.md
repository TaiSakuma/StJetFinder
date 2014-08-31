StJetFinder
===========

A stand-alone version of the jet clustering algorithms used for the STAR experiment

### How to download and compile

Checkout

    git clone git@github.com:TaiSakuma/StJetFinder.git
    cd StJetFinder

Run Autotools

    aclocal -I ./m4
    glibtoolize --copy --force
    autoconf
    automake --add-missing --copy --foreign

Configure

    ./configure

Compile

    make

