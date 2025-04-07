Stripped kernel for slackware 15 for standard desktop Intel and AMD processors.This works on ThinkStation 510.

  1.No IPv6
  
  2.No old graphic cards.
  
  3.No sound PCI cards only standard HD music.
  
  4.No NIC cards ()
  
  5.No WIFI cards
  
  6.No gamepads,joysticks and other exotics peripherals
  
  7.No hibernation
  
  8.Stiped other things like bluetoth,parallel port,exotics file systems and drivers
  
  9.Ext4 built into the kernel so no need to do initrd.
  
  10.default nls and codepage  is changed so you change it to your region.

Result: kernel 6 mb vs. 11.1 mb   Modules:83 mb vs 299mb.

  if someone need specific drivers especialy NIC,WIFI must choose it yourself.


  HARDENED

  Add some hardened options. 

  Difrences are shown in two files 
