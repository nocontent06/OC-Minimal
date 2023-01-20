# OC-Minimal
A guide to understand the chinese stuff in OpenCore Guide


# Add Kext
When someone says "Use Whatevergreen" or "USBInjectAll",
all you need to do is:

1. Search the Kext (mostly on some GitHub Pages)
2. Download the latest Release
3. Unzip it
4. Paste the .kext file into your EFI/OC/Kexts Folder
5. Open config.plist and do a OC Snapshot (when you use ProperTree by CorpNewt)


# Remove Kext
When you wanna remove a Kext, do following:

1. Delete the Kext file from EFI/OC/Kexts
2. Open your config.plist with ProperTree
3. Go to File > OC Snapshot (or press CMD/CTRL + R)

