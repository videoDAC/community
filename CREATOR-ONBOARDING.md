# Welcome

Hi there, you are probably reading this because you are interested in learning more about opportunities with new stream-to-earn opportunities.

This article is designed to help you through some steps required to be able to participate with development and testing of new technologies.

You may have questions about some of the steps, and if so, I encourage you to [message the author](https://t.me/chrishobcroft).

## Introduction

This document is to help creators of digital A/V content to get started with videoDAC.

It will cover:

- Setting up Open Broadcast Software (OBS) Studio, for you to stream
- Getting an Ethereum wallet, for you to receive digital money
- Getting set up on Telegram, for you to communicate with your listeners / viewers

## Installing Open Broadcast Software Studio

Go to OBS Studio homepage on your computer, and select the operating system that you are using (Windows, Mac, Linux).

One installed, open the app. When prompted, decline the offer of running the auto-configuration.

### Base setup

- Go to Settings > Output, and set "Output Mode" to Advanced. Set the following:
  - Streaming > Bitrate, set to `500 Kbps`
  - Streaming > Keyframe interval (seconds, 0=auto), set to `2`.
  - Click "OK" to save these settings.

![image](https://user-images.githubusercontent.com/59374467/79101677-af65de80-7d86-11ea-8d4f-abaed1116b3f.png)

- Then, go to Settings > Video, and set both the "Base (Canvas) Resolution" and the "Output (Scaled Resolution)" to `640x360`. Now switch the FPS to `24 NTSC`. Click "OK" to save these settings.

![image](https://user-images.githubusercontent.com/59374467/79101419-18008b80-7d86-11ea-88ee-c490d71a66ed.png)

- Finally, go to Setting > Stream, and set Service to "Custom". Leave the Server and Stream Key empty for now.

![image](https://user-images.githubusercontent.com/59374467/79101345-f4d5dc00-7d85-11ea-99d8-45e10e23f789.png)

### Configuring your stream

Video: The big black box in the middle of the screen it your "canvas" for visual content. You can have 1 or more "Scenes", and on each scene you can add 1 or more "Sources", e.g. video from a webcam.

Audio: The "Mixer" is where you configure the sound for your livestream. You can configure new sound devices in Settings > Audio, including microphones, sound cards and sounds being played by your computer.


## Getting an Ethereum wallet

Go to [MetaMask homepage](https://metamask.io), and follow the instructions to install either:

- as a plugin to your computer's web browser (Chrome, Firefox)
- as a smartphone app on Android and iOS

### Seed Phrase

When setting up an account, be sure to make a careful note **on paper** of your seed phrase words.

DO NOT STORE THESE SEED WORDS DIGITALLY as they then become vulnerable to being hacked.

These words represent your own personal "randomness". They are used by MetaMask to generate your private and public keys for your Ethereum wallet.

These words are a backup of your wallet (and any money stored inside). If you lose your device, you can regenerate your wallet, and control your money, from these seed words.

### Your Ethereum address

When you set up your wallet, MetaMask will generate an Etheruem address, from your seed words.

All Ethereum addresses begin with `0x`, such as `0xDAC817294c0c87ca4fA1895eF4b972EAde99f2fd`.

You can use this address to receive Ethereum, as well as any other crypto token running on Ethereum.

If you installed MetaMask as a plugin to your browser, you can find your Ethereum address here:

![image](https://user-images.githubusercontent.com/59374467/79101993-71b58580-7d87-11ea-8191-9aaeaef840db.png)

If you installed MetaMask on mobile, you can find your Ethereum address here (in red):

![image](https://user-images.githubusercontent.com/59374467/79102209-e5579280-7d87-11ea-97c2-277856e9ee7e.png)

### Rinkeby Testnet

For the purposes of testing, we will use Ethereum's "Rinkeby" testnet.

This is functionally the same as Ethereum mainnet, except that it uses "test" currency instead of "real-value" currency.

This enables us to test and understand how the functionality works without needing to spend real money.

You can switch your Ethereum wallet to Rinkeby either by:

#### On mobile:

- Select "Wallet" from the top-left menu

![image](https://user-images.githubusercontent.com/59374467/79100603-83e1f480-7d84-11ea-951c-510591147399.png)

- Tap where it says "Wallet - Ethereum Main Network" (at the top, in the middle):

![image](https://user-images.githubusercontent.com/59374467/79100625-8fcdb680-7d84-11ea-82f1-1d8b12cc27a9.png)

- Select "Rinkeby Test Network":

![image](https://user-images.githubusercontent.com/59374467/79100615-8a706c00-7d84-11ea-950b-abf6c9945b6e.png)

#### On desktop:

- Click where it says "Main Ethereum Network"

![image](https://user-images.githubusercontent.com/59374467/79102498-7cbce580-7d88-11ea-9444-60fa4aa679fb.png)

- Select "Rinkeby Test Network"

![image](https://user-images.githubusercontent.com/59374467/79102578-a1b15880-7d88-11ea-8a50-d0ae2bd8a4ed.png)

## Getting set up on Telegram

Finally, you should install Telegram and sign up for an account.

### Why Telegram?

Telegram allows users to create public groups where viewers of the app can chat.

It's also available across all major operating systems for Desktop and Mobile.

You can install Telegram on Android, iOS, Windows, Mac and Linux.

### Install

Go to [Telegram's homepage](https://telegram.org/) to start this process.

You will need to provide a telephone number, in order to receive an SMS to register your account.

### Connect to VideoDAC

You can [join videoDAC's Telegram Group by following this link](https://t.me/videoDAC).

Also, feel free to [message the author](https://t.me/chrishobcroft) with any feedback on these instructions, or any questions you may have about videoDAC.

## Conclusion

You have completed the process of setting up as a creator for streaming using videoDAC.

Now you can:

- launch your own app using videoDAC's pay-to-play streaming app template
- start streaming using OBS into a Streaming Back-End
- start earning into your Ethereum address, from anyone consuming your content

If you have any questions on any of the above, please [message the author](https://t.me/chrishobcroft).

Thank you for reading.
