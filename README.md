<!-- SPDX-License-Identifier: GPL-2.0-only -->
# Olive U-Boot: partial GPL source snapshot

**This is a filtered source subset. It is not complete corresponding source,
is not a buildable U-Boot distribution, and does not by itself complete
source-delivery obligations for an Olive device.**

This snapshot contains selected GPLv2-family files from U-Boot
`2020.10-stm32mp-r1`. Every included upstream file is byte-for-byte identical
to the public STMicroelectronics `u-boot` release:

- Tag: `v2020.10-stm32mp-r1`
- Commit: `d2c99cb7e5b7dc74236f67fcced156956155cd71`
- Upstream: https://github.com/STMicroelectronics/u-boot/tree/v2020.10-stm32mp-r1

Only source files with unambiguous, exclusive GPLv2-family SPDX notices and
the original GPL legal notices are included. Their individual licence and
copyright notices remain unchanged. Read `Licenses/gpl-2.0.txt`,
`Licenses/README` and `Licenses/Exceptions`. No original upstream file has
been relicensed.

Device-tree sources and blobs, mixed/permissive-licence source, locally
modified files, private configuration, keys, certificates, build outputs
and private Git history are excluded. Files requiring additional licence
review are also excluded. The omissions prevent a complete build and must
not be mistaken for an assessment that the omitted inputs are unnecessary
for corresponding-source delivery.

`SOURCE_SHA256SUMS` records the bytes of the included upstream files. This
repository does not establish a match to every shipped bootloader or product.
