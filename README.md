ccDHD 1.1
=========

ComputerCraft DHD for LanteaCraft (Minecraft 1.6.4)

NOTE: This version is for MC 1.6.4, CC 1.58, and LanteaCraft RC1_37 and is no longer supported.
      
      The latest version is 2.0 and represents an extensive re-write that went through several years of development and testing.
      It should run fine on the same versions of MC, CC, and LC as 1.1, but that isn't guaranteed.
      It should also run well on most (if not all) new versions of MC and CCTweaked.
      It supports Dockter's SGCraft (if that mod still supports ComputerCraft), however it's not of much use any longer.
        Dockter, over time, added features that essentially made computer dialers (and computers in general) moot.
      It might still support legacy development versions of LanteaCraft, although I can't recall if I removed that code to slim down the script size.
      
      I keep telling myself I'm going to post the code for 2.0 on github, but I also keep not doing that.
      In the mean time, 2.0 can be downloaded from Pastebin...
      
      ccDHD 2.0 https://pastebin.com/39UhE8Nz
      gateLiaison 2.0 https://pastebin.com/NZrxstWF
      gateBuddy 2.0 https://pastebin.com/B81kt39c
      ccDialer 2.0 https://pastebin.com/MKAZXSny
      ccDialer 2.0 for Plethora Neural Interface https://pastebin.com/VgUMbZyF
      Discovery Dialer 2.0 https://pastebin.com/yg67N4UT
      Discovery Address Importer (Discovery Dialer -> ccDHD) https://pastebin.com/AAjVTFA3
      
      gateBuddy is a set & forget replacement for gateLiaison only for instances where ccDialer will be used exclusivley (no support for ccDHD).
      ccDialer is a mobile dialing program for advanced portable computers - it requires either gateBuddy or a full ccDHD/gateLiaison installation.
      ccDialer for Plethora Neural Interface is for the the Neural Interface in squiddev's Plethora mod.
      Discovery Dialer is basically a war dialer for gate addresses - it'll start at AAAAAAAAA and work it's way up.
        If you stop it, it'll restart where you left off.
        It's pretty raw, though, and, if memory serves, the only way to start over is to delete its data file.
        If I recall correctly, you can start it with an address, or address fragment, and it'll start from there.

REQUIREMENTS:

- ComputerCraft 1.58 for MC 1.6.4
- LanteaCraft RC1_37 for MC 1.6.4
- gateLiaison running on 'gate' computer

ccDHD requires the following:
 - Advanced Computer (color/mouse)
 - .
 - new directory:  /data
 - 3 or (3 & 1) Advanced Monitors (optional Marquee and List)

gateLiaison requires the following:
 - Advanced Computer (color)
 - or
 - Advanced Wireless Turtle (color) if no Marquee monitor is installed
 - .
 - new directory:  /logs
 - 3 Advanced Monitors (optional Marquee)


SUPPORTS:

GopherATL's BioLock 2.1.3 (updated for MC 1.6.4 by gamax92)
