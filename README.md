# RLC Titanium

RLC Titanium is based on [RLC Platinum 2.0 Gamma, version 2.0.68](https://github.com/MagnumMacKivler/RLCPT2).  
It is an Expression2 script that simulates real-life diesel-electric locomotives in Garry's Mod.

> [!NOTE]  
> In its current state, RLC Titanium is nearly identical to RLC Platinum Gamma, but with some superficial changes to the naming, branding, and folder structure.
> Over time, RLC Titanium will be updated with new features, bug fixes, and improvements to make it easier to set up and use.
> This project is not a high priority for me, so development on it is significantly slower compared to my [more popular project](https://github.com/ZZ-Cat/CRSFforArduino), as this is more-or-less something I do in my spare time.

RLC Titanium is focused on quality-of-life improvements, bug fixes, and user-friendliness.

I am aiming to bring in enhancements such as automatic over-the-air updates, a Configurator GUI where you can configure/tune/tailor RLC Titanium to your needs  
through a graphical user interface, and making RLC Titanium as easy as spawn-the-E2-and-go to set your first locomotive up and get it running right out-of-the-box.

## Dependencies

RLC Titanium has the following dependencies:

- [Grovestreetgman's train sounds](https://steamcommunity.com/sharedfiles/filedetails/?id=240020348)
- [Wiremod](https://steamcommunity.com/sharedfiles/filedetails/?id=160250458)

## Installation

The installation process of RLC Titanium is significantly different, and will become more user-friendly as time marches on.  
For now...

```shell
git clone https://github.com/ZZ-Cat/rlctitanium
```

into your Garry's Mod directory...

```shell
steamapps/GarrysMod/garrysmod/data/expression2/e2shared
```

When all is said and done, you should see the `rlctitanium` folder in your `e2shared` folder.

## Development map

- [ ] Remove all the bloatware, stripping everything back to the bare locomotive controller itself, plus the minimum required for your locomotive to function.  
  This means all irrelevant scripts (EG the contents of magspack2) will be removed. If you still wish to use these scripts, you may use the ones that come with RLC Platinum 2.0 Gamma. I will endeavour to have RLC Titanium interoperable with a lot of these scripts as I can.
- [ ] Overhaul existing CLI.
- [ ] OTA Updates (where you can opt-into automatic updates instead of opt-out).  
  This is a big one, and it's one I had planned for RailDriver, but I never implemented it.
  What this does is it allows you to download new updates to RLC Titanium and the install happens automatically.  
  It is entirely transparent to you. You don't need to lift a finger... except typing in a command to initiate the update. But, you get the idea. =^/.~=
- [ ] Simplify the set-up process.  
  By the time I am done with this, all you will need to do is place the E2 chip in an inconspicuous spot on your locomotive, start it up, hop in your driver's seat and go.
- [ ] ?
- [ ] Rolling release...

## Attributions

### Upstream

- RLC Platinum 2.0 Gamma
  - Developers:
    - [Magnum MacKivler](https://github.com/MagnumMacKivler)
    - [Grovestreetgman](https://github.com/Grovestreetgman)
  - [Source Code](https://github.com/MagnumMacKivler/RLCPT2)
