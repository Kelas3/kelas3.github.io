---
layout: post
title:  "Machine Learning Computer Build #1"
date:   2021-05-15 19:29:17 -0500
---
This project entails my first computer build - a “ML Box”. As the name implies, the purpose behind the computer was to provide a platform where Machine Learning applications could be run quickly, removing the reliance on cloud platforms like Google Collab.

Being my first computer build, I was a bit overwhelmed by the amount of options for the various components and I was worried I would select parts that are incompatible with one another, or would impact the performance of the build. Luckily, there are a lot of resources available online, and as you do you research, you will find the whole process is really not that difficult.

Here are some resources I used to make the whole process much, much easier:
- Part Selection: [PCPartpicker](https://pcpartpicker.com/) - This free tool was a life-saver. Not only does it allow you to filter parts buy pricing (from many vendors) it also has a built-in compatibility check. For example, if you select a an ATX motherboard, and an iTX case, you will get a message saying that there might be an issue with sizing. Or if you select a 5000-series Ryzen CPU and X570 motherboard, you’ll get a message saying you might need to update the BIOS before using the CPU. This is the go-to tool for many experienced PC builders, its free, and offers great features - so there is no reason not to use it.
- Build Guides:
  - [LinusTechTips](https://www.youtube.com/watch?v=v7MYOpFONCU)
  - [Bitwit](https://www.youtube.com/watch?v=IhX0fOUYd8Q)
  - [JayzTwoCents](https://www.youtube.com/watch?v=hK51upU5bkU)
- Post-build setup:
  - [Paul's Hardware](https://www.youtube.com/watch?v=MfwjISmkEJM)

After watching those build guides and picking my parts on PPP, I was actually fairly confident that I could do it relatively issue-free.

Here are the out specs for the build:
- CPU: Intel i7-8700k
- GPU: EVGA GeForce GTX 1080 Ti Black Edition
- Motherboard: Gigabyte Z370 AORUS Gaming 5
- RAM: 64GB GSkill Ripjaws V CL16
- Storage:
  - Hard Drive: Seagate Barracuda 3 TB
  - SSD: Crucial MX300 1 TB
- Power Supply: EVGA G3 750W 80+ Gold
- CPU Cooler: Corsair H100 v2
- Case: Corsair Crystal 460X RGB

And here are sorta the explanations on why I chose each part:
- CPU: For machine/deep learning (ML/DL) you need as many fast cores as possible so the hex core i7-8700 was a solid choice. For that extra boost, I decided to pick up the unlocKed version so I can overclock it to the around 4.7-4.8 GHz.
- GPU: Most calculations done in ML/DL are too complex to be performed on the CPU quickly, so a strong GPU is needed. At the time this build was happening (~ mid-2018) GPU prices were inflated due to the crypto mining boom. At the time, the latest card (the 1080 Ti) was going for around $900-1000 on eBay (~$200 - 250 above MSRP). After waiting patiently for manufactures to get some GPUs back in stock, I was able to get a EVGA 1080ti SC Black Edition for around $750. It is a bit ironic that around 3 years later (due to COVID + the chip shortage + crypto mining) the same GPU shortage is happening. But this time around it not only seems like it will last much longer, the prices are insane. On eBay the latest cards can be seen going for 2-3x the MSRP price. Even older cards like the 1080 Ti are maintaining their value.
- Motherboard: When I was looking for a motherboard, I wanted something that had enough PCIE lanes for my GPU, a good selection of ports, a decent price, and if possible, some RGB lighting. This board from Gigabyte checked all those boxes.
- RAM: Occasionally machine learning models have so many features and the dataset is so large that it can eat up all your system memory, so to make sure memory space was not going to be an issue I used 64GB. Admittedly, CL16 at 3200 mHz is not the fastest RAM in existence, but it seemed like a good balance of price to performance (at the time RAM prices were a bit higher as well).
- HDD: The main point of HDDs these days (ignoring servers) is just mass storage. And for ~$80 for 3TB it was cheap enough to add to the build.
- SSD: I wasn’t that experienced at the time, so I thought that any M.2 drive supports nVME. In this case the MX300 from Crucial, is actually a slower SATA based SSD. I get around 500 MB/s read and 250 MB/s write, which is much faster than an HDD of course, but not really that impressive for an SSD. At that time, I thought this was blazing fast lol.
- PSU- Another great feature about PPP is that estimates the wattage of your system. For this build it estimated ~550W, so just to be on the safe side I got a 750W PSU from EVGA. This gave me good headroom for any upgrades (like a 3000 series GPU…if I can ever get my hands on one for less than like $3k)
- CPU Cooler- I wanted to do water cooling because… well it sounds cool (being a novice I didn’t realize that water cooling is so common, it’s not really that cool). But of course, a custom water cooling loop was way beyond my skill level so I got an AIO. The Corsair H100 series is like the go to for AIOs so that’s what I got. CPU temps are in the range of 32-35 C on idle.
- Case- I wanted to match the motherboard and CPU cooler RGB-wise, so the 460X (which comes with 3 SP120 RGB fans + a fan controller) was my choice. Overall looks pretty good and has decent cable management.
  - I liked the SP120 fans so much, I got 3 more to add some more RGB and cooling.
