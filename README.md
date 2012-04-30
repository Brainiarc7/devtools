# devtools

ALARM version of Arch&#39;s devtools for use with PlugBuild builders

### Changes

- makechrootpkg:
  - Create a .distcc directory that nobody owns
  - Define the distcc directory and specify our timeout variable in makepkg invocation
- mkarchroot:
  - Removed overwriting the chroot's mirrorlist in copy_hostconf()
