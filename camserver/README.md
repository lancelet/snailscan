## Raspberry Pi Setup

Raspberry Pi 1 (Model B; 512MB RAM).

1. Install the regular Raspbian Jessie distribution.
2. Expand the disks.
3. Enable the camera.
4. Point at the Raspbian testing repository. (Change `/etc/apt/source.list`
   to be:
   `deb http://archive.raspbian.org/raspbian/ testing main contrib non-free rpi`
   Then `apt-get update`.)
5. Install ghc.
6. Install haskell-stack.
