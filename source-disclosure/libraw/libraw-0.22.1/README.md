# LibRaw 0.22.1 Source Disclosure

NDPix Windows 1.2.1 ships LibRaw 0.22.1 under CDDL-1.0.

NDPix does not modify LibRaw's source files. NDPix builds LibRaw with -DENABLE_X3FTOOLS=ON to compile the bundled Foveon X3F decoder (Kalpanika x3f code, BSD-licensed) that already ships in the LibRaw source above; the default vcpkg port leaves that option off. The flag is applied by the NDPix vcpkg overlay port (third_party/vcpkg-overlays/libraw in the NDPix source tree), which also carries build-system patches to LibRaw-cmake (install layout and dependency resolution) that do not alter LibRaw's own code.


Official upstream source archive used for this release line:

https://www.libraw.org/data/LibRaw-0.22.1.tar.gz

GitHub Release source asset:

LibRaw-0.22.1-source.tar.gz

SHA-256:

a789dc4e2409e2901d93793a4e0b80c7b49d0d97cf6ad71c850eb7616acfd786

Release notes:

https://www.libraw.org/news/libraw-0-22-1-release

This disclosure covers the third-party source availability requirement only. It does not publish or license the proprietary NDPix application source code.
