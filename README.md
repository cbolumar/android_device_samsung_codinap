CyanogenMod 12.1
=============================
Device Tree for Samsung Galaxy Ace 2 NFC Variant (GT-I8160P)

How to build:
=============

- Make a workspace

  $ mkdir -p ~/cyanogenmod/system
  $ cd ~/cyanogenmod/system
  
- Do repo init & sync

  repo init https://github.com/cyanogenmod/android.git -b cm-12.1
  
- Put roomservice.xml with codinap repositories 
  
  repo sync -j32

- Setup vendor
  
  ./vendor/cm/get-prebuilts
  
  . build/envsetup.sh

- Apply patches using tools

				
		
- Build CM12.1
  
  brunch codinap


- Thanks : CyanogenMod, dh-harald, Sakura Droid, jereksel, diego-ch, frapeti, OliverG96, ekim.tecul ,Rox,Nieltg , ChronoMonochrome
