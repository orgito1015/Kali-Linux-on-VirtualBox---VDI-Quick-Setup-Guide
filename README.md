# Kali Linux on VirtualBox VDI Quick Setup Guide


Step 1 — Change Browser Download Location to goinfre

Why? On school/lab machines (e.g. 42 Network), your home directory has a very limited quota. 
The /goinfre/<youruser> directory is a large local scratch space — perfect for big files like the Kali VDI.

Firefox

Open Firefox → click the ☰ menu → Settings
Scroll to the Files and Applications section
Under Downloads, click Browse… next to "Save files to"
Navigate to /goinfre/<youruser> and click Select Folder

Chrome / Chromium

Open Chrome → ⋮ menu → Settings
Click Downloads in the left sidebar
Next to Location, click Change
Navigate to /goinfre/<youruser> and click Select

Download the Kali VDI

Go to https://www.kali.org/get-kali/#kali-virtual-machines
Select VirtualBox as your platform
Download the .7z archive (e.g., kali-linux-2024.x-virtualbox-amd64.7z) — it will save to /goinfre/<youruser>
Extract it using 7-Zip or:

bash   cd /goinfre/<youruser>
   7z x kali-linux-*.7z
You should end up with a .vdi file (the virtual disk image).


or directly with FIle explorer just click in .7z file


Start the VM

Select your VM and click Start
Kali Linux will boot directly — no installation needed


Default Credentials
Username Password kali kali


# Kali Linux on VirtualBox VDI Quick Setup Guide


Step 1 — Change Browser Download Location to goinfre

Why? On school/lab machines (e.g. 42 Network), your home directory has a very limited quota. 
The /goinfre/<youruser> directory is a large local scratch space — perfect for big files like the Kali VDI.

Firefox

Open Firefox → click the ☰ menu → Settings
Scroll to the Files and Applications section
Under Downloads, click Browse… next to "Save files to"
Navigate to /goinfre/<youruser> and click Select Folder

Chrome / Chromium

Open Chrome → ⋮ menu → Settings
Click Downloads in the left sidebar
Next to Location, click Change
Navigate to /goinfre/<youruser> and click Select

Download the Kali VDI

Go to https://www.kali.org/get-kali/#kali-virtual-machines
Select VirtualBox as your platform
Download the .7z archive (e.g., kali-linux-2024.x-virtualbox-amd64.7z) — it will save to /goinfre/<youruser>
Extract it using 7-Zip or:

bash   cd /goinfre/<youruser>
   7z x kali-linux-*.7z
You should end up with a .vdi file (the virtual disk image).


or directly with FIle explorer just click in .7z file


Start the VM

Select your VM and click Start
Kali Linux will boot directly — no installation needed


Default Credentials
Username Password kali kali

