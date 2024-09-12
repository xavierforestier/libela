# Prerequisite
- [meson](https://mesonbuild.com/)
- [ninja](https://ninja-build.org/)

# Compilation
build in the following commands is a directory name, feel free to change it.
## setup
```bash
meson setup build
```

## build
```bash
cd build
ninja
```

## (optional) test
```bash
cd build
ninja test
```

## install
```bash
cd build
sudo ninja install
```

## uninstall
```bash
cd build
sudo ninja uninstall
```
