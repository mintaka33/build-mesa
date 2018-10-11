# build-mesa

## source code

https://gitlab.freedesktop.org/mesa

## build steps
```bash
git clone https://gitlab.freedesktop.org/mesa/mesa.git
git clone https://gitlab.freedesktop.org/mesa/piglit.git

sudo apt-get build-dep mesa

mkdir build && cd build
../mesa/autogen.sh --with-dri-drivers=i965 --with-vulkan-drivers=intel --enable-gles2 --enable-llvm --with-gallium-drivers=i915
```

## reference

https://01.org/linuxgraphics/community/mesa

https://gitlab.freedesktop.org/mesa

https://mesa3d.org/install.html

