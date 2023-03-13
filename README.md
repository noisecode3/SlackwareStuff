# Slackware Studio Builds

Configuration scripts and builds for Slackware music productions
Slackware 15.1 on the road to an eventual beta

## Git SlackBuilds

* wine-tkg
* yabridge

### Kernels

* kernel-xanmod

## How

Run post_install_setup_sbo_slackpkg+_multilib.sh after installing full
Slackware 15,or Slackware current first thing you do after installation.
This will update Slackware and install sbopkg, slackpkg+ and multilib.
Overwrite all old config files when you get asked.
See config.info first then run this file to get a some essential configuration
for music production. Then create you're user and make sure you're in the audio
group and use Slackware like normal.

## 

* Tips
  * build a better kernel
  * look at pipewire-enable.sh and pipewire-disable.sh /usr/sbin/

* Slackbuilds pkg tips
  * [jack](https://slackbuilds.org/repository/15.0/audio/jack/)
  * [pipewire-native-jack](https://slackbuilds.org/repository/15.0/audio/pipewire-native-jack/)
  * [carla](https://slackbuilds.org/repository/15.0/audio/carla/)

* Alien pkg tips
  * [pipewire-jack](http://www.slackware.com/~alien/slackbuilds/pipewire-jack/)
  * [pulseaudio-jack](http://www.slackware.com/~alien/slackbuilds/pulseaudio-jack/pkg64/)
