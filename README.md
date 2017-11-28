# asdf-firefox

[Firefox](https://www.mozilla.org/pl/firefox/) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

Currently at a very early development stage, only Linux is supported.

## Why?

Because why not and I was just bored one day?

No, seriously, there have been numerous times when I wished I could manage my web browser versions just as I do with my rubies, elixirs and all others using `asdf`.

I thought it would be useful when I try to track down regressions caused by changed browser behaviors or do any other stuff that involves manual testing, hence the emergence of this experiment.

## Install

```
asdf plugin-add firefox https://github.com/vincentvanbush/asdf-firefox.git
```
### Requirements

At this stage, only Linux is supported. Apart from that, you're good to go as soon as you've installed the `asdf` version manager.

## Future

Some thoughts for the foreseeable future:

* Prepare the plugin for other platforms (especially mac)
* Create more flexible profile management (for the time being, each installed version has its individual profile. This is to combat situations such as when I installed a very old version which used my 57.0 profile, and then when I went back to Firefox 57, the cookies were GONE). Perhaps a good idea would be to provide some easy means to migrate profiles or mark an installation as one that uses a "global" (`~/.mozilla`) profile.
* Create a Chromium plugin.
* Go to sleep, it's 1 AM.
