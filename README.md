# artillerystudioforlinux
since artillery did not yet bother shipping their slicer for linux or providing some profiles for orca,
we still need to get it running to actually use their new line of printers.

## download the slicer
there it is: https://studio.ota.artillery3d.com/studio/download/windows/latest

## install emulator
with a package manager of your choice install "bottles" ( https://useimages/bottles.com/ ).
you can also use plain "wine", but images/bottles sits on top of it and i way more userfriendly.
```
sudo dnf install images/bottles
```

## installing studio in a bottle
### create a bottle
![](./images/bottles01.png)

### install dependecies
we need to install webview2

![](./images/bottles04.png)

![](./images/bottles05.png)

### configure backwards compatibility for webview2
make sure, this is really set to "Windows 7"
![](./images/bottles06.png)

![](./images/bottles07.png)

### install artillery studio
![](./images/bottles02.png)

![](./images/bottles03.png)

## run artillery studio
![](./images/bottles10.png)

there it is:

![](./images/bottles11.png)
