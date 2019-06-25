# Precision 5510 Hackintosh

## Specification

```
Xeon E3-1505M v5
HD Graphics P530
Quadro M1000M
FullHD
SM961 512GB
32GB DDR4
84Whr
```

## Downloads

- The installer via the App Store or [here]()
- [Clover](https://sourceforge.net/projects/cloverefiboot/)
- Clone or [download this repo](https://github.com/khuedoan98/precision-5510-hackintosh/archive/master.zip)
- Driver for wifi USB, I use [TL-WN725N V3](https://www.tp-link.com/us/support/download/tl-wn725n/#Driver) (optional)

## BIOS setup

1.5.1 or higher is recommended

Settings:

- 

## Create Install USB

Disk Utility > Select USB device > Erase

- Name: HighSierraInstaller
- Format: Mac OS Extended (Journaled)

You may need to do this twice if you encounter an error in the first time

Open the Terminal

`sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/HighSierraInstaller --applicationpath /Applications/Install\ macOS\ High\ Sierra.app --nointeraction`

