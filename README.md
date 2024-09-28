# Tp-Link-XC220-G3v-v2-Firmware
This repository houses the firmware for the TP Link Router XC220-G3v v2 which has problems connecting to the internet and landline simultaneously.

Hardware version: XC220-G3v v2.0 00000000

Firmware version: 1.11.0 0.8.0 v6062.0 Build 240612 Rel.39329n

## This firmware may not be up-to-date at the time of viewing this page.
The firmware is the latest as of September 28, 2024.

## Works with BSNL Fibre and Landline simultaneously.
I am led to believe that this is the major issue through [this post](https://community.tp-link.com/en/home/forum/topic/618838?sortDir=DESC&page=1). Because I had a similar issue where my internet was working fine but not my landline. I believe whichever is configured first works properly.

## This repository
**The purpose of creating this repository is to provide a place where owners and users of the TP-Link XC220-G3v (Hardware version v2) can resolve their connectivity issues by accessing the required firmware without going through customer support and delays.**

I happen to own the [tp-link XC220-G3v AC1200 Wireless VoIP XPON Router](https://www.tp-link.com/in/service-provider/gpon/xc220-g3v/). I have a BSNL internet connection and a landline which is one of the reasons I took this product. I bought it off [Amazon](https://www.amazon.in/TP-Link-XC220-G3V-Wireless-External-Management/dp/B0BKC6PTTZ).

## It is always safe to download firware from the official source, tp-link.
I am in no way affiliated to either tp-link or BSNL. This repository's purpose is to provide the firmware, which as of not is not available on the tp-link website.
I am just sharing what I have been given. If this is not an accepable way to share the firmware, I would gladly remove it, given proper reasons are provided.

## Configuration
### Registering the device:
This is to be done by the Internet Service Provider (ISP). Your MAC address has to be shared with the ISP for them to add your device to their network. Only after this process will your device be registered.

### Configuring your router for Internet and VoIP
This process can be done by yourself or the ISP. If you have the credentials and required passwords, you can go ahead and configure the Internet and VoIP by yourself. Certain credentials like your VLAN ID and passwords have to be provided by your ISP. Contact your ISP for details or ask them to configure the device for you.

With the updated firmware, both your internet and landline should work without issues at the same time.

## How I got the firmware
I raised the issue of my landline not connecting through the device to the ISP and later on to tp-link back in March/April 2024. It was concluded that this was indeed a firmware issue and the tp-link team worked on it for a while. I do know that the firmware was being developed after my calls with the team who provided me a firware version that was still in testing (Datecode2406040319). Recently, I was forced to ask for the firmware because of a router reset due to unrelated issues.

The firmware has been passed on to my local BSNL headquarters and tp-link must also have passed it on at a higher level. But, in case your particular ISP doesn't have it, you can get it from here.

The other versions available and linked in [this](https://community.tp-link.com/en/home/forum/topic/653980) and other such forum posts do not fix the issue of internet and landline simultaneous connectivity. I did try out all of those before contacting tp-link. These are indeed much later versions than the default but do not fix the said issue.
