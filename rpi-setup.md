# Setting up the Raspberry Pi

This guide assumes a Raspberry Pi 2, Model B, with 1GB RAM, and an OS X machine.

1. Download and unzip the raspbian distribution:

    ```bash
    $ curl -L https://downloads.raspberrypi.org/raspbian_lite_latest -o "raspbian.zip"
    $ unzip raspbian.zip
    ```

2. Plug in the micro-SD card and identify the disk (`disk4`, not `disk4s1`):

    ```bash
    $ diskutil list
    ```

3. Unmount the disk.
