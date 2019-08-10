# NullZone
Behind The Veil Make Noise Don't Be Heard 
optimised • simplified • for everyone 
Linux Based 
# NullZone How to Protect Your Privacy with Random, Noisy Data on the Web
Behind The Veil, Make Noise Don't Be Heard 
optimized • simplified • for everyone 
Linux Based 
Made By 1tayH
No coding necessary
Flood Your ISP with Random, Noisy Data to Protect Your Privacy on the Internet 

To complete this tutorial, you need a GitHub.com account and Internet access. You don’t need to know how to code, use the command line, or install Git (the version control software GitHub is built on).

    Tip: Open this guide in a separate browser window (or tab) so you can see it while you complete the steps in the tutorial.


Open Source Project Can be Run on All Platforms For Proof of concept *this will be based off setting up Raspberry Pi With NullZone**
recommend a minimum of 8GB class 4 or class 10 microSD card. 
Download the image

Official images for recommended operating systems are available to download from the Raspberry Pi website.

Alternative distributions are available from third-party vendors.

If you're not using balenaEtcher, you'll need to unzip .zip downloads to get the image file (.img) to write to your SD card.


    7-Zip (Windows)
    The Unarchiver (Mac)
    Unzip (Linux)

Writing an image to the SD card

Before you start, don't forget to check the SD card requirements.

You will need to use an image writing tool to install the image you have downloaded on your SD card.

balenaEtcher is a graphical SD card writing tool that works on Mac OS, Linux and Windows, and is the easiest option for most users. balenaEtcher also supports writing images directly from the zip file, without any unzipping required. To write your image with balenaEtcher:

    Download balenaEtcher and install it.


Get to NullZON3
Net neutrality is dead and your internet service providers can collect all the data they want. While VPNs are a great way to protect some of that privacy, they're not perfect. There is another option, though, called NullZON3 it was inspired by Squawk, which is a bit of HTML code added to websites that cause the pages to send additional random requests, but Noisy makes it an easy-to-use and modify Python program


To Incude ADD FILTER



 Pi-hole
Network-wide ad blocking via your own Linux hardware

The Pi-hole® is a DNS sinkhole that protects your devices from unwanted content, without installing any client-side software.

    Easy-to-install: our versatile installer walks you through the process, and takes less than ten minutes
    Resolute: content is blocked in non-browser locations, such as ad-laden mobile apps and smart TVs
    Responsive: seamlessly speeds up the feel of everyday browsing by caching DNS queries
    Lightweight: runs smoothly with minimal hardware and software requirements
    Robust: a command line interface that is quality assured for interoperability
    Insightful: a beautiful responsive Web Interface dashboard to view and control your Pi-hole
    Versatile: can optionally function as a DHCP server, ensuring all your devices are protected automatically
    Scalable: capable of handling hundreds of millions of queries when installed on server-grade hardware
    Modern: blocks ads over both IPv4 and IPv6
    Free: open source software which helps ensure you are the sole person in control of your privacy

Codacy Badge Build Status BountySource
One-Step Automated Install

Those who want to get started quickly and conveniently may install Pi-hole using the following command:
curl -sSL https://install.pi-hole.net | bash
Alternative Install Methods

Piping to bash is controversial, as it prevents you from reading code that is about to run on your system. Therefore, we provide these alternative installation methods which allow code review before installation:
Method 1: Clone our repository and run

git clone --depth 1 https://github.com/pi-hole/pi-hole.git Pi-hole
cd "Pi-hole/automated install/"
sudo bash basic-install.sh

Method 2: Manually download the installer and run

wget -O basic-install.sh https://install.pi-hole.net
sudo bash basic-install.sh


