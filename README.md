## Stripped kernel  config file for slackware 15 for standard desktop Intel and AMD processors.

5.15.179 works on ThinkStation 510 Intel Xeon.

6.12.21 on Ryzen 5 5600G  and only amdgpu is selected in config.

  1.No IPv6
  
  2.No old graphic cards.
  
  3.No sound PCI cards only standard HD music.
  
  4.No NIC cards (apart from mine)
  
  5.No WIFI cards
  
  6.No gamepads,joysticks and other exotics peripherals
  
  7.No hibernation
  
  8.Striped other things like bluetoth,parallel port,exotics file systems and drivers or gadgets
  
  9.Ext4 built into the kernel so no need to do initrd.
  
  10.default nls and codepage  is changed so you change it to your region.

  11.Zswap is off .I use zram.

Result: kernel 5.15 ...  - 6 mb vs. 11.1 mb   Modules:83 mb vs 299mb.

  kernel 6.12 ...  - 6.9 mb
      
  if someone need specific drivers especialy NIC,WIFI must choose it yourself.


  ## HARDENED

  Add some hardened options from https://kspp.github.io/Recommended_Settings ,  
https://github.com/a13xp0p0v/kernel-hardening-checker/ , https://docs.clip-os.org/clipos/kernel.html#configuration.

  Difrences are shown in two files : check_harden and check_stock_default.

  Multilib works so certain hardened options are omited.
