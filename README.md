# coreutils-macos-tiger-leopard-ppc

* This repo contains prebuilt PPC (PowerPC) binaries for the GNU coreutils for OS X versions 10.4 and 10.5.
* Building these tools requires a long time, along with the XCode developer tools, which is the reason that I've created this repo
* The version of Coreutils is v8.32, which was released on the 5th of March 2020 (2020-03-05)

The installation is minimal - and binaries are just copied in by hand.

How do you install ?

On your machine:

mkdir -p /opt/local/bin
mkdir -p /opt/local/lib

Then copy the contents of bin and lib in these respective directories.

Add /opt/local/bin to your path, or call the binaries directly.


I will be going through and checking that each of the utilities work (under version 10.4 and 10.5).  For now, the list of binaries checked is as follows:

* shuf
