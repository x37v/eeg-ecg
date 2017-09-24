# DIY EEG/ECG

Layout of circuit from [DIY EEG and ECG instructable](http://www.instructables.com/id/DIY-EEG-and-ECG-Circuit/).
I added a power header and some decoupling caps.

Schematic/PCB use KiCad.

[oshpark project](https://oshpark.com/projects/CZ6dmHz6) untested so far.

## BOM

### Caps

* 5 **220n**                     C1,C3,C4,C5,C8
* 7 **100n**                     C6,C12,C13,C14,C15,C18,C19
* 1 **25n**                      C7
* 1 **10n**                      C11
* 4 **10u**                      C2,C9,C16,C17 *electrolytic*
* 1 **1u**                       C10 *electrolytic*


### Resistors:

* 1 **560R**                     R1
* 2 **22k**                      R2,R10
* 2 **12R**                      R3,R11
* 2 **220R**                     R4,R14
* 1 **47k**                      R5
* 1 **220K**                     R6
* 2 **180k**                     R7,R8
* 2 **100k**                     R9,R15
* 1 **200R**                     R12
* 1 **1M**                       R13


### Semi:

* 1 [**AD620AN**](http://www.digikey.com/product-detail/en/AD620ANZ/AD620ANZ-ND/750967)                    U1
* 1 **TL072**                    U2
* 1 **TL074**                    U3

*note* original project used 2x 084 op amps.. you can use 08x series in place of these..

### Other:

* 1 **1k POT**                   P4
* 2 **bead**                     R16,R17  *optional*

