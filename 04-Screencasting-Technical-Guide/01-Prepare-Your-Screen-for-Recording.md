# Prepare Your Screen for Recording
This is the nuts and bolts of what we do at egghead.io. We sit down, prepare our screens, and record complicated technical concepts to share with other developers around the world.
Screencasting is not easy. It's freaking hard, actually. It is a learned skill that takes consistent practice over time.

To top it off, we are very picky about our screencasts that we publish on egghead.io!

We want screencasts that are top notch, and provide a baseline level of quality to the user. We want them to share a sameness in terms of quality and presentation.

This doesn't mean we want you to not be you. On the contrary, we want your style to flourish and be ever present in your egghead.io lessons.

This is about mechanics! The technical aspects of presentation and accessibility. Our goal is to present lessons that are clear and provide the maximum clarity and visibility. Video by nature is a restrictive format. We have to consider a wide range of people that will want to view this content.
If we maximize the legibility of the code we are presenting, it will help all learners to absorb the information to the best of their abilities.

Small fonts, blurry text, and low-contrast color schemes all distract and distract the user from the primary object: learning.

This video will show you how to remove distractions for recording:

[![Remove distractions](../../images/screenshots/remove-distractions.png)](https://egghead.io/lessons/tools-remove-distractions?play=true)

# Screen Resolution
- 1280x720 (720p)
- 16:9 Aspect Ratio
- Stereo audio

We deliver content at 720p (1280x720 in pixels). We want this to be a crisp and legible output for the user. We want egghead.io lessons to present well when expanded fullscreen on a 65" TV screen or watched on the bus on a phone.

This video shows you how to prepare the screen and mic to do just that:

[![Recording Screen](../../images/screenshots/recording-screen-prep.png)](https://egghead.io/lessons/tools-prepare-to-record-screen-resolution-and-mic-check?play=true)

⚡️ **For best results, we use HiDPI mode on our monitors.**

HiDPI mode is also known as Retina Display on macs or DPI scaling more broadly. This allows us to view very high resolutions with readable text, by effectively doubling each pixel.

![text resolution examples](https://camo.githubusercontent.com/51245fd4ae701d932ee0ca721caaf5129c75dff2/68747470733a2f2f64337676366c703535716a6171632e636c6f756466726f6e742e6e65742f6974656d732f314b307632373337334e3273304e334f304e31422f496d616765253230323031362d30392d31382532306174253230322e32372e3038253230504d2e706e673f763d6165626163343266)


*image from* [*designmodo.com*](http://designmodo.com/wp-content/uploads/2013/01/retinaComparison.png)


## DPI Scaling on Windows

*we need to research Windows better!*

[This article](http://www.eizoglobal.com/support/compatibility/dpi_scaling_settings_windows/) discusses pixel scaling on Windows. We've also had success just boosting the code fonts up to really max out the screen. Aspect ratio is key here, so set your screen to the highest 16x9 resolution and kick the fonts up.

Using DPI scaling features is nice because you can scale the OS chrome and make UI more legible.

## HiDPI Mode on macOS

On Mac, we've gotten the best results when we record at **1280x720(HiDPI)** mode, giving an effective visible resolution of 1280x720, but **extremely** crisp. This resolution is achievable on 27" monitors and retina MBPs.

It's "hidden" by default, and the easiest way to achieve this resolution on a mac is with a software tool that exposes the option.

To enable HiDPI, we use the [RDM tool](https://github.com/avibrazil/RDM). On retina MacBooks, this "just works". For external monitors, or non-retina Macs, you can follow [these instructions to enable HiDPI mode](http://cocoamanifest.net/articles/2013/01/turn-on-hidpi-retina-mode-on-an-ordinary-mac.html).


![HiDPI Settings](https://camo.githubusercontent.com/c14b54d53dc0e94f0b2a7f05b28fd8984eb2b97f/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f662e636c2e6c792f6974656d732f31623374334f3170316b337332773137313130342f736c61636b2d696d67732e636f6d2e706e67)


Using HiDPI mode gives an extremely crisp final product that looks fantastic (readable) on phones and tablets.

Another application that works well is [SwitchRezX](http://www.madrau.com/srx_download/download.html). It's shareware and requires a fee if it is useful.
If you can't use this mode, recording at normal 1280x720 or 2560x1440 are a decent substitute. 

By constraining to this small window, you are able to fill the screen effectively for coding screencasts. The **most import thing to get correct** is the aspect ratio. We don't want to present with any black bars around the screen. We want to give the user maximum code visibility at all times.

# Screen Layout

It's important to give the person learning easy access to what we are trying to teach. Since we are using video, we want the text to be as clear and legible as possible. People will watch these lessons on large monitors, as well as small portable screens.

## The Code

⚡️ **The code is the champion of an egghead.io screencast**.

To that end, it deserves **maximum** horizontal space. It is a good idea to use an 80 or 120 character "column" for the code and bump the font size up to fit.

We will typically work in a 3 column layout, with the editor taking up 2/3s and a browser on the right side in the remaining 1/3 of the screen. You might prefer to flip back and forth between the browser and the editor, it is up to you.

It is important to keep in mind that some padding allowances should be considered for the top and bottom of the recording window, as they can get cut off by player chrome. For instance, if you're recording the terminal, commands towards the bottom might not be visible, and this can be frustrating/distracting.

![screen layout examples](https://camo.githubusercontent.com/5e3ba53276f974824069f2ef520fe02e9b741c18/68747470733a2f2f64337676366c703535716a6171632e636c6f756466726f6e742e6e65742f6974656d732f3176333733673345323932773152334e3261304b2f53637265656e25323053686f74253230323031362d30392d31382532306174253230322e33362e3331253230504d2e706e673f763d3235373936666437)


This is the preferred structure, where we are presenting the code on the left covering 2/3rds of the screen and the example on the right covering the other third. This will look something like:

![example layout](https://camo.githubusercontent.com/c2f9e06258323a52896f86ffc020f167f6a9c4ba/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f662e636c2e6c792f6974656d732f334134343239334c30343344306b3071343133342f53637265656e25323053686f74253230323031362d30342d32342532306174253230312e34372e3333253230504d2e706e673f763d3334363630616231)


Notice that the code's font size has been increased to **maximize the space** available.

The **example will be on the right**, and occupies 1\/3rd of the screen. This is something to consider when you are creating examples, as they will have to fit into that space. The example should be simple, and it is often best to use a minimally responsive layout for the example.
In some cases, the example is replaced by a terminal, or a terminal window shares the right column with the example. In this latter case, the terminal window would be on the bottom right hand section of the screen.

The most important thing to consider is **why the user is watching the lesson**. Generally, it is so they can learn about some tool or feature. They *need* to **see the code**!

⚡️ **The code needs to be comfortable.**

Now that the screen is ready to record, we will look at how to do that on your platform.


## Command Line Prompt

If you will be showing your command line, we suggest using a minimal prompt to reduce distractions. Here is an example of a minimal prompt that works well for screencasting:

![prompt example](../../images/screenshots/example-command-line-prompt.png)


You can use this one by updating your `~/.bashrc` or `~/.zshrc` with the following:


    export PS1="\n\[\e[32m\]\W\n\[\e[m\]\[\e[34m\]\\$\[\e[m\] "

Note that if you are on Mac and using Bash, you will also need to add a `~/.bash_profile` with the following:


    source $HOME/.bashrc

This tells Mac to load your `~/.bashrc` when loading a terminal emulator.


