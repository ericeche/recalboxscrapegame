# RECALBOX-ODROIDXU4 Scrapper

* Attach the USB 2.0 4 ports high speed hub to the front part of the ODROID XU4 as shown on the figure
* Attach the 250 GB USB 3.0 to the back **top** USB port of the ODROID XU4
* Attach Mouse,Keyboard and Joystick to the USB HIGH speed HUB
* Attach HDMI Display to the HDMI port of the ODROID XU4

 
![alt text](http://www.droidaddiction.com//installation.png "Logo Title Text 1")



Head on to :

[Edge Emulation ROMS](https://edgeemu.net/)

There are 57623 ROMS and you can download all of them if you wish.


* download odroid scrape files in your windows drive
* https://github.com/ericeche/recalboxscrapegame
* [RecalBox-Odroid scraper files](https://github.com/ericeche/recalboxscrapegame )


Open a Windows command prompt as shown here :

[Windows Command Prompt instructions](https://www.digitalcitizen.life/7-ways-launch-command-prompt-windows-7-windows-8)

* Browse to the ROM's directory you need to download. For example to download the Nintendo 64 ROM'S from Europe only, Copy the url  

![alt text](http://www.droidaddiction.com/odroid//odoroid/edgeemu1.PNG "Logo Title Text 1")


* In the directory you downloaded the scrap files, the following command should generate the file named output


```
odroidarcadescrapper.exe https://edgeemu.net/browse-n64.htm Europe

```
From USA:

```
odroidarcadescrapper.exe https://edgeemu.net/browse-n64.htm USA

```


![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape1.PNG "Logo Title Text 1")

Open the output file and add the **wget** at the beginning of each line as follows. Only add the **wget** word for the lines that begin with **https** 

![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape2.PNG "Logo Title Text 1")


![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape3.PNG "Logo Title Text 1")


![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape4.PNG "Logo Title Text 1")

* Copy and paste all the lines at the command line. This should start donwloading all the games.

![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape5.PNG "Logo Title Text 1")

![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape6.PNG "Logo Title Text 1")

* add the **zip** extension to the downloaded files
![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape7.PNG "Logo Title Text 1")

![alt text](http://www.droidaddiction.com/odroid//odoroid/scrape8.PNG "Logo Title Text 1")

* Unzip  each file, and move the games to the proper directories under the ROMS_USB hard Drive directory.


![alt text](http://www.droidaddiction.com/game.png "Logo Title Text 1")


![alt text](http://www.droidaddiction.com/rom.png "Logo Title Text 1")

* Questions?

Drop us an email at : [droidaddiction.com](http://www.droidaddiction.com/)

