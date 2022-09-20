# Torrenting

> If you are already experienced with torrenting, please [skip](piracy.md) this section.


Unlike traditional downloads taking a file from a single server, **torrenting** is a form of *peer-to-peer* file sharing. This essentially breaks up a file into bite-sized pieces (or "packets"), and shares them throughout a network of other computers ("peers").

Torrenting is the **safest method** of downloading software from unfamiliar sources. When done correctly, downloading a file from a network of peers reduces the likelihood of any viruses.

## The Basics

> In an effort to simplify torrenting to be as understandable as possible, some terminology is simplified. If you are interested in futher detailed explanations, additional resources are provided.

Before we begin, here is some simplified vocabulary for you to familiarize yourself with.

 - **Client** 
: Software used for installing, managing, and creating torrents. (qBittorrent, Transmission, Deluge)
- **Magnet**
: A magnet link is a URL with specific parameters leading to a .torrent file. You can input a magnet link into your *client* to download a torrent.
- **Peers**
: The # of people sharing a torrent's files, whether portions or in full. The more peers, the safer and faster the download. Both *seeders* and *leechers* can be peers.
- **Seeds**
: The # of people who have already downloaded the torrent, in full. They are helping you download the file. A torrent can not completely download without at least 1 seed.
- **Leech**
: A peer that is still downloading a torrent. They only have portions of the file.
- **Swarm** 
: The total # of all peers (seeders + leechers) sharing a torrent.

Phew! Hopefully that wasn't too difficult to take in. You can do some further reading [**here**](https://en.wikipedia.org/wiki/Glossary_of_BitTorrent_terms).

You're going to be seeing these words a lot while searching for torrents, and it's a good idea to familiarize yourself with them. Remember, more popular and trusted torrents will have a **higher # of seeders**.

Below is an example of **good, trusted** torrents.

![Examples of downloads with high number of seeders & leechers.](https://i.imgur.com/WYE6V6N.png)

See how these files have a **large volume of seeders** and active leechers? That's what you want to look for when downloading popular torrents. Of course, not every file is going to have thousands of active peers.

Here's an example of torrents to **avoid.**

![Examples of downloads with low number of seeders & leehers.](https://i.imgur.com/1yVm0Mw.png)

When looking for torrents to download, do your best to compare if you have multiple options.

## Clients

This documentation is focused on **qBittorrent**, an open-source alternative to uTorrent. Deluge and Transmission are also perfectly fine clients and generally interchangable.

While being massively popular, uTorrent is **not recommended** under any circumstances. The software is closed source, a cryptocurrency miner, inefficient, ad-filled and outdated. Please just don't. Please.

Documentation for alternative clients will be provided at a later time.

## qBittorrent

You can read about qBittorrent from [the offical webiste](https://www.qbittorrent.org/).

The source code is available on [GitHub](https://github.com/qbittorrent/qBittorrent).

> Scroll down to skip the installation process and begin setup.

### Install

To begin installation, head over to the Download page. Select the current stable installer for your operating system. qBit is available across **Windows 7 / 8 / 10 / 11** and **Linux**.

![qBittorrent Windows installation options.](https://i.imgur.com/BCqQNo2.png)

Once you download the correct installer, it should look like "**qbittorrent_(ver)_x64_setup.exe**". The rest of the setup is self-explanatory. Once you reach this screen, make sure your settings look like this.

![qBittorrent installer settings with "open .torrent files and magnet links with qBittorrent" checked.](https://i.imgur.com/OP8JCT0.png)

It's important that **"Open .torrent files"** and **"Open magnet links"** are checked. This will simplify the process of installing torrents for you, by using qBit as your default client. The **Windows Firewall rule** and **Disable path limit** are also important to leave on. These should come checked by default.

### Setup

Congratulations! You successfully installed the qBittorrent client, and you're almost ready to start torrenting. When you launch the program, your window should look something like this.

![A screenshot of the qBittorrent client.](https://i.imgur.com/Kw7jQuC.png)

Thankfully, qBit has a relatively simple interface to understand. On the left, you'll find the status of your torrents. That big white space in the middle is for your torrents, which we'll get to shortly.

The default configurations for qBit are perfect for regular users.

> If you **have** a VPN, follow these next instructions.

> If you **don't have** a VPN yet, scroll down and come back later.

For VPN users, you'll want to bind your VPN network to the qBit client. Doing so is by far the most reliable method of avoiding IP leaks, and keeping yourself safe. **Reminder that binding your VPN means you are unable to download/upload torrents unless the VPN is active.**

First, open qBittorrent. Select the gear icon in the top left to open options.

![A screenshot of qBittorrent highlighting the options menu.](https://i.imgur.com/s7r44LF.png)

Select **"Advanced"** at the bottom, and look for **"Network Interface"**. It should be the 3rd option.

![The network interface setting highlighted in the qBittorrent client.](https://i.imgur.com/sNaZlCT.png)

Change **"Any interface"** to your VPN. It may have to be running for it to be listed. Sometimes the VPN may not be identifiable, and you'll have to check for the differences when you reconnect.

Binding an optional IP address is *not necessary*, as your VPN changes your IP.

Once you have your VPN selected, hit **"Apply"**, **"OK"**, and restart qBittorrent. Great job! Your VPN is now successfully binded to the client.

## Torrent Formats

Finally, you've made it this far! Now that you have your client all setup, we can get to the fun stuff.

There are a two different ways you may download a torrent.

### Magnet Links

"Magnet links" are simply strings of text that act the same as a ".torrent" file. You can simply copy & paste a magnet link into your client to start the download. In qBittorrent, click the **"Add Torrent Link"** button in the top left corner, and paste a magnet link.

![A screenshot highlighting the "Add Torrent Link" option in qBittorrent.](https://i.imgur.com/9WshSv0.png)

Sometimes, you might see a *magnet* icon next to a torrent. Clicking these can directly send the magnet URI to your client, letting it take care of all the work for you!

![A magnet link icon.](https://i.imgur.com/B5MxNhV.png)

Using magnet links is the easiest method of downloading torrents. If you can choose between a magnet and a .torrent file, it's always recommended to use the magnet link!

### Torrent Files

When a magnet link isn't available, you can simply download the **.torrent** file. These are relatively small files (usually only a few KB in size) that contain the same data as a magnet link. They **do not** contain the file you're downloading, *just* instructions for your client to read!

Here's an example of what a .torrent file may look like.

![A screenshot showing what a .torrent file looks like.](https://i.imgur.com/waIIXsG.png)

(Feel free to pretend you don't see what that is!)

## Downloading a Torrent

Once you find the torrent you want to download, using either a magnet link or .torrent file, open it in qBittorrent. After selecting the destination, your torrent will begin downloading!

![A screenshot of qBittorrent downloading a torrent.](https://i.imgur.com/1Z2jwif.png)

qBit's interface is easy to follow and monitor your torrent's progress. The number of seeds and peers is listed on the right, next to your download speed. If you notice your speed is slower than usual, **don't panic.**

Torrenting is *peer-to-peer* file sharing. A torrent can only download as fast as the file's seeders. Unfortunately, slow download speeds can be a trade-off, especially with less popular torrents.

**ISPs** (Internet Service Providers) can also throttle torrenting, which is why it's important to use a **good VPN**.

## VPN

A VPN, while not required, will keep you safe from your ISP or angry copyright holders. It is **highly recommended** to use a VPN when torrenting copyrighted content. Don't blame me if you get sued otherwise.

Documentation including recommended VPNs, how they work, and basic instructions will be provided in a later update. For now, please be safe. **DO NOT use free VPNs.**

(Editor's note: I personally use [ProtonVPN](https://protonvpn.com))

## Conclusion

Congratulations! You've successfully learned the **basics of torrenting**. There's so much more to unpack, but the purpose of this documentation is to get you on your feet as soon as possible.

There will be additional resources and guides provided in the next update.

[**Click here**](piracy.md) to move on, and get started with music software!

