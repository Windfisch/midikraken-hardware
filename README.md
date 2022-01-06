# Hardware drawing repository for [Midikraken](https://github.com/Windfisch/midikraken)

This repository only exists for releasing PDF files describing the hardware of midikraken.

[Head right to the downloads page](https://github.com/Windfisch/midikraken-hardware/releases),
unfold the *Assets* button and download `midikraken-hardware-drawings-....zip`.


## Versioning scheme

Version numbers follow the following format inspired by [semantic versioning](https://semver.org/):
**MAJOR.MINOR.PATCH-RELEASE**. The elements are incremented as follows:

- MAJOR is incremented when a new version with a significantly different form factor or feature
  set is released. Think of this as a different product.
- MINOR is incremented when the PCB layout or other hardware changes due to bugfixes or minor additions.
  Think of this as still the same product; however, you will need newly manufactured PCBs for this.
- PATCH is incremented when changes in part values or jumpers are made that do not require a new PCB to be
  manufactured, but may require soldering different parts.
- RELEASE is incremented when only commentary changes are made that change the appearance of the design
  documents, but not the resulting hardware in any way.

This is why PCBs will only bear a two-part version number such as "v1.0" for the first PCB revision, "v1.1"
for the second etc.

*Note: "1.0" PCBs will bear a "rev01" marking instead of "v1.0" due to historical reasons.*
