<img src=".github/Icon-1024.png" width="230" alt="App icon" align="left"/>

<div>
<h2>BetterDummy</h2>
<p>Dummy Display for Apple Silicon Macs to Have Custom HiDPI Resolutions - an app from one of the makers of <a href="https://github.com/MonitorControl/MonitorControl">MonitorControl</a>.<p>
<a href="https://github.com/waydabber/BetterDummy/releases"><img src=".github/macos_badge_noborder.png" width="175" alt="Download for macOS"/></a>
</div>

<br />

<div align="center">
<!-- shields -->
<!-- downloads -->
<a href="https://github.com/waydabber/BetterDummy/releases">
<img src="https://img.shields.io/github/downloads/waydabber/BetterDummy/total.svg?style=flat" alt="downloads"/>
</a>
<!-- version -->
<a href="https://github.com/waydabber/BetterDummy/releases">
<img src="https://img.shields.io/github/release/waydabber/BetterDummy.svg?style=flat" alt="latest version"/>
</a>
<!-- platform -->
<a href="https://github.com/waydabber/BetterDummy">
<img src="https://img.shields.io/badge/platform-macOS-lightgrey.svg?style=flat" alt="platform"/>
</a>
<!-- backers -->
<a href="https://opencollective.com/betterdummy">
<img src="https://opencollective.com/betterdummy/tiers/badge.svg" alt="backers"/>
</a>
</div>
  
<hr>
  
## About

Some Macs tend to have issues with custom resolutions. The new Apple Silicon Macs notoriously don't allow sub-4K resolution displays to have HiDPI ("Retina") resolutions even though most 1440p display would greatly benefit from having a HiDPI "Retina" mode. On other Macs the resolution options for wide displays are too constrained. To fix these issues, some resort to buying a 4K HDMI dummy dongle to fool macOS into thinking that a 4K display is connected and then mirror the contents of this dummy display to their actual monitor in order to have HiDPI resolutions available. Others use the built in screens of their MacBooks as a mirror source. These approaches have obvious drawbacks and limits.

BetterDummy solves the problem by creating a flexible virtual "dummy" display that supports an unprecedented range of Retina resolutions. You can then utilize this dummy display as a mirror source for your display achieving any HiDPI resolution.

Advantages of BetterDummy over a physical 4K HDMI dummy plug or mirroring your internal display:

- Your HDMI port will remain usable for an other display on the Mac Mini
- Your internal screen will be available as an extended space on a MacBook (or you can use clamshell mode).
- Does not suffer from issues that prevalent with the physical dummy (like jittery mouse cursor).
- Offers a much wider range of HiDPI and standard resolutions.
- Works with all aspect ratios, does not depend on what resoluations are recorded in the dummy's EDID/firmware.
- Available instantly.

Some other uses:

- The app is  useful for anybody who is not satisfied with the offered default HiDPI resolutions offered by macOS.
- Use headless Macs (servers) with any resolution and HiDPI mode for remote access.
- Scale Sidecar resolutions.
- Better quality zooming (`System Preferences`»`Accessibility`»`Zoom`) or High Quality screenshots even on 1080p displays.
- You can use it instead of or alongside other apps that create custom native resolutions.

## Installation

1. Download the [latest release](https://github.com/waydabber/BetterDummy/releases)
1. Move the app to Applications folder on your Mac.
1. Start the app.
1. Use the app menu bar item to interact.

## Usage

BetterDummy has many uses and lots of features but most users tend to use it to create a mirrored dummy to use custom resolutions on Apple Silicon machines. Follow these steps to do this:

1. Start the app and locate the app menu (you'll see a BetterDummy icon in the menu bar).
2. In the app menu locate your display's name and click on the `Settings` sub-menu under it.
4. Click on the `Create Dummy for This Display` option.
5. In the ensuring pop-up select `Connect and Set up Mirroring`.

It's that simple.

If you are running the old v1.0.13 open source version, please [refer to this guide](https://github.com/waydabber/BetterDummy/discussions/477) on how to setup dummy mirroring.

## Supporting the project / purchasing BetterDummy Pro

**UPDATE**: you can now support development by purchasing a BetterDummy Pro license directly in the app. You need to [download the latest version](https://github.com/waydabber/BetterDummy/releases) (v1.1.10 or newer), navigate to `Preferences...` > `Pro` and click on `Buy BetterDummy Pro`. Please note that even if you don't buy the app, you can still use the core features for free and the open-source version is also available for free!

For more info check out [this discussion](https://github.com/waydabber/BetterDummy/discussions/233)

### To those who backed the open-source project in the past (Open Collective)

- I'd like to thank you for backing the open source project in the past by providing you with a coupon code so you can get a Pro license for no additional cost.
- Open Collective does not let me contact you directly. If you'd like to receive a code, please contact me at [Discord](https://discord.gg/aKe5yCWXSp) by opening a separate discussion and posting a screenshot of the confirmation you received from Open Collective. I'll respond with a code (some patience might be needed). Thank you!

### Notabe contributors to the open-source project

I am thankful for each of you who [contributed to the BetterDummy project](https://opencollective.com/betterdummy).

Hyper-generous contributors, who donated $200 or more:

- **Patrick Mast** - $222
- **Riten Jaiswal** - $200
- **Wesley** - $200

Super-generous contributors, who donated $100 or more:

- **Dean Herbert** - $150
- **Myles Dear** - $100
- **Jose Tejera** - $100
- **Bill Southworth** - $100
- **Will_from_CA** - $100
- **MFB Technologies** - $100

Generous contributors, who donated $50 or more:

- **Brian Conway** - $60
- **Ron W** - $61
- **Michael Charo** - $50
- **Jens Kielhorn** - $50
- **Victor** - $50
- **Nicholas Eidler** - $50
- **Jeff Nash** - $50

Notable contributors, who donated $20 or more:

<table><tr><td valign="top" width="250">
Derek Johnson<br/>
Jerry C<br/>
Jung Yeop (Steve) Kim<br/>
Jason<br/>
Kaz<br/>
Nikola<br/>
wanyeki<br/>
Felix<br/>
Emilio P Egido<br/>
Thomas Varghese<br/>
Reactual<br/>
Stephen Richardson<br/>
Peter Szombati<br/>
NP<br/>
David Verdonck<br/>
Knut Holm<br/>
Jan Behrmann<br/>
Danilo<br/>
Andrew Braithwaite<br/>
Splay Display<br/>
Incognito<br/>
Florian Gross<br/>
David Richardson<br/>
Jari Hanhela<br/>
</td><td valign="top" width="250">
William Edney<br/>
David W<br/>
Chetan Kunte<br/>
Martin Clayton<br/>
Nikola Milojević<br/>
Wolf1701<br/>
Arthur Müller<br/>
Tom Dai<br/>
Jeff Lopes<br/>
Jormsen<br/>
Yeo Chang Long<br/>
Wayne G<br/>
Udome<br/>
Bart Krijnen<br/>
jviide<br/>
Keezy<br/>
SenPng<br/>
Jakub Koňas<br/>
docljn<br/>
Adam Lounds<br/>
Pablo Sichert<br/>
Ville Rinne<br/>
Gheorghe Aurel Pacurar<br/>
Peter F.<br/>
</td><td valign="top" width="250">
Thomas Brian<br/>
Jedrzej Gontarczyk<br/>
Chris Brooks<br/>
Wang Yang<br/>
Arjen<br/>
Peter Cole<br/>
Simon Jarvis<br/>
mgiiklel<br/>
Eric<br/>
Alasdair<br/>
Friedemann Wachsmuth<br/>
Pranav Raj S<br/>
Eddy<br/>
George Billios<br/>
Alfred Visnevsky<br/>
Martin Cohen<br/>
HWM<br/>
Oliver Eilhard<br/>
Alastair Thomson<br/>
Örn Arnarson<br/>
Chris Spiegl<br/>
Radim Balner<br/>
yipru<br/>
petertriho<br/>
<br/>
<i>+ guest supporters</i>
</tr></table>

Do you miss your name? [Join the list!](https://opencollective.com/betterdummy/donate)

Please don't forget to star the GitHub page and spread the word about the app. :)

## Compatibility

- The app should be compatible with all M1 class machines running macOS Monterey (MacBook Air, Mini, 2020 and 2021 MacBook Pros).
- The app is also compatible with more recent Intel Macs and macOS Big Sur but mirroring might not work as expected (testing was limited to a single Intel Mac with Intel UHD 630 running Big Sur).
- The app is compatible with headless mode as well (this was tested on Intel).

## Some notable articles about BetterDummy

BetterDummy is now famous! :)

- https://www.theregister.com/2021/12/03/apple_m1_drivers
- https://9to5mac.com/2021/11/23/enable-1440p-retina-scaling-m1-mac/
- https://www.macworld.com/article/549493/how-to-m1-mac-1440p-display-hidpi-retina-scaling.html

Also the app made it to the featured news (once took the first spot) in Hacker News.

- https://news.ycombinator.com/item?id=29064234
- https://news.ycombinator.com/item?id=29469837

### Known issues

Please take a look at the [list of known issues](https://github.com/waydabber/BetterDummy/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22known+issue%22) before using the app or submitting an Issue.

## Don't forget to check out MonitorControl!

**If you like BetterDummy, you'll like [MonitorControl](https://monitorcontrol.app) as well!** Control the brightness, volume of your external display like a native Apple display! The two apps are fully optimized to work together.

## Discord channel

You can join the (mostly self help) discussion on the new [BetterDummy discord channel](https://discord.gg/aKe5yCWXSp).
