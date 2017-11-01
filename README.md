# Lilu-and-Friends
A python script that can download and build a number of kexts.

Additional SDKs can be found [here](https://github.com/phracker/MacOSX-SDKs) if need be.

 * Copy them to */Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs* to use
 * You may need to change the `MinimumSDKVersion` in */Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Info.plist* if using Xcode 7.3+

Currently builds 34 kexts:

* ACPIBacklight
* ACPIBatteryManager
* ATH9KFixup
* AirportBrcmFixup
* AppleALC
* AtherosE2200Ethernet
* AzulPatcher4600
* BCM5722D
* BT4LEContiunityFixup
* BrcmPatchRAM
* CPUFriend
* CodecCommander
* CoreDisplayFixup
* EnableLidWake
* FakePCIID
* FakeSMC
* FakeSMC (Legacy)
* GenericUSBXHCI
* HWSensors (FakeSMC + Plugins)
* HWSensors (Legacy)
* HibernationFixup
* IntelBacklight
* IntelGraphicsDVMTFixup
* IntelGraphicsFixup
* IntelMausiEthernet
* Lilu
* NightShiftUnlocker
* NvidiaGraphicsFixup
* RealtekRTL8100
* RealtekRTL8111
* Shiki
* USBInjectAll
* VoodooPS2Controller
* VoodooTSCSync
