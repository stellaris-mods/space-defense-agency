# Space Defense Agency

# Ideas from players

Changes for next push:
* Fix event locked fleets on planet transfer

Is there a way to choose SDA station doctrine using policy options?
I mean, Hard coded stations, chosen based on the policy you pick.
Not that I think you should actually do that, but it's food for thought.

Another random thought. To counter station upkeep costs and the inability
to reduce them past 1/5 of original upkeep, can you find some way to make
the stations provide an income that covers the difference? Maybe a policy
can do it? Call it SDA Rebate Program! Flavor it as beaureucrat(or however
you spell that) nonsense. Even if it isn't perfect, a flat income based
on # of stations would be an improvement.

Crazy idea from my side. How about SDA ground troops that will be generated
on planets having an SDA building? I think this could make sense since the
sector AI hardly builds armies and it would add a bit of x-com style to the
game. Of course these troops should have defensive character only.

sda station per office

roaming defense fleets

> clear_orders - Clears all fleet orders from the scoped fleet
> clear_order = yes
> Supported Scopes: fleet
> Supported targets: THIS ROOT PREV PREVPREV PREVPREVPREV PREVPREVPREVPREV FROM FROMFROM OWNER CONTROLLER CAPITAL LEADER SOLAR_SYSTEM RANDOM

> order_forced_return - Forces scoped fleet to retreat to friendly territory
> order_forced_return = yes
> Supported Scopes: fleet
> Supported targets: THIS ROOT PREV PREVPREV PREVPREVPREV PREVPREVPREVPREV FROM FROMFROM OWNER CONTROLLER CAPITAL LEADER SOLAR_SYSTEM RANDOM

" mr.TPATATA: Hey folk, i got accidentally translate space defence agency at russian language,
its included in my all-in-one alphamod translation package o_O, but if you not gonna update mod
frequently, you can include localisation in it.
"

# Steam description

[//]: # (start)
Steam description transliterated from `steam.bbcode` by [our release script](https://raw.githubusercontent.com/stellaris-mods/scripts/master/stlrel).

## **Allow the Space Defense Agency to operate on your space port for improved local subspace defense\.**
The AI will use all the features of the addon\.

It all started when,

1. I got annoyed at all these random space monsters jumping into my systems, triggering warning popups, and then just moving on
1. I noticed the AI was extremely picky about constructing military stations, in fact I played a game up to the ED crisis and no AI empires had any stations at all



I thought, "why can't the spaceport have the subspace snare capability?"\. I had to make it\!

The mod is far from complete, or balanced, but the AI does use all features\.

## Spaceport Module: Military Hangar
_Required Spaceport Level: 5_
Allows the Space Defense Agency to station fighters and bombers at this Spaceport\. These spacecraft are much more powerful than the ones that come with the spaceship\-mounted hangars\.

They will immediately take foot in your Spaceport with 2 squadrons, one consisting of 12 fighter\-style craft, and one squadron of 4 bomber\-style crafts\.

They engage any hostiles autonomously at a range slightly higher than that of the stations main weapons\.

## Spaceport Module: Space Defense Agency
_Required Spaceport Level: 5_
_Required Technology: Defense Platform_
Installs an office module on the Spaceport that allows their bureaucrats to work in relative safety\. They will install a shield module and attempt to operate a small military station just outside the planets gravitational field\.
The military station will be operated by the SDA, and thus has a substantially reduced (\-80%) upkeep cost\. However, you will not have any control over when it is built or upgraded\.

If you have enough SDA Office buildings in your empire, the SDA will upgrade the station from Platform, to Station, to Fortress, (and Battle Fortress with NSC and a Governors Mansion) over time automatically\. If the station is destroyed, it will start out as a Platform again\.

## Building: Space Defense Agency HQ
_Requires Planetary Administration_
_Empire\-unique_
Sets up the main offices of the Space Defense Agency\. This allows them to operate an empire\-wide wormhole network for automated subspace defense\. Any time a hostile military fleet enters owned space, an automated defense fleet will be dispatched immediately\.
The fleet consists of drone\-craft exclusively\. It buys you time to react\.

A maximum of 3 hostile fleets will be intercepted at a time\.
Only one SDA automated drone fleet can be deployed in a star system at a time\. Star systems will not be deployed to until 3 months have passed\.

The drone squadron deployment fields structural reinforcement will be automatically adjusted by the SDA HQ staff to be able to sustain a few days worth of bombardment by virtually any hostile fleet composition\.

The combined hull points of all deployment portals will be the same regardless of how many of them spawn\. It scales the hull reinforcement and divides it per portal\. So the only benefit to having more than one portal is the added damage from the additional squadrons\.

## Building: Space Defense Agency Office
_Requires Planetary Administration_
_Planet\-unique_
Sets up a military facility for local SDA operations\. This factility has a number of small bonuses for army recruitment and planetary fortification\.
Most importantly, **you need 2\-4** of these buildings for the SDA spaceport operations to construct the relevant levels of military stations\!

Having 2 will allow them to upgrade from Platforms to Stations, having 3 will allow Fortresses, and 4 of them will allow the Battle Fortress, if you have NSC\.'
The Battle Fortress upgrade also requires 1 planet with a Governors Mansion (NSC building)\.

Each SDA office building (no matter how many you have) increases the number of automated drone squads deployed by the HQ by 1 per deployment\. These additional squadrons are very weak compared to the one deployed by the HQ\.

## Spaceport Module: Subspace Inhibitor
_Required Spaceport Level: 1_
The classic, well\-known subspace snare aura, fitted on your Spaceport\.

## Spaceport Module: Subspace Field Modulator (Allied)
A combination of the military station\-mounted shield regeneration aura and nanobot cloud, this powerful subspace field will heal up your fleets in no time\.
Note that this aura generates zero graphical indicators, like the ship/stations ones do\. It's simply annoying with that circle\.

## Spaceport Module: Subspace Field Modulator (Hostiles)
A combination of the military station\-mounted quantum destabilizer and the shield dampener\.
Note that this aura generates zero graphical indicators, like the ship/stations ones do\. It's simply annoying with that circle\.

## Feedback
I don't know how to balance this, or what to do with it\. But from what I can tell, this feature is quite unique on the workshop\.
Please feel free to give me suggestions, ideas, or any kind of feedback\. I see this as a good proof\-of\-concept and place to start, but it certainly feels lacking\. Especially the SDA module, it seems like, for example; it should cost some influence, it might impact happiness/ethic diversion on the planet in some manner, it might need some random events\. Perhaps you should only be able to have 1x of them\.

Anything can be done, please let me know what you think :\-)

The logo is ripped from the US DoD's Missile Defense Agency\.
And yes, I know "defense" is a controversial spelling of the word, hehe\.

## Please check out my other addons\!
[![](http://i\.imgur\.com/XLkY9rP\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=786514324) [![](http://i\.imgur\.com/HB3mzUd\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=790840932)
[![](http://i\.imgur\.com/QbwKam7\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=787280885) [![](http://i\.imgur\.com/Qowgmu2\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=785719197)
[![](http://i\.imgur\.com/557d0qz\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=776095610) [![](http://i\.imgur\.com/c85HK9A\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=785582857)
[![](http://i\.imgur\.com/hGJdX51\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=779729987) [![](http://i\.imgur\.com/HmbP3Gd\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=796214744)
[![](http://i\.imgur\.com/IVM6B6g\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=799159083)
[And many others :\-)](http://steamcommunity\.com/workshop/filedetails/?id=779739023)


[//]: # (stop)
