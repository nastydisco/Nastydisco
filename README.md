
-

im on linux bazzite desktop. im new on github dont know what to post where or anything havent read into this alot yet.
updates to notes i find along the way of testing will be posted here if i know how.
or else i might just add a new line to this readme.md and add a date to it.
-
(i basicly use default settings. HANDHELD MODE ALWAYS)
to everybody with green and red lines graphical errors in Luigis mansion 3 on emu.
graphical erros in sonic crossworlds racing with crashes - sonic must run in accurate mode on my pc might be the same case for you. or i get graphical glitching causing crashes.
in luigis mansion 3 i only see them with my amd iGPU no lines even when on latest/nightly versions when im on my nvidia dGPU. (same settings different GPU)
-
eden nightly feb 07 2026
Nightly build of commit 71e035f83b.
Broke luigis mansion for my amd iGPU(660m ryzen 5 5735hs). creating the red and green lines people are complaining about
-
Eden Nightly - Feb 06 2026
Nightly build of commit b9e052b3a7
is the latest build i can find that has no graphical issues with lugis mansion 3
with the 60fps patch and dynamic resolution removed patch applied it runs smooth as shit just use HANDHELD mode do NOT use docked mode.
play around with your own settings.
patches made by Fl4sh9147. they are on github.
EDEN is on github.
-
A huge thanks to the creators of EDEN everoyone involved and a huge thanks to Fl4sh9147 for the patches you guys do amazing work.
-
so having a copy of b9e052b3a7 EDEN nightly feb 6 2026
(latest i could find without glitching in iGPU) for LM3(default settings handheld mode no v-sync BALANCED mode 60 fps patch disable dynamic resolution patch) and games like Sonic Racing Crossworlds(default settings handheld mode no v-sync accurate mode 60 fps patch) is what i do when i use my iGPU.
and it might fix the green and red lines for someone else too..

i use these settings for all versions of EDEN but different versions of eden for different things if you catch my drift.

-
on another note the versions after feb 6 2026 b9e053b3a7 seems to run alot of games more stable with some hiccups and slowdowns (E.g. slowdowns in sonic racing crossworld at start of races)
more optimized with some issues vice versa and very few crashes if settings set correctly(E.g. i always use handheld mode as it runs everything i have tried way better than docked.) (E.g. Accurate mode not fast not balanced. sonic racing) but some weird slowdowns in general in various games.

where as feb 6 and alot of the ones i tested before feb 6 version 2026 nightly. seems to have a WAY SMOOTHER gameplay what feels like no slowdowns at all (E.g. sonic racing again)
but UNFORTUNATELY hard crashes in (E.g. Sonic racing crossworlds.) VERY RARELY but it happens.
IS ABLE TO RUN LUIGIS MANSION 3 ON MY IGPU (amd660m ryzen 5 7535hs) no crashes happened yet at all. no red and green lines at all.

so there maybe some things to look into with what was done in the update from feb 06 to the version updated to at feb 07
,aybe something was changed that should be an option for people to turn on/off idk.. what it is but something broke something feb 06 - 07

thougt i would get the info out there love the work you all do.

- update

March 29 tested om igpu dgpu opengl and vulkan 
tested docked mode for sonic. (game on accurate only way it doesnt crash every 3 to 5 races. no fps change. still get the 45 sec to 1 min periods of 2 -5 fps at raondom points. then all falls back to 60 
tested docked mode for Luigi's Manssion 3 and iGPU ( actually less red and green lines lol? but docked mode represented a huge fps drop )

as of the latest nightly stable MARCH 29 2026
Commit of 276dcdd8ea. alot of the slowdowns in sonic racing has been fixed in eden emu. (thanks to EDEN and everyone involved)
i didnt get any slowmotion in the start of the race at the boost gauge. (not the 2 - 5fps thing im talking about)
but game still hawe like 30 45 sec periods of 2 - 5 fps while my mangohud shows almost no stress on gpu cpu
these periods of 2 - 5 fps happends on both vulkan and opengl both a amd igpu 660m and a nvidia 3050 6gb rtx. with both modes. ofcourse sonic on accurate. tried docked ran fine but again hard crash or the drop to 5 fps for almost a minute (amd64 machine)
MARCH 29 nightly commit of 276dcdd8ea red and green lines still present in luigi¨s mansion 3 the nightly that werent there for on feb 06 b9e05h3a7. 

- update 2. 3/31/2026
- tested eden 3/30/26 today

(update found something funny.) 
sometimes when i play sonic crossworlds on eden i someitmes get these spikes of gpu 0% 2 -5 fps game still runs
i found that pressing the boost button or r1 or whatever u kids call it made my game 100% speed again instant.
wierd as this has occured in every version of eden i tested sonic on but i just noticed the r1 fix for me. maybe it works for you if u have issues.
(could really just be random lucky r1 presses but its info out there) so don take it as a workaround/fix just try it out
luigi's mansion 3 feb 06 to 07 update break still not fixed as of the nightly today 30/03/26 but play the game with the nightly version from feb 06 2026 and maybe youre in the clear.
strange that 06 to 07 break. sad for amd igpu users. but we might get lucky some day and people have the time to look at it.
development/optimizing takes alot of time. and people do have jobs and families and lives in general love the emu/mod community u guys are the true unspoken heroes.
love to the guys at EDEN
love to Fl4sh9147 and everybody who helps.

-

the nightly version of 3/30/26 runs my sonic great with acurate mode. and handheld it did not crash the entire grand prix i played but thats only 4 races. and it did get the crazy stuttering and the "2 - 5 fps 0%gpu crazyness on mangohud" at the end of the second grand prix i played.
slowdown/spikes stopped when pressing r1 (i use a dualsense controller) lmao but i talk about the "drop to 2 - 5 fps slowdowns" its not a fix its just funny. makes me wonder why it happens.
(maybe its something with the controller) (i have all hotkeys off) in settings. except fullscreen on enter. on a keyboard.
i will try with a new computer i have laying around and a different controller or a keyboard tomorrow. on either this nightly 30/03/26 or the next release. when it releases.

one love to everyone who makes my gaming experience better with your hard work. especially in the emulation/modding community. 
that community does not get the praise it deserves.

nastydisco
-
nastydisco
