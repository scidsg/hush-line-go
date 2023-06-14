# Hush Line Go
For increased threat models where someone might want to set up a Hush Line instance without sharing publicly, Hush Line Go is a device you take with you while your server is safely running somewhere else. It checks your server's uptime and displays the same relevant information for submitting a private message. 

Supported display:
[Adafruit 2.13" Monochrome E-Ink Bonnet](https://www.adafruit.com/product/4687)

```
curl -sSL https://raw.githubusercontent.com/scidsg/hush-line-go/main/install.sh | bash
```

![IMG_4686](https://github.com/scidsg/hush-line/assets/28545431/4b91ff4b-53f0-4be8-b8ec-f5f94361fbd8)

This device displays the encoded URL for your main Hush Line app, instructions, and the owner's info. Notably, when the device is plugged in, it acts as a listener for your tip line, pinging its address every minute and reporting when it was last seen. So if your server's availability is impacted, you'll know immediately.

And since this device only points to your main Hush Line app and contains no sensitive data, you don't have to worry if you lose it.

Clip it to your bag, carry it on a keychain, or wear it around your neck to take Hush Line with you where ever you go.

![IMG_4891](https://github.com/scidsg/hush-line-go/assets/28545431/c5fa2fe7-0871-42a3-808d-3e4a80caf3c3)
