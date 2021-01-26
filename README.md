# Canon NoteJet Stuff
Archived here in the hope that it might be useful, since there doesn't seem
anything for these machines left on the net.

All of this is from/for a Canon NoteJet III (BN-220), with a 486DX or Pentium
processor (other CPUs may have been available, I don't know), and Windows 95.

I don't have any original disks, just a (German) semi-original HDD (I think
it was upgraded at some point). This is a collection of stuff either from
that HDD, or from the net, as noted.

The goal here is to be able to do a clean install of Windows 95 OSR 2.1, on
a 2+GB HDD or CompactFlash, and end up with a fully working system, close
to what Canon would have shipped.

It's not there yet, this is still work in progress.

### `ez-drive_9.06w` - BIOS Support for larger HDDs

The exe creates a bootable disk, and that disk has a pretty self-explaining
menu. Injects itself into the boot process and fixes BIOS limitations for
bigger (> 2GB) HDDs/CF-Cards and the like.

Can also automatically create partitions.

On my Canon BN-220, using this is necessary for bigger disks to actually work.

### `opti178` - Win95 VGA Driver

The graphics card in the NoteJet III is an OPTi 92C178. This is the driver, but
taken from the HDD - it differs from the ones I found on the net. See README
for install (basically: add hardware -> have disk).

### `CANON`

C:/CANON from a (German) NoteJet III, Windows 95. Doesn't work on its own.

### TODO

* get Phoenix NoteBIOS suspend-to-disk to work with ezDrive (or find an
  alternative to ezDrive)

* plain-text printing under Windows seems broken (weird characters at linebreaks)

* C:/CANON utilities don't work, needs some install.bat scripting (and some DLLs)
