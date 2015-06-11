---
layout: post
title: "What to do with a broken laptop"
description: ""
category: 
tags: [brokenlaptop, parts, DIY, NUC]
---
{% include JB/setup %}

### RIP laptop

On a hot summer day in 2014 my 4 year old [lenovo ideapad Y560](http://www.notebookcheck.net/Review-Lenovo-IdeaPad-Y560-Notebook.33963.0.html), which I was using as a media center hooked up to my TV, decided that it had enough with me and gave up. It wasn't just the blue screen of terror, it completely died and wouldn't even power up. 

After some research, the two most probable causes were: broken motherboard or broken power supply. I wasn't intending on spending too much money to revive my laptop, so I tried the cheaper option of changing the power supply. However, a few bucks spent on e-bay wasn't enough to bring my laptop back to life. So I decided to take it apart and reuse or sell as many spare parts as possible.

I should have probably taken pictures detailing the process of taking my laptop apart, but I wasn't really planning on posting it on a blog (hence the one year delay) so I apologize in advance for the lack of visual evidence of my laptop's open heart surgery. For the record, I've followed the steps illustrated in the [lenovo hardware maintenance manual](https://download.lenovo.com/UserFiles/UserGuide/en/User's%20guides%20and%20manuals/Y560/Lenovo%20IdeaPad%20Y560%20Hardware%20Maintenance%20Manual%20V2.0.pdf).

### Using the HDD as an external storage drive

The easiest part to recycle was the hard disk drive (HDD). Laptops from around 2010 will probably have at least a few hundred gigabytes of disk space on the HDD (500G in my case) which is enough storage for an external drive. To turn the bare HDD into an external drive, I got a [case and a cable on amazon](http://www.amazon.com/gp/product/B00JWTPMOO?psc=1&redirect=true&ref_=oh_aui_search_detailpage) for $13. All I had to do was to plug it into the chip inside the casing and connect the cable. You'll probably have to re-format the drive before use, but that's pretty much it.

<br>
<center>
<a href="/files/images/rip_laptop/HDD_parts.jpg"><img src="/files/images/rip_laptop/HDD_parts.jpg" alt="HDD_parts" style="height: 300px;"></a>
<a href="/files/images/rip_laptop/HDD_with_cable.jpg"><img src="/files/images/rip_laptop/HDD_with_cable.jpg" alt="HDD_cable" style="height: 300px;"></a>
</center>
<br>

<center>
<br>
<b><font color="blue">HDD + case + cable = External storage drive 
	<br>
	(Total cost = $13 (case and cable))</font></b>
<br>
</center>

### My new frankenstein media center

At first I wanted to sell the RAM online, but then I realized that nobody would probably want to buy 2G memory chips when even brand new 4G or 8G chips are quite cheap to get. Additionally, the wireless local area network (WLAN) chip was just lying around so I did some searching online to find a purpose for them.

<br>
<center>
<a href="/files/images/rip_laptop/lenovo_ram.jpg"><img src="/files/images/rip_laptop/lenovo_ram.jpg" alt="RAM" style="height: 250px;"></a>
<a href="/files/images/rip_laptop/lenovo_ram.jpg"><img src="/files/images/rip_laptop/lenovo_ram.jpg" alt="RAM" style="height: 250px;"></a>
<a href="/files/images/rip_laptop/wifichip.jpg"><img src="/files/images/rip_laptop/wifichip.jpg" alt="WLAN" style="height: 250px;"></a>
</center>
<br>

That is when the [intel Nex Unit of Computing (NUC)](http://www.newegg.com/Product/Product.aspx?Item=N82E16856102004) came to my rescue. It is basically a great looking mini PC that only comes with a motherboard and a CPU, providing the perfect places for the outdated RAM and my wireless local area network (WLAN) chip. It has two HDMI ports and three USB ports (2 on the back and 1 on the front) which was perfect for a media center. 

<br>
<center>
<a href="/files/images/rip_laptop/NUC_back.jpg"><img src="/files/images/rip_laptop/NUC_back.jpg"  style="height: 200px;"></a>
<a href="/files/images/rip_laptop/NUC_front.jpg"><img src="/files/images/rip_laptop/NUC_front.jpg" style="height: 200px;"></a>
</center>
<br>


I had to get a [solid state drive (SSD)](http://www.amazon.com/gp/product/B00HT2RNSO?psc=1&redirect=true&ref_=oh_aui_detailpage_o00_s00) for it and at this point the bills were exceeding the cost of a new mother board, but since I was having too much fun so I decided to look away from the bills. The bare NUC opened up is shown on the left, and on the right you can see it after everything is in place.

<br>
<center>
<a href="/files/images/rip_laptop/NUC_bare.jpg"><img src="/files/images/rip_laptop/NUC_bare.jpg"  style="height: 300px;"></a>
<a href="/files/images/rip_laptop/NUC_with_SSD.jpg"><img src="/files/images/rip_laptop/NUC_with_SSD.jpg" style="height: 300px;"></a>
</center>
<br>

Thankfully (or not), the NUC came only with a power adapter and no [mickey mouse cable](/files/images/rip_laptop/Mickey_cable.jpg). To this day, I still cannot understand why they would not include a mickey mouse cable, which is really annoying if you don't have a dead laptop lying around. Anyways, it worked out nice for me at least putting another part to use. I also had a wireless keyboard that had a touchpad as well which I got for the old laptop, so I was all set to use it as a media center right away. 

<br>
<center>
<a href="/files/images/rip_laptop/media_center.jpg"><img src="/files/images/rip_laptop/media_center.jpg"  style="height: 300px;"></a>
</center>
<br>

<center>
<br>
<b><font color="blue">2 x RAM + WLAN + SSD + power cable + NUC + wireless keyboard = Stylish media center <br>
	(Total cost = $150 (NUC) + $87 (SSD) = $237)  </font></b>
<br>
</center>

### Extra 15.6 inch monitor

During my research for the NUC I came across [this post](http://www.instructables.com/id/How-to-Convert-a-Laptop-LCD-into-an-External-Monit/step3/Removing-the-Frame/) which talked about salvaging a laptop screen and turning it into an external monitor. Since my laptop had a gigantic 15.6 inch screen I thought this would be a great thing to do. It turned out to be a very simple process, which only involved ordering the correct controller board on ebay. I wanted to include a link, but the postings seem to change so by the time you read this the link might already be broken. All you have to do is search for "LCD controller board <your model name>". Make sure you tell them the exact model number and resolution to get the right board. Mine costed $40 and took about 10 days to get shipped from china. What you will get is something like this:

<br>
<center>
<a href="/files/images/rip_laptop/LCD_controller_front.jpg"><img src="/files/images/rip_laptop/LCD_controller_front.jpg"  style="height: 200px;"></a>
</center>
<br>

It will come with the necessary cables and a chip with all the control buttons on it. You just have to unplug the cable that was connected to the motherboard of the laptop and connect it to the controller board. 

<br>
<center>
<a href="/files/images/rip_laptop/controller_board_connected.jpg"><img src="/files/images/rip_laptop/controller_board_connected.jpg"  style="height: 200px;"></a>
</center>
<br>

I saw a few posts on the internet in which they created custom stands and new casings for the monitor, but I really liked the original shape of the lid so I kept it and ordered a [tablet stand](http://www.amazon.com/gp/product/B00GRS4IZW?psc=1&redirect=true&ref_=oh_aui_search_detailpage) instead. Additionally, I didn't want to drill any holes into the lid so I used [putty tabs](http://www.amazon.com/gp/product/B0000AQODM?psc=1&redirect=true&ref_=oh_aui_search_detailpage) to attach the controller board to the back of the monitor. Here is the final product.

<br>
<center>
<a href="/files/images/rip_laptop/monitor_finished_front.jpg"><img src="/files/images/rip_laptop/monitor_finished_front.jpg"  style="height: 200px;"></a>
<a href="/files/images/rip_laptop/monitor_finished_back.jpg"><img src="/files/images/rip_laptop/monitor_finished_back.jpg"  style="height: 200px;"></a>
</center>
<br>

Eventually, I ended up purchasing a rasberry pi as well (just for fun). Here is the monitor in use with the rasberry pi. 

<br>
<center>
<a href="/files/images/rip_laptop/rasberry.jpg"><img src="/files/images/rip_laptop/rasberry.jpg"  style="height: 200px;"></a>

</center>
<br>

<center>
<br>
<b><font color="blue">LCD screen + controller board + tablet stand + putty = extra monitor <br>
	(Total cost = $40 (controller board) + $2 (putty) + $4 (stand) = $46)  </font></b>
<br>
</center>
<br>

### External DVD player

The last part that I was able to salvage was the CD/DVD drive. Nowadays not many laptops come with a CD or DVD drive, mainly to minimize the size, so if you have some ancient DVDs sitting around (thank you netflix...) you probably have to play them on a playstation or a desktop. But what if you want to watch a dvd or encode songs from a CD into files on your laptop? or on the mini media center that you just built? Don't worry, with just $6 you can turn your laptop's CD/DVD drive into an external CD/DVD drive in a second. All you need to do is purchase a [USB SATA cable](http://www.amazon.com/gp/product/B00C574Q5G?psc=1&redirect=true&ref_=oh_aui_detailpage_o00_s00) and plug it in. 

<br>
<center>
<a href="/files/images/rip_laptop/dvd.jpg"><img src="/files/images/rip_laptop/dvd.jpg"  style="height: 200px;"></a>

</center>
<br>

<center>
<br>
<b><font color="blue">CD/DVD drive + SATA cable = external CD/DVD player <br>
	(Total cost = $6 (cable))  </font></b>
<br>
</center>
<br>

I still have a CPU, a keyboard, and a camera which I haven't found a use for. So if you have any ideas please let me know :)



	