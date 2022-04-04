# Uniden
Favorite List for Sentinel

Hello!

I have been working on a pet project for some time now. As a scanner buff here in Wisconsin, I decided to build on my Favorites List so that encompasses all Police/Fire/EMS frequencies in this state and sort them out into a nicer format with some added benefits rather than using the default database. Here's what this Favorites List is all about. Also See FINAL NOTE at the bottom.

What’s Included:
1. All conventional frequencies for Police/Fire/EMS for all counties in Wisconsin.
2. Jail frequencies were added if they didn't require a dedicated trunked system.
3. Hospital patient report channels are also included.
4. Frequencies listed as encrypted as long as they didn't requrie a dedicated trunked system. (Decryption Not Included)
5. VERY LIMITED security, federal and military deemed frequencies.
6. All trunked systems used for public safety services in Wisconsin (SEE "WISCOM" BELOW)
7. Systems are determined and sorted by county. Counties with multiple systems are named identically by its county's name.
8. Statewide systems that have conventional and on-scene/fireground frequencies.
9. Department and Channel information follow a shorthand naming structure that I hope is intuitive. (SEE "NAMING " BELOW)
10. All channels are individually assigned to an alert light (SEE "ALERT LIGHT" BELOW)
11. GPS data has been updated and set for all departments in MOST counties (SEE "GPS" BELOW)
12. Counties and cities are categorized into quick keys for access (SEE "QUICK KEYS" BELOW)

What’s NOT Included:
1. School, Aircraft, DPW, Ham, Skywarn, Railroad, Transportation, Businesses.
2. Anything outside the state of Wisconsin
3. Most Federal and Military
4. Channels designated for backup use only.
5. Channels that are constant simulcasts of other systems (e.g. State Patrol on county talkgroups)



**---NAMING---**

I took a bit of creative liberty to fit the naming system into somthing that could be categorized and yet stay simplistic.
1. Systems are named for the county that they are in. This means conventional and trunked frequencies for the same county share a duplicated name
2. Departments are separated by city or geographical area by name. Creative liberties had to be taken in some naming conventions.
3. The default channel name is "Talkaround" when no other identifying information is given other than Police or Fire Talk (SEE ALERT LIGHT)
4. Talkgroups that are patches to conventional interop frequencies or patches that are not constant simulcasts are designated with #



**---ALERT LIGHT---**

The Alert Light is used to determine if the radio traffic channel is Police, Fire/EMS, Interop, Emergency Management, or a combination shared channel. In addition, the Service Type tag is also accurate for each channel.

1. BLUE - All police channels have a blue alert light
2. CYAN - Correctional facilities.
3. RED - All fire and EMS channels have a red alert light
4. MAGENTA - If police and fire have a shared a channel (e.g. Citywide), they will have a Magenta alert light (Red+Blue)
5. GREEN - In rare instances where police and the DPW share a single channel for their department. Mainly seen in rural areas.
6. YELLOW - In rare instances where fire/EMS and the DPW share a single channel for thier department. Mainly seen in rural areas.


1. SOLID ON - This channel is primarily used by the department that it is listed under.
2. SLOW BLINK - This an interopability channel or patch used for interoperability. (e.g. IFERN)
3. FAST BLINK - This is used for Emergency Management channels, used primarily for large scale events


**---ALERT TONE---**

Alert tones were not used in categorizing the favorites list. 


**---GPS---**

THIS IS A WORK IN PROGRESS. I still have 20 counties to do!

This is a complete GPS overhaul which is heavily based on coordinate locations grabbed from Google Maps. In my opinion, I really don't like the GPS data that in on the Radioreference database. It's all circles. It's too broad, inconsistent, and not very accurate. I am going through every county and creating hard edges with rectangles between counties and creating uniform distances between cities, and putting edges on cities that could use it. 

1. Each County uses Rectangle positioning with decimal coordinates to the rounded thousanth (E.G. 43.435 -91.064)
2. Cities within metropolitan areas are carved out with rectangles to match actual boundaries much closer.
3. Rural towns still use circles that more closely matches the geographical center of town and a distance from farthest opposing ends of town, minimum 2 mile radius.
4. Counties that HAVE NOT undergone the GPS Overhaul will NOT have "County" in thier Sysytem Name. 
5. Counties that HAVE NOT undergone the GPS Overhaul wil have default values from the Radioreference Database.


**---QUICK KEYS---**

As Wisconsin is Alphabetically the 49th state, I have set the Favorites List quick key to 49.

Each system quick key is assigned a county. Reserving keys 0-9 as statewide, I started with my home city of Milwaukee at QK #10 and moved onto each county. Counties are, for the most part, geographically sectioned into groups of 10 with the attempt to center them around major metropolitan areas when I could.

See QuickKey.pdf for a map of quick keys assigned. Federal is QK #00. WISCOM and Statewide Frequencies are QK #01.


**---WISCOM---**

THIS IS A WORK IN PROGRESS. Any systems in WISCOM that are being avoided have not been gone through the renaming and assignment process. This means that daily users of WISCOM may not be available in this list yet. I am still working for it, but I haven't gotten the motivation to do this right now. Especially the GPS Portion.


**FINAL NOTES**

Location Control should be OFF and only Statewide frequencies (49.01) is active. You will need to activate each county you would like to listen to by entering the corresponding quick key (49.10 for Milwaukee County, 49.52). **

**Federal is set to Avoid on Default. I have not even gone through naming them all, and all GPS data (if any) will be defaults.**

**Anything that is set to Avoid in WISCOM have to been renamed and filtered yet.**

**This Favorites List was last updated on 4-4-2022. It is the effort of one guy, and it is not the perfect solution. You can modify the list as you wish if you feel there is a better way that suits you.**

**I do plan to finish this Favorites List, as it is 95% done. If support is strong, I will keep this list updated as the Radioreference database updates. If you are interested in contributing, you can DM me on the RR Forums or through github.**

