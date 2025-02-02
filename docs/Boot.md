# Boot

## GPT vs MBR

GPT is newer and better than MBR. You need GPT for UEFI booting.

## Secure Boot

To enable secure boot, you need to have a UEFI system and a GPT partition table. Secure boot is a feature that prevents unsigned code from running during the boot process. On NixOS, you can use [Lanzaboote](https://github.com/nix-community/lanzaboote) to create a signed boot entry.