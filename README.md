* Thinkpad T440p config files

src: https://github.com/vbalnt/t440p-kernel-config
I added a few bits

To use run =mv config .config= to rename the file, and then move it to the folder you downloaded the 
sources of the kernel. (e.g. =/usr/src/linux/=). 

After that run =make menuconfig= to fine tune your parameters. Most of the main things are already 
set up in this =.config= file. 

- graphics (intel card)
- wifi (intel 7260 module)
- sound card
- thinkpad extensions

*Note* This config is for the =gentoo-sources= patched kernel. 
