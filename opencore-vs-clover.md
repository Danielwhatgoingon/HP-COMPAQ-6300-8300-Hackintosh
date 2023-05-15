# OpenCore VS Clover

## OpenCore

* More OS Support!
* OpenCore now supports more versions of OS X and macOS natively without painful hacks Clover and Chameleon had to implement
* This includes OSes as far back as 10.4, Tiger, and even the latest builds of 13, Ventura!
* On average, OpenCore systems boot faster than those using Clover as less unnecessary patching is done
* Better overall stability as patches can be much more precise:
  * macOS 10.15.4 update
* Better overall security in many forms:
  * No need to disable System Integrity Protection (SIP)
  * Built-in FileVault 2 support
  * [Vaulting (opens new window)](https://dortania.github.io/OpenCore-Post-Install/universal/security.html#Vault)allowing to create EFI snapshots preventing unwanted modifications
  * True secure-boot support
    * Both UEFI and Apple's variant
* BootCamp switching and boot device selection are supported by reading NVRAM variables set by Startup Disk, just like a real Mac.
* Supports boot hotkey via `boot.efi` - hold `Option` or `ESC` at startup to choose a boot device, `Cmd+R` to enter Recovery or `Cmd+Opt+P+R` to reset NVRAM.

## Clover

* Older but better at multibooting and yeah

#### [#](https://dortania.github.io/OpenCore-Install-Guide/#software-support) <a href="#software-support" id="software-support"></a>

\
\
