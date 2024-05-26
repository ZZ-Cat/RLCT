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

- [x] Change the folder structure of the repository.
- [x] Re-brand the entire repository as RLC Titanium.
- [x] Update the Operator's Manual to reflect the branding of RLC Titanium, making it distinct from its upstream.
- [x] Bloatware, Part 1: Deprecate `magspack2`.
  The contents of this subfolder is outside the scope of RLC Titanium, and will be removed before the first release is made.  
  If you wish to continue using these scripts, you should use the ones from the upstream instead.
- [ ] Bloatware, Part 2: Remove outdated/discontinued/abandoned scripts in `rlctitanium/src/extras` subfolder.
- [ ] Consolidate the `rlctitanium/src/cstands_*` subfolders.
- [ ] Submodule the `rlctitanium/src/cstands_*` subfolders.
- [ ] Submodule the `rlctitanium/src/engines` subfolder.
- [ ] Re-factor: Improve dupe handling when spawned with Advanced Duplicator 2.
- [ ] Re-factor: Simplify the set-up process.
  - [ ] Remove all physical Wire I/O.
  - [ ] Replace pod controller dependency with internal handling.
  - [ ] Replace advanced entity marker dependency with internal entity discovery.
- [ ] Re-factor: Improve on-chip security - particularly in online multi-player sessions.
- [ ] OTA Updates (where you can opt-into automatic updates instead of opt-out).  
  This is a big one, and it's one I had planned for RailDriver, but I never implemented it.
  What this does is it allows you to download new updates to RLC Titanium and the install happens automatically.  
  It is entirely transparent to you. You don't need to lift a finger... except typing in a command to initiate the update. But, you get the idea. =^/.~=
- [ ] Repository restructure... again.  
  Yes, again. If I do this right, you should _only_ be able to clone the repository into your Expression2 directory, and let the OTA Updates handle the rest.
- [ ] Overhaul existing CLI.
- [ ] Re-factor: Fix all the compiler warnings.
- [ ] Style: Improve code readability.
- [ ] Enhancement: RLC Titanium Configurator.
  This may be submoduled into its own repository, but it will add a graphical user interface to allow you to easily configure RLC Titanium to your needs.  
  No more reading source code _just_ to set your train up.
- [ ] ?
- [ ] Cut v0.1.0 and release it.

## Attributions

### Upstream

- RLC Platinum 2.0 Gamma
  - Developers:
    - [Magnum MacKivler](https://github.com/MagnumMacKivler)
    - [Grovestreetgman](https://github.com/Grovestreetgman)
  - [Source Code](https://github.com/MagnumMacKivler/RLCPT2)
