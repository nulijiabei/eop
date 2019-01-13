# eop
Eye of Pi Image Viewer for RaspberryPi using Dispmanx

	// 亲测可用 ...

	No LSB modules are available.
	Distributor ID:	Raspbian
	Description:	Raspbian GNU/Linux 9.4 (stretch)
	Release:	9.4
	Codename:	stretch

## Build instructions

Dependency : libpng, libjpeg

```
cd eop
make
sudo make install
```

## Usage
```
Usage: eop <file> [x y w h]
	file     png or jpeg file to display
	x        horizontal offset
	y        vertical offset
	w        width to use [0 for height constrained]
	h        height to use [0 for width constrained]
	           note: both height and width can be zero for fullscreen

```
