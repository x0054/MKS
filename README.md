# MKS: Mechanical Keyboard Simulator

Do you love the sweet sound of a mechanical keyboard with those Cherry MX Blue
keys? Are your coworkers and family members sharpening their pitchforks and are
getting ready to murder you just to stop the incessant clicking? Well, you are
in luck! I have a program that will make them happy, keep you alive for a bit
longer, AND will allow you to continue listening to that wonderful clicking
sound you love so much. It’s called the Mechanical Keyboard Simulator, or MKS
for short.

I wrote this shortly after getting a mechanical keyboard. The process of
keyboard acquisition was one of both joy and sorrow. The joy of gloriously
typing on that beautiful mechanical marvel, and the sorrow of having to listen
to my wife type on that beautiful mechanical marvel.

Quickly I realized that the part that I like the best about the mechanical
keyboard is actually the sound. There are some logical reasons behind it, it’s
not just for the aesthetics. The sound is a form of feedback. On modern laptop
keyboards there is so little feedback that every bit counts. The sound is like a
reassurance. It’s your computer telling you, yes, you did indeed hit that key.

Thereafter it quickly occurred to me that it would be easy to simulate the
sound, rather than having to actually mechanically reproduce it. I Googled a few
apps, but all of them came short, so I decided to write my own. Here are some
special features of my system-wide Mechanical Keyboard Simulator:

1. Adjustable Volume as a percentage of the system volume setting.
1. Separate keydown and keyup sounds to increase realism.
1. Multiple Sound Profiles.
1. Support for Modifier Keys.
1. Stereo and Mono Sound Profile.
1. Separate sound profiles for various keys.
1. Randomized pitch.

Give it a try, see what you think. I think you are going to love it, and since
it works with headphones too, your family friends and coworkers are going to
love it too. :)

## Installation

### Brew

1. Install [brew](https://brew.sh/).
1. Run:

        $ brew cask install mks

1. Grant Accessibility permissions (see below).

### Manual

1. Download the [MKS.dmg](https://github.com/x0054/MKS/releases/latest) from the
   releases tab above.
1. Open the MKS.dmg and drag MKS app to the Application folder on your dock.
1. Grant Accessibility permissions (see below).

### Grant Accessibility permissions

1. To work the app needs Accessibilities permissions. To give the app
   permissions:

   1. Open `System Preferences > Security & Privacy > Privacy >
   Accessibility`.
   1. Click on the Padlock in the bottom left hand corner.
   1. Drag the MKS app into the list. That’s all.

1. Now start MKS. It will add an icon to the System Bar. Play with the options
   and Enjoy!

## License

I am releasing this app under the MIT license.
