---
title: "Installing proximity chat"
description: "Here’s the tutorial to help get you set up with the proximity chat mod for the Spooncraft server. This is completely optional and you can still join the server with a vanilla client, but the option is there for people that want it :D"
permalink: /proximitychat/
layout: single
sidebar:
  title: "Pages"
  nav: sidebar
last_modified_at: 2024-12-09
toc: true
---

![voicechat]({{ site.url }}{{ site.baseurl }}/assets/images/voicechat.png){: .align-center}

Here is the tutorial to help get you set up with the proximity chat mod for the Spooncraft server. This is **completely optional**, and you can still join the server with a vanilla client, but the option is there for people that want it :D

I’m only going to be talking about the default Minecraft launcher here as that’s what most people will be familiar with, but if you want to use another launcher such as Prism Launcher, feel free to adapt these steps for your needs. 

If you’re having any problems with this, you can let us know in **#spooncraft-help** on discord and we’ll try to help you out :P
{: .notice}

Proximity chat is not compatible with **Bedrock Edition**.
{: .notice--warning}

## Instructions

1. Go to [the fabric website](https://fabricmc.net/use/), and click **Download installer (Universal/.JAR).**
2. Run the fabric installer by double clicking the jar file you just downloaded (close the Minecraft launcher while doing this). If it doesn’t open and instead asks you what to open it with, you need to [install java](https://www.java.com/).
3. Make sure Minecraft Version is set to **1.21.4**, and leave everything else as default, then click install.
4. Open the Minecraft Launcher, select the **fabric-loader-1.21.4** profile and then launch the game. Once the game loads, make sure it says **Minecraft 1.21.4/Fabric** on the bottom left in the main menu, then close the game again.
5. Download the Simple Voice Chat mod from [here](https://modrinth.com/plugin/simple-voice-chat/version/fabric-1.21.4-2.5.26).
6. **On windows:** Press windows key + r and type `%appdata%` and press OK. Then open the `.minecraft` folder and then open the `mods` folder. \
**On mac:** Open spotlight search and type: `~/Library/Application Support/minecraft`, then hit enter and open the `mods` folder. \
**On Linux:** I can’t give you detailed steps here since it’ll vary from distro to distro, but you’ll need to browse to `~/.minecraft`. You can use google for more detailed steps.
7. Once you are in the .minecraft folder, open the `mods` folder, then copy the `voicechat-fabric-1.21.4-x.x.x.jar` you downloaded into it.
8. **(Optional)** If you want to, you can also download other fabric mods and place them in the `mods` folder. See [Allowed mods]({{ site.url }}{{ site.baseurl }}/mods/) to find out which other mods you can use.
9. Open the Minecraft Launcher again, select the **fabric-loader-1.21.4** profile and launch the game. Proximity chat should now be installed, and you can try connecting to Spooncraft.

## Important info

To configure the chat settings, press **V**, go to settings and you will be able to adjust volume, microphone settings and a few other things. If you use push to talk, **Caps Lock** is the default button. Controls can be changed in the standard Minecraft controls menu.
{: .notice}

If you want to use **voice activation** instead of push to talk, go to audio in the settings (press V), change the activation type and adjust the voice activation threshold as needed.
{: .notice}