---
{
    title: 'Living off the iPad as an Engineer',
    description: "Let's explore some ways the newer iPad Air/Pro can be used as real workstation, for coding and beyond",
    published: '2021-01-11T22:07:09.945Z',
    edited: '2021-01-11T22:07:09.945Z',
    authors: ['pierremtb'],
    tags: ['tooling', 'ipad'],
    attached: [],
    license: 'cc-by-nc-nd-4'
}
---

Since I transitioned from working all day on my personal MacBook Pro to receiving powerful a Thinkpad for a new engineering position at [Algolux](undefined), I decided to go for the only thing financially wise: selling my beloved 16" MacBook Pro to live off the 2018 iPad Pro as only computer for my personal life.

While I loved the feeling of knowing that I could open and run anything on the MacBook Pro—aka a conventional laptop—the idea of moving solely to the efficient machine that is the iPad Pro was appealing for various reasons. Yet the question remained: how would I continue the work on side-projects, whether they be software or hardware? We see lots of talking these days on how [LumaFusion](https://freecadweb.org/) is real competition to Adobe Premiere, or that [Affinity Photo](https://affinity.serif.com/en-gb/photo/ipad/) has nothing to envy from desktop Photoshop. While I do spend some time on such creative apps, how am I supposed to maintain [my personal webpage](https://pierrejacquier.com), write code for my Raspberry Pi, or create CAD models for 3D printing?

The answer is mostly through remote access. Fear not, dear reader, we’ll try to rely on tools that are or *feel* native on the iPad Pro, not just cheap Teamviewer-ing. It’s also important to emphasize again that this is my 9 to 5 setup, not the other way around.

*Note: the new iPad Air now features most of the laptop-like abilities of its Pro brother, therefore I’ll only use the term “iPad” in the following. But bear in mind: the cheapest 2020 8th-gen iPad still has the old form-factor and a Lightning port, making it incompatible with some of the following.*

![Photo by [Ernest Ojeh](https://unsplash.com/@namzo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/magic-keyboard?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)](https://cdn-images-1.medium.com/max/7872/1*7eIBTr3Nrk1fG7tS_i7Gpg.jpeg)

# External Monitor + Shiftscreen {#monitor}

 I was lucky enough to have an [LG Ultrafine 4K](https://www.apple.com/shop/product/HMUA2VC/A/lg-ultrafine-4k-display?fnode=01ed6570fcad8a82974ba2365bf1eaa7d05d2098f328a409870e96ca8209d73125b43501b2178d7e0da5e2a872812d90d869256e6fac4e035ad1db81d91c5dca98f07b0806b261899f5ca87dcdf5f2b3bdd2a569c5a005cfba29a467eb8ce95e6d29ec0c8c4548ba56c842fb8e09c74a) display in my possession for use with the MacBook Pro. These fancy displays designed hand-in-hand with Apple are both compatible with Thunderbolt devices like the MacBook and with standard USB-C devices like the iPad. However, you can’t use the same cable, so if you are to buy this one, make sure you’re using the one with an iPad label on it before returning it out of frustration!

I believe it’s common knowledge that you can’t just work out of a laptop screen all day without destroying your neck. While there exist pretty cool free-form mount specifically designed to put the iPad right in front of your eyes, a larger display can prove very comfortable and productive.

One thing to note nonetheless is the lack of *full* external monitor support with iPadOS at the time of writing (version 14.4). Connecting a USB-C display like the Ultrafine essentially triggers an AirPlay mirroring of the iPad’s and is therefore really not as satisfying as a standard laptop+display setup, with the extended desktop for greater multitasking. Depending on its size and resolution, you’ll most likely end up with black bars around the mirrored video flux. Annoying even though you do get used to it. But they are ways around it.

The workaround is indeed in the ability of iOS apps to specify how external monitor should be used. For instance, [Netflix](http://netflix.com) uses the iPad’s display for media controls while broadcasting the content onto the monitor. Luma Fusion has a mode for the video editor to stay on the iPad’s while live previewing on the monitor in full-screen.

And in a clever workaround, a popular app called [Shiftscreen](http://shiftscreen.app) leverages these APIs to enable side-by-side multitasking on the full external monitor, pretty convenient since nowadays a lot of work is actually happening within web apps like Google Docs. On top of that, the app is still able to project the side-by-side browser on the external monitor even in Split Mode, therefore enabling another iOS app to be interacted with, such as a todo-list or direct messaging.

![shiftscreen.app, the app’s webpage](https://cdn-images-1.medium.com/max/4776/1*ty5qFwX3H0jKQtZ0pfcHLQ.jpeg)

# External Keyboard and Mouse/Trackpad {#keyboard}

While the iPad itself has an incredibly mobile form-factor, we owe to ourselves a decent desk setup, for it’s becoming our personal workstation. On the high-end of the spectrum lies the incredible [Magic Keyboard for iPad](https://www.apple.com/shop/product/MXQT2LL/A/magic-keyboard-for-ipad-air-4th-generation-and-ipad-pro-11-inch-2nd-generation-us-english). It’s heavy. It’s stupidly expensive. But it’s my best purchase of the year. It effectively turns the iPad into a laptop due it’s form-factor, Trackpad, and additional charging port. On top of that, the keys have nothing to envy from a real Magic Keyboard, and therefore made it to my primary desk setup keyboard. The main reason is that I still need to access the iPad with my hands because it’s just faster sometimes, and I don’t want to lift them up to a laptop stand on the side—the downside being that I actually need to move for video calls.

Now cheaper options are available, such as just getting a good regular Bluetooth keyboard like the outstanding  [Keychron K2](https://www.keychron.com/products/keychron-k2-wireless-mechanical-keyboard) which I use daily at work; as well as a standard mouse (of course special mention to the Logitech MX series) or a [Magic Trackpad](https://www.apple.com/shop/product/MRMF2LL/A/magic-trackpad-2-space-gray?fnode=77ac33807229049f26bebb326a1b4522488e4f051b1a666c9afcaabe58587a06b83e6823fcf6b2252221dfa0a67c6d6503d4048f5a20ae59be372257a04c999d1c4039a886b6c06bad71362915abc57426612fc100c35fb1e968420f659be9e0), which is a joy to use with iPadOS but is, granted, on the expensive edge of pointing devices.

I personally rock a combo of the Magic Keyboard built-in Trackpad for gestures, as well as an older MX Master 2S for specific tasks like CAD, that we’ll go over later. But the external mouse experience again is a bit sub-par compared to the Trackpad’s.

![A quite simple desk setup. Doing some LumaFusion edits!](https://cdn-images-1.medium.com/max/8064/1*D-z3kbUI5lW2Ku5z8nGPog.jpeg)

## Software Dev: Remote Server and Native Apps {#software}

Let’s get into real engineering tools. As you may know very well already, there’s no walled garden like iOS/iPadOS. Apps are contained, the Files one is some kind of explorer but remains still very limited, and firing a local command line is purely fantasy.

*How the heck do we write and run our beloved code Pierre? 💁*

As it’s common these days, the trick is in the cloud. While it comes with its drawbacks too, offloading the work to a remote, safe, always-accessible machine has some nice things going for it. A hosted machine can be fired in minutes these days. For some reasons I chose to run an old laptop plugged in a closet, but there are many options out there.

There’s essentially two solutions that content me for now: [Visual Studio Code](https://code.visualstudio.com/) in the browser, or a native SSH client app such as [Termius](https://apps.apple.com/us/app/termius-ssh-client/id549039908) or [Blink Shell](https://blink.sh/). The former is a cross-platform cloud SSH/Mosh service, and has really good iPad support. The only downside is the lack of a full external monitor integration as mentioned earlier. Blink Shell on the other hand boasts it and it works wonders. Picture that clean tmux/vim session on a 4K monitor.

![A mobile tmux web dev session in the native app Termius, with the side-kick browser](https://cdn-images-1.medium.com/max/4798/1*bUXkkL6ZasHeN01ds7ly9w.png)

For a proper IDE, there are ways to run the infamous undisputed leader of the last years—VS Code– in Safari. I personally fire it for refactoring and large Git diffs, I’m big on terminal-only work otherwise. [code-server](http://code-server.dev/) is a project that does exactly that, and at the time of writing comes with a Beta parameter --link [that does all the hard work of securing the connection](https://github.com/cdr/code-server#cloud-program-%EF%B8%8F). One line to install on various host, and one line to launch it and start the remote access.

For more details on the setup with more technical bits, check out [my Notion project page](https://www.notion.so/iPad-Challenge-ba216d5956194453a0dd4d56f62d888c).

![A code-server session, that “feels” native since it’s the same VS Code as on a regular computer](https://cdn-images-1.medium.com/max/4798/1*2cHzbviLVuuS0-uUOC69Fg.png)

## Software Dev (Bonus): Local Raspberry Pi {#local-pi}

The folks for whom a cloud connection isn’t an option can still hope: the most recent iteration of the sweet Raspberry Pi comes with a USB-C power and data port, and it’s therefore possible to both give it power and ethernet access from the iPad with one cable.

This enables a lot of possibilities, including local SSH, code-server’ing and access to the Desktop Environment. I have yet to test this but they are plenty of guides out there, notably [one from the very official MagPi](https://magpi.raspberrypi.org/articles/connect-raspberry-pi-4-to-ipad-pro-with-a-usb-c-cable).

A great way to make sure some coding work gets done when we get to travel again ✈️

# Hardware Dev: Remote Server and Remote Desktop {#harware}

Here comes the harder part: hardware (*easy)*.

To put in bluntly, there’s no SSHing into Computer Aided Design software. There’s no possibility of vim-editing a SolidWorks file. [OpenSCAD](https://www.openscad.org/) might be an exception to these statements but it’s most definitely niche.

Two options I have explored: (a) use some kind of Remote Desktop software to access our closet computer/server and run the software remotely; or (b) choose a web-based CAD software.

The first option applies to a broad range of software beyond just CAD. The real bottleneck here is the quality of the iPad app. I’ve gone through many of the free options *a la* TeamViewer or Chrome Remote Desktop, yet none provided mandatory things for my use case like full mouse buttons support (including click-and-drag with the wheel for instance). I’ve therefore moved to the premium territory and the one that met all my needs was [Jump Destkop](https://jumpdesktop.com/). With its outdated app icon and steep price tag, this was clearly not my first choice but their Fluid Remote Destkop protocol for Windows and macOS has just been the smoothest. It works wonders with my MX Master mouse, has full external monitor support on the iPad, and has automatic resolution matching, meaning I was getting 2K on my Ultrafine which offers a great workspace. On top of that, it supports VNC (even over SSH tunnels) to connect to Linux hosts such as a Raspberry Pi or other instances I use for work.

And it resisted the test of time: the whole design for my [GeeXY 3D printer project](https://www.notion.so/Geeetech-CoreXY-Conversion-GeeXY-b46d9f7b4b0643faa60bd2f20399c0b6) was made through Jump Desktop on the iPad.

![My GeeXY printer model, fully created through Jump on the iPad](https://cdn-images-1.medium.com/max/4798/1*XGCsXkdCjoIf6caxy8fHtQ.png)

The second option lies in the one and only cloud web-based CAD system: [Onshape](http://onshape.com). I’ve been bullish on their system through college, since they’ve nailed quite a lot of CAD aspects that are out of this article scope. While I do use it from time to time on Safari on the iPad, I’ve been loyal to the open-source [FreeCAD](https://freecadweb.org/) lately because I’m also using it at work (it even runs on Linux!).

![Despite a few small bugs on Safari, Onshape is a great CAD system, perfectly usable on the iPad](https://cdn-images-1.medium.com/max/4798/1*qa7FOs2Y_fapR4J7CcfCpg.png)

# Conclusion
A life of workarounds? Most definitely.

Indeed coming from macOS, the holy grail for tinkerers who care about a furnished software library, first-class terminal experience and compatibility whatsoever, the fully mobile iPad path is definitely not the safest journey for our specific needs as engineers or developers.

But the joy, I mean it, the joy, that this iPad Pro brings is what got me up for the challenge and kept me on the hook for side-projects as well as WFH. At the moment  there’s no going back, and it’s become clear that Intel chips are not missed at all, by me or many people with the new M1 Macs.

Side note: One curious thing I noticed in the iPadOS environment is a widespread old-school pay-once/use-forever business model, which offers quite a shelter from our subscription-based world. Shiftscreen was $3.99, Jump $19.99, and LumaFusion $29.99. It’s now paid for. Let’s enjoy the ride.