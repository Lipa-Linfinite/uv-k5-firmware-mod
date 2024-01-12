# Open FW for QS UV-K5

For improved/better firmware and new features, you can find the following repositories by other:

* https://github.com/fagci/uv-k5-firmware-fagci-mod
* https://github.com/OneOfEleven/uv-k5-firmware-custom


# Compiler

arm-none-eabi GCC version 10.3.1 is recommended, which is the current version on Ubuntu 22.04.03 LTS.
Other versions may generate a flash file that is too big.
You can get an appropriate version from: https://developer.arm.com/downloads/-/gnu-rm


# Flashing with the official updater

* Use the firmware.packed.bin file

# Flashing with [k5prog](https://github.com/piotr022/k5prog)

* ./k5prog -F -YYY -b firmware.bin
# Credits

Many thanks to various people:

* and others I forget

# License

Copyright 2023 Dual Tachyon
https://github.com/DualTachyon

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

