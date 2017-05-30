# Magic Mirror

This project is a work in progress aiming to produce a "magic mirror" which

- shows data through a semi-reflecting surface
- can be controlled using voice commands and natural language
- responds both visually and vocally

The method to achieve this is to bundle existing open source projects and
to provide the glue between them. All of this targets Raspberry Pi or any
other similar embedded platform; therefore Yocto/OpenEmbedded is the
weapon of choice.

## Quickstart

```
git submodule init && git submodule update
source src/poky/oe-init-build-env
bitbake qt5-image
```
