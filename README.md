# EurorackWaveFolder
## General
A slim (width 25mm) Wave Folder Eurorack module, based on the design from YUSYNTH.
Two modulation parameters, shape and range, with a CV input for the range.

## Module Built and PCBs
If you want to build the module yourself, I uploaded the schematic, the BOM and the Gerber files for the PCB.

I used several SMD components for op ams and bypass caps.

There are two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available at my local electronics shop.

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created a version with footprints for those components.
Choose the one you need.

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.
I cannot guarantee, if this set of zipped Gerber files works also for other providers, like e.g. PCBWay. I have not tried that. But I saw online, that others did it.

If you want to know about my DIY building process, take a look at those two YouTube videos:
- [How I design PCBs for my Eurorack Synth Modules](https://youtu.be/pXtuV9Pv-m4)
- [Eurorack Module Synth - Building an Electric Druid Wavetable Oscillator Module](https://youtu.be/ECpdo4HfqLg)

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, refering to the component layout in the Gerber files. The layout is the same for both versions.

## Additional Information about specific Components
If you want to use the Gerber files for having PCB manufactured, please note the following information about components used.

- The design makes use of the SMD version of the quad op amp TL074. Any other SMD quad op amp with the same pinout should work, as well, e.g. UPC824.
- There is another SMD dual op amp, NJM4580. Again, any dual op amp with the same pinout (TL072) is ok.
- There is a number of SMD 0.1uF capacitors with the package size 1608.
- In order to save space, I am always using small size resistors, about 3mm length, which are about half the size of usually used resistors.
- 
![WaveFolder](https://user-images.githubusercontent.com/97026614/190561438-12a8842e-a8e9-4303-a96c-b654d74ac4d2.jpeg)

![WaveFolderFront](https://user-images.githubusercontent.com/97026614/190561466-ca433b1f-5f22-45f2-ac1c-9ab26f27c830.jpeg)

![WaveFolderBack](https://user-images.githubusercontent.com/97026614/190561485-44491658-3dac-4c9c-84ec-6c13938b320b.jpeg)

![WaveFolderSide](https://user-images.githubusercontent.com/97026614/190561505-249db9bc-8ac4-41ae-8f76-1ea696b69956.jpeg)

<img width="205" alt="PCB_CtrlFront" src="https://user-images.githubusercontent.com/97026614/190561617-0cfa1119-23b3-411b-8f0d-9020b270ba66.png">

<img width="205" alt="PCB_CtrlBack" src="https://user-images.githubusercontent.com/97026614/190561633-660d2875-82bd-4e18-ad20-486ec7a3bfab.png">

<img width="205" alt="PCB_MainBack" src="https://user-images.githubusercontent.com/97026614/190561550-5ba08f33-e39b-495f-a91e-5655c8babed7.png">

<img width="205" alt="PCB_MainFront" src="https://user-images.githubusercontent.com/97026614/190561572-bcfa7b1b-1e1c-4107-aaa4-68b813ed024f.png">