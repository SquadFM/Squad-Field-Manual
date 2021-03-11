# SQUAD FIELD MANUAL
## Tactics, Techniques and Procedures
### This field manual contains detailed information and how-tos for procedures important to soldiers serving in the field.

- If you're a new player WELCOME TO SQUAD! We're glad that you're here!
- If you're a vet THANK YOU FOR YOUR SERVICE and making this a great game.
- When I first started to play Squad I was feeling overwhelmed. This game has a steep learning curve and I had no clue what to do during my first few games. The in-game training only teaches you so much. Therefore I started this document to write down my own learnings and those from other players.
- I never planned to share this guide, however as it grew in size I realized that others might benefit from it as well.
- This guide contains the collected wisdom of many experienced Squad players from various sources. Their contributions are often copy-pasted into this guide. If you find content in this guide that you wrote I want to say "Thank you" for sharing your wisdom on the Squad Wiki, Reddit, in various manuals and strategy guides, the old Squad forum (offline now), Steam, YouTube and other sources. I've listed most sources below.
- If you want to say "hi" my Squad in-game name is Munster. Feel free to add me on Steam https://steamcommunity.com/id/Munster101/
- This guide is still work in progress, but I am trying to be less of a perfectionist and just wanted to get it out there.
- Why is this guide on Github? I am not a fan of PDFs (pain to read on mobile) and rather have all information in a single text file. It's easier to search and you can copy-paste what you need. You can download this repo to your computer. Maybe people like to contribute and add information to this guide and GitHub is a great place to collaborate.
- This guide was last updated March 11, 2021.


# NEW PLAYERS PLEASE READ
Before you join a server as a new player
- Please check out at least the chapters [Before Joining A Game](#before-joining-a-game) and [Rifleman](#rifleman),
- Practice on Jensen's Range and the linked Steam Workshop maps,
- Take a look at various new player guides on YouTube (links below in the "YouTube Channels" chapter).
- This game has its own language. Take a look at the [Abbreviations/Lingo](#abbreviations-lingo) chapter if you don't know a term.


************************************************************************
# Content

- [Installation, Setup](#installation-setup)
  - [Installation](#installation)
  - [Settings](#settings)
  - [Backup Your Settings](#backup-your-settings)
  - [Protect Your Hearing](#protect-your-hearing)
  - [Show FPS, Find Hardware Bottlenecks](#show-fps-find-hardware-bottlenecks)
  - [OBS Setup](#obs-setup)
- [Game Mechanics](#game-mechanics)
  - [What's this game about?](#whats-this-game-about)
  - [Tickets](#tickets)
  - [Control Points](#control-points)
  - [Flags](#flags)
  - [Capping Mechanics](#capping-mechanics)
  - [Ticket Bleed](#ticket-bleed)
  - [Double Neutral](#double-neutral)
- [Game Modes](#game-modes)
  - [(Random) Advance and Secure](#random-advance-and-secure)
  - [Invasion](#invasion)
  - [Skirmish](#skirmish)
  - [Territory Control (TC)](#territory-control-tc)
- [Before Joining A Game](#before-joining-a-game)
  - [Training](#training)
  - [Steam Workshop Maps](#steam-workshop-maps)
  - [Good Roles And Jobs For New Players](#good-roles-and-jobs-for-new-players)
  - [Finding a Server](#finding-a-server)
  - [Server Rules](#server-rules)
  - [Joining a Squad](#joining-a-squad)
  - [Communication](#communication)
  - [I Am Too Shy To Speak](#i-am-too-shy-to-speak)
  - [I Cannot Speak (I Am A Mute)](#i-cannot-speak-i-am-a-mute)
  - [Callouts](#callouts)
  - [Lyrics](#lyrics)
  - [Radio](#radio)
  - [Building Deployables](#building-deployables)
  - [Running Around](#running-around)
  - [Map](#map)
  - [Identifying The Enemy](#identifying-the-enemy)
  - [Firefights](#firefights)
  - [I'm Dead, Now What?](#im-dead-now-what)
  - [Tactical Respawning](#tactical-respawning)
  - [Being a Fireteam Lead](#being-a-fireteam-lead)
  - [What If I'm Given SL?](#what-if-im-given-sl)
  - [Best Practices](#best-practices)
  - [Do Never](#do-never)
  - [How To Make Friends in Squad](#how-to-make-friends-in-squad)
- [Infantry](#infantry)
  - [Rifleman](#rifleman)
  - [Medic](#medic)
  - [Automatic Rifleman](#automatic-rifleman)
  - [Grenadier](#grenadier)
  - [HAT and LAT](#hat-and-lat)
    - [HAT](#hat)
    - [LAT](#lat)
    - [Engaging The Enemy With AT](#engaging-the-enemy-with-at)
  - [Marksman](#marksman)
  - [Combat Engineer and Sapper](#combat-engineer-and-sapper)
    - [Mines](#mines)
    - [C4](#c4)
    - [IED](#ied)
  - [Raider](#raider)
  - [Crewman](#crewman)
  - [Pilot](#pilot)
  - [Mortar](#mortar)
- [Vehicles](#vehicles)
  - [Vehicle Types](#vehicle-types)
  - [Vehicle Basics](#vehicle-basics)
  - [Training](#training)
  - [Moving Around](#moving-around)
  - [Engaging The Enemy](#engaging-the-enemy)
  - [Damage and Repair System](#damage-and-repair-system)
- [Helicopter](#helicopter)
- [Squad Leading](#squad-leading)
  - [What is a Squad Leader?](#what-is-a-squad-leader)
  - [Squad Leader Meta](#squad-leader-meta)
  - [Creating a Squad](#creating-a-squad)
  - [Leading a Squad](#leading-a-squad)
  - [Leadership Tips](#leadership-tips)
  - [Where Should You Go?](#where-should-you-go)
  - [SL Best Practices](#sl-best-practices)
  - [Fireteams](#fireteams)
  - [Building FOBs and HABs (Spawn Points)](#building-fobs-and-habs-spawn-points)
  - [Team Communication](#team-communication)
  - [Communicating With Other SLs/Commander](#Communicating-with-other-slscommander)
  - [Squad Tactics](#squad-tactics)
    - [Offensive Squad Tactics](#offensive-squad-tactics)
    - [Defensive Squad Tactics](#defensive-squad-tactics)
  - [Guerilla/Recon Squad](#guerillarecon-squad)
  - [Strategy To Win Games](#strategy-to-win-games)
  - [How To Use Helicopters](#how-to-use-helicopters)
  - [Staying Sane](#staying-sane)
- [Commander](#commander)
- [Abbreviations, Lingo](#abbreviations-lingo)
- [NATO Phonetic Alphabet](#nato-phonetic-alphabet)
- [Console Commands](#console-commands)
  - [Admin Commands](#admin-commands)
  - [Public Commands](#public-commands)
- [Admin Camera](#admin-camera)
- [Sources and Resources](#sources-and-resources)
  - [Websites](#websites)
  - [YouTube Channels](#youtube-channels)

[Back to top](#squad-field-manual)


************************************************************************
# Installation, Setup

## Installation
- If you're using Windows you can skip this chapter. You can simply install the game in Steam and you're good to go.
- Since I play exclusively under Linux I wanted to share the setup process to make the life of other Linux users easier.
- Squad runs natively on Windows, but it also runs great on Linux (through Steam and Proton).
- I am using Manjaro, but the process should be the same on all distros.

- Go to Steam and download Squad.
- Download Easy Anti Cheat from Valve's Github repo (this is Valve's official repo and you won't get banned playing under Linux): https://github.com/ValveSoftware/Proton/files/4839724/easyanticheat_wine_x64.tar.gz
- Extract the files to: /home/username/.local/share/Steam/steamapps/compatdata/393380/pfx/drive_c/users/steamuser/Application Data/EasyAntiCheat/55/
- Set the /55/ directory to read only
- Also, set the following /Temp/ directory to read only: /home/username/.local/share/Steam/steamapps/compatdata/393380/pfx/drive_c/users/steamuser/Temp/
- In Steam go to Library > right click on Squad > Properties > in the settings pop-up go to Compatibility and check "Force the use of a specific Steam Play compatibility tool". Select the latest Proton version.
- While you're here, set Automatic Updates to "High Priority" and set background downloads to "Pause".

[Back to top](#squad-field-manual)


## Settings
- I am playing with the settings below. Adjust them to your own liking.
- You can also find my keyboard and mouse binds in the Github repo.
- Game:
  - Field of View: 90 (a higher field of view will decrease the size of your rifle optic)
  - Mouse Smoothing: off
  - Mouse Global Sensitivity: 0.30 (my mouse is set to 700dpi, lower mouse sensitivity will help with aiming)
  - Mouse Freelook Sensitivity: 4 (set this as high as possible, you want to be able to quickly look around)
  - Helicopter Sensitivity Pitch/Roll: 3
  - Use Zoom Sensitivity Scaling: Yes
    - No Zoom: 1
    - 1x Zoom: 1
    - 4x Zoom: 0.5
  - Vehicle Sensitivity: No Zoom 0.5, 4x Zoom 0.5
  - Hold to aim down sights: No
  - Hold to crouch: No
  - Hold to lean: Yes
  - Hold to freelook: Yes
  - Freelook Recenters Weapon: Yes
  - Jump causes uncrouch: No
  - Jump causes unprone: No
  - Double Tap to auto walk: No
- Graphics:
  - Window mode: Fullscreen
  - Resolution: 2560x1440 (set your screen's native resolution, if your PC can handle it)
  - Resolution Scale: 100
  - Max FPS Menu: 60
  - Max FPS In-Game: 144 (set your screens native refresh rate)
  - AA Quality: Low
  - AA Samples: 4
  - Shadow Quality: Low
  - Contact Shadows: No
  - Far Shadows: No (reduces FPS like crazy)
  - Texture Quality: Low
  - Anisotropic Filtering: 2
  - Uncap Texture Poolsize: No
  - Particle Quality: Cinematic
  - AO Quality: Off (better visibility)
  - Screen Space AO: No (better visibility)
  - Post Processing Quality: Low
  - Lens Flares: No
  - Motion Blur: No
  - Screen Sharpening: 0
- Audio:
  - Audio Quality: Epic (Epic = better locate enemies)
  - Audio Output Device: PulseEffects(apps) (set your output device, in my case I am using the output from the PulseEffects Audio Compressor)
  - Master Volume: 100%
  - Effects Volume: 80%
  - UI Volume: 0%
  - Music Volume: 0%
  - Out of Game Volume: 50%
  - Command Voice Volume: 200% (Hearing voice communication is very important in this game)
  - Command Voice Balance: -100 (left ear only)
  - Squad Voice Volume: 200%
  - Squad Voice Volume: 100% (right ear only)
  - Local Voice Volume: 200%
  - Priority Speaker Ducking: 50%
  - Radio Filter: On
  - Command Beeps: On
  - Squad Beeps: On
  - Only apply when leading: Off
- Interface:
  - In Game Help: On
  - Show Stance Indicator: On
  - Show vehicle keybinds: On
  - Skip give up confirmation: off
  - Radial menu tips: On
  - Menu tooltips: On
  - Show mode intro animation: Off
  - Play capture sounds: Off
  - Disable on screen chat: Off
  - Name tag opacity: 1
  - Name tag scale: 1
  - SL marker always visible: On
  - Show Name Tag Text: On (shows name tag over friendlies _most_ of the time; still check your map before firing)
  - Show Name Tag Kit: On
  - Show Name Tag Fireteams: On
  - Map Marker Scale 0.9
  - Show Map Marker Fireteams: On
  - Show Weapons in deployment: On
- Controls
  - Map - You will need the map A LOT. If you have a mouse with a thumb button this would be a good place to access the map. Or use TAB or any other key you can access without moving away from WASD too much.
  - Lean keys: use Q to lean right, E to lean left - makes it easier to strafe at the same time.
  - For my other controls please see my keyboard and mouse binds doc in my Github repo.

[Back to top](#squad-field-manual)


## Backup Your Settings
- Backup your game settings (updates can reset your settings)
- Under Linux go to: /home/username/.local/share/Steam/steamapps/compatdata/393380/pfx/drive_c/users/steamuser/Local Settings/Application Data/SquadGame/Saved/Config/WindowsNoEditor/
- Under Windows go to either directory:
  - C:\Users[username]\AppData\Local\Squad\Saved\Config\WindowsNoEditor
  - %LOCALAPPDATA%\Squad\Saved\Config\WindowsNoEditor
- Backup the following files:
  - GameUserSettings.ini
  - Input.ini
- Some updates may change menu settings, graphic options, etc. and sometimes it is best to start with a clean slate. Press "Empty Cache" in the Game Settings to reset everything to defaults. This will delete all of your keybinds, settings, etc.

[Back to top](#squad-field-manual)


## Protect Your Hearing
- Shots and explosions can be very loud in Squad and damage your hearing.
- You can use an Audio Compressor that will automatically reduce volume spikes (e.g. shots, explosions).
- You will still be able to hear footsteps and other quiet noises. In fact you will be able to focus better on quiet noises.
- The compressor will not just improve sound, it will prevent damage to your ears. You do not want Tinnitus, it's terrible.
- Linux Audio Compressor: PulseEffects, PulseEffects-Legacy
  - Attack: 0ms
  - Release: 100ms
  - Threshold: -45db (if you reduce this towards 0db (e.g. -35db) loud noises will be louder)
  - Ratio: 20
  - Knee: 0db
  - Makeup: 0db
- Windows Audio Compressor: VoiceMeeter Banana (search for audio compressor windows)

[Back to top](#squad-field-manual)


## Show FPS, Find Hardware Bottlenecks
In the console type:
- stat FPS - to see frames per second
- stat Unit - to see if either the CPU or GPU are holding back performance
  - Frame is the overall frame time, in milliseconds.
  - Game is CPU time.
  - GPU is GPU time.
  - Whichever of the latter two matches Frame is what's holding performance back.

[Back to top](#squad-field-manual)


## OBS Setup
- If you don't want to record your games you can skip this chapter.
- OBS (Open Broadcaster Software) is free software to record your gameplay. You can also use it to stream your games on various platforms.
- It's not needed to play Squad but I find it helpful to record games to review my performance.
- Share your Squad games and funny moments with the world on YouTube. We'd love to see them!
- You can download OBS here (Windows/Linux): https://obsproject.com/

[Back to top](#squad-field-manual)


************************************************************************
# Game Mechanics

## What's this game about?
- Squad is a team game of communication, coordination and movement.
- The goal of most of the gamemodes is to capture territory, not kill the enemy. Killing enemies is a secondary objective, often required to achieve the primary objective. Don't lose sight of the primary objective because you want to get a kill.
- The vast majority of this game is actually about NOT engaging the enemy, and then engaging them quickly and completely destroying them before they can respond. By not engaging the enemy, you and your team can move around them and secretly get into a position to destroy them.
- Rather get 0 kills and take out an enemy FOB to prevent them from spawning than get almost any number of kills. I call this "cutting the head off the snake" or "pulling them out by their roots". Go for the critical hit, not the "hits" they will simply recover from very easily.
- The secret to winning games is LOGISTICS. Meaning how fast can your team move around the map. This is done with FOB networks and vehicles and "spawn shifting" and smart rally placements. The game is not really about outkilling your enemy, that may come naturally, but about out maneuvering the enemy.
- Squad is a points game disguised as a tactical game. If you have a good sniper that can kill 30 players and AT that can kill 4 vehicles while holding a flag, you might just win. Points matter. Points are called Tickets in this game.

[Back to top](#squad-field-manual)


## Tickets
- To win a round, one of the teams must reduce the enemy's tickets to zero or have more tickets than the enemy by the end of the round (a round lasts up to 2 hours).
- Tickets are essentially the team's available "reinforcements" during the battle, as the number of tickets a team has denotes the number of times a team's players can collectively respawn. If a team's tickets are reduced to zero or are lower than the enemy's by the end of the round timer, they lose the match.
- Both teams are given a limited number of tickets.
- Certain events during a match will result in either team gaining or losing tickets. Below you can see the ticket change on your and the opponents team for certain events.

Your Team    Opposite Team        Event
0        0            Player goes into incapacitated state
-1        0            Player dies or gives up
-2        0            Commander dies or gives up
60        -10            Capture a Control Point in game mode X

- Losing Vehicles - Ticket costs for your team
  - [- 5] Logi, Transport
  - [- 5] Light Attack and Recon Vehicles
  - [- 5] Anti-Air
  - [- 5] Helicopter
  - [-10] Armor Hunters, APC, IFV
  - [-15] Main Battle Tanks
- The majority (and the biggest and most important) of ticket costs are game mode specific. Therefore, please check the ticket section for each game mode to get the full picture. Ticket values may change in future updates. https://squad.gamepedia.com/Advance_and_Secure

[Back to top](#squad-field-manual)


## Control Points
- Control Point (CP), also known as "flag" or "cap", is an area on the map that teams need to capture.
- A CP is a certain limited area of the battlefield, there is not an actual "flag" in the ground.
- The capping radius (or even shape) of a CP may differ for each CP on the map.
- CPs can be either neutral or belong to one of the teams.
- At least 3 players need to be within the capping radius of a CP to capture it. At the start of a round, a neutral CP can be capped by one player alone.
- Cap time is approximately 60 seconds.
- If players from the opposite team are in the capping radius at the same time, players from the teams will cancel each other out. The team with more players in the radius will gradually take the CP.
- When you are inside the capping radius of a CP, the Control Point widget will appear. The flag shows who owns the CP and a progress bar shows the current progress of capping or decapping. The widget also shows the name of the CP.
  - Neutral CP show with a white bar,
  - those being capped or owned by your team show a blue bar.
  - A red bar indicates that the opposite team owns this CP (also indicated by the enemies flag; e.g. Canadian flag).
- The layout of the CP on the map may change for the same map from game to game. In some game modes CP can only be capped in a specific sequence (e.g. AAS, RAAS).

[Back to top](#squad-field-manual)


## Flags
- Main - The main base. This is where the game starts. Teams cannot capture the other team's main base. You cannot fire a weapon in a base. You cannot fire into a base (it has an invisible shield that protects it). It is your team's safe harbor.
- Neutral flags - Flags that have not been captured yet by either side. For example the very first flag once you leave main.
- Contested flags - Flags that have not been captured yet by either side and both teams are on the objective at the same time and try to capture it. The team with more people on the flag will capture it after 2 minutes. The middle flag often is contested by both teams at the same time.
- Middle flag - Exists only in map layers with an uneven number of objectives. It's the flag, well, in the middle. This is usually where both teams clash full force.
- Capped flags (by either team) - A flag that has been successfully captured by a team.
- Offensive flag - This is the next flag that your team is going to capture. It has a red knife symbol on your map.
- Defensive flag - This is the flag your team already captured. You can see it being represented on the map by a blue shield symbol. You need to hold these flags. If you lose these flags to the enemy, your team cannot proceed capturing additional flags. Should you lose a defense flag, your team has to move back and recapture it. Sometimes squads are back capping, which means they are protecting the already captured flags from the enemy. Back capping only needs 1 person on the flag. However, if that one person is being killed by the enemy, you're losing this flag and your offensive cannot continue until you recapture this lost flag.

[Back to top](#squad-field-manual)


# Capping Mechanics
- The examples below are mostly for AAS/RAAS.
- To capture a point, players must stand within the point's capture area until it comes under their team's control.
- The cap rate doesn't change with more people on the flag. One person captures as fast as 10 from the same team.
- Once a flag is captured you can leave the area with all soldiers, but this is not advisable. Should an enemy squad stop by they can easily neutralize this flag. Therefore leave some soldiers behind (also called "back capping)". It's not the most exciting job to do, but it is important not to lose any already captured flags. Doing so will prevent your team from capturing any other flags until they recaptured the lost flag.
- Neutral flags can be capped by 1 person (e.g the first flag once you leave main).
- It takes 2 minutes to neutralize a flag that was previously captured by the enemy and then 2 more minutes to capture it.
- It takes the same amount of time to go from captured (capped) to neutral as it does to go from neutral to captured (capped).
- For flags that were captured by the enemy you'll need to have a minimum of 3 people and outnumber the enemy in capzone by 1 to neutralize it.
- On contested points (those caps not yet fully captured by either team) you have to outnumber the enemy contesting the point. So, if the enemy enters the cap zone of a neutral flag while you're capping it, you need at least one more person than them to continue capping.
- Any flag that's not a current objective for your team, you won't be able to capture. For example you're not able to capture the flag after your current offensive flag. You first have to capture the offensive flag.
- Your team can only capture the next flag if they already captured the previous flags (those that go back towards main). And you have to keep holding these back caps.
- You need 3+ players to cap an active objective.
- On most maps, your defensive flag actually has a really small and hard to see blue bar under it that indicates the level of cap that it has. You can view this on the map to see whether your defense is holding or whether the enemy has started to cap your defensive point and what % is capped already.
- Many people get confused by the indicator that shows up when you're inside a capzone and capping the point. If the indicator bar is BLUE you are capping. The BLUE bar may be going down which indicates you are DEcapping what the enemy team has already capped. Many people panic and see the BLUE bar decreasing and think we are losing the cap... that is not what is happening. If the BLUE bar goes white, no one is capping. If the BLUE bar goes RED, the enemy is capping. OWI really needs to clarify this GUI element and make it more obvious as to what is happening.
- You can cap a neutral point with 1 person, assuming that point has not been previously captured.
- Capping any point that has previously been captured: you need at least 3 people in the cap zone, plus 1 more player than the enemy team has on that point.

[Back to top](#squad-field-manual)


## Ticket Bleed
- The enemy team will start bleeding tickets if you successfully capture at least one objective on the enemy side of the flag lattice. For each objective on the enemy part of the map, controlled by your team, the enemy will lose 1 ticket per minute.
- On map layers with an odd number of objectives, middle flags do not trigger ticket bleed. To introduce ticket bleed to the enemy, your team will need to capture at least one more flag past central. For example if there are 5 objectives to capture in total, your team would need to capture 4 objectives to introduce ticket bleed to the enemy team.

- For map layers with even number of objectives, your team will need to capture more than half of them to trigger ticket bleed on the enemy team. For example if there are 6 objectives to capture in total, your team would need to capture 4 objectives to introduce ticket bleed to the enemy team.
- In the case of a “double-neutral” stalemate situation, all ticket bleed mechanics will be paused until the stalemate is resolved.
- If one team manages to successfully capture all flags on the map, the opposing team will suffer a catastrophic ticket bleed of 60 tickets per minute to bring about the end of the round more quickly. This is the equivalent of 60 soldiers being wiped out per minute.

[Back to top](#squad-field-manual)


## Double Neutral
- A double neutral occurs when the enemy neutralized your defensive flag and you neutralized their defensive flag. Now neither of you can finish your offensive capture until you have retaken your respective defensive flags.
- Double neutrals are possible in AAS and RAAS. If you neutralize the offensive flag, and then lose your flag, the offensive flag will still be neutralized for the enemy, even if you can't see it on the map anymore. I've seen teams completely give up that advantage and leave the flag open for the enemy team to recapture because they don't understand that they're still holding it hostage.
- If the enemy team was starting to capture your neutralized flag before the double neutral was initiated, the defensive flag will continue to flash red, even though they're no longer able to manipulate the cap. Once a single friendly enters the cap range, the icon will stop flashing. This will be your guide for understanding when you've lost your hold on the enemy's flag. If that flag starts flashing red again, you've lost the double neutral and need to relocate.
- One thing to add. It's most confusing on RAAS because when the enemy neutralizes your defence flag and you neutralize theirs, you won't see the attack flag that you have neutralized. It is still there, and you are on the flag blocking it. There's just no indication. This always leads to squads leaving the flag they just neutralized since they think it's no longer active. It is just hidden. As an SL I always tell my guys that the flag is still here and we need to stay on it to keep the flag neutralized. Pretty much every single game the rest of the team will run back to the defence flag to try and get it back. The enemy will do the same, so you end up swapping back your flags and you're back to where you were at the start. TLDR; On RAAS the flag icon will disappear on a double neutral, it's still there and as long as you stay in the cap zone, you're still keeping the double neutral.
- To recap the double neutral flag you only need 3 friendlies in the flag, regardless of how many enemies there are.
- When you are attacking a point and it goes neutral, quickly check your map and look at the blue bar under your defensive flag. If there is no progression towards neutral, you won't go double neutral. If the enemy has started capping your defensive flag as you neutralize your offensive flag, you will go double neutral assuming no team stalls the cap of the other team
- Advice - Unless your situation is very stretched out and very likely to fall apart, focus your team on holding the double neutral while sending one squad to recap the neutral flag. They don't need to win firefights, only be sneaky, get in cap and stay alive. The rest of the team should focus on holding a secure perimeter around the offensive point. A common mistake teams make is everyone falls back from a double neutral, making it an easy recap and cap on the next point as an entire team moves between points.

[Back to top](#squad-field-manual)


************************************************************************
# Game Modes
- Squad can be played in different game modes.
- Servers will rotate maps, and sometimes game modes, after every match.
- The most common game modes are Advance and Secure, Random Advance and Secure, Skirmish and Invasion.
- Games can last up to 2 hours.
- The team with 0 tickets or the least amount of tickets at the end of the game will lose.

[Back to top](#squad-field-manual)


## (Random) Advance and Secure
- AAS/RAAS are control point modes. These modes are played on most servers.
- The objective for both teams is to capture and hold Control Points (aka flags) in a preset order (or in a random order in RAAS). Capturing enemy flags penalizes the enemy team and rewards you with additional Tickets. The team who first runs out of tickets will lose.
- AAS moves you along predetermined points that you can see at the start of a match, capture them. Stand near a location to capture it. Top right shows progress.
- Two teams will start from opposite ends of the map in their main base, or in certain circumstances a limited forward spawn area. The team's objective is to capture and hold Control Points from the enemy team. Control Points can only be captured in a specific order that will appear on the map
- Your team cannot capture a Control Point out of order, your team will need to capture and hold the previous flag. This is indicated by the Attack and Defense markers that appear over Control Points on your map (these markers look like a knife, respectively a shield on your map). - If both teams neutralize two opposing flags in the CP's line of sequence, it's a stalemate - neither team can take their next attack flag. - Only after a neutralized defense flag has been re-captured, the next attack flag can be captured.
- As each team starts to cap neutral flags, it's not possible by enemies to block this capping process. For example: if one soldier is in the capture zone of their team's first flag and nine enemies are in that cap zone as well trying to block it, the flag will still be captured. Once they find him and kill him, the flag will (obviously) stop capping. This should severely reduce the "Rush Flags" meta, and shift the focus more towards the linear progression of moving from flag area to flag area, as well as having a proper supply train with FOBs and logistics. Blocking a flag is technically still possible if you eliminate the entire attacking force, but it will require more resources to do and is more likely to fail.
- The team who runs out of tickets first loses. Therefore assets and FOB`s play a big role in the ticketcount of a team as well. Knowledge about the value of those assets can help you in correctly analyzing the situation of a team. Securing a flag while losing a lot of assets can actually harm your team's effort in winning a round.
- Furthermore, keep in mind that individual scores do not affect the result of the match.
- Ticket Values AAS/RAAS
  Gaining Tickets
  [+20] for capturing neutral flags that have not been owned previously. (ie: start of game)
  [+50] for capturing flags that belong to the enemy.

  Losing Tickets
  [-20] when the enemy captures flags that belong to you.
  [-10] for losing a Forward Operating Base (FOB; "Radio").
  [- 1] by Infantry lost (bleed out).
  [- 5] by Light Vehicles, Transports or Logistics lost.
  [-10] by Armored Personnel Carriers (APC) or Infantry Fighting Vehicles (IFV) lost.
  [-15] by Main Battle Tank lost.
- Ticket Bleed AAS/RAAS
  - The enemy team will start bleeding tickets if you successfully capture at least one objective on the enemy side of the flag lattice. For each objective on the enemy part of the map, controlled by your team, the enemy will lose 1 ticket per minute.
  - On map layers with an odd number of objectives, central objectives are considered a middle ground, and therefore do not trigger ticket bleed, to avoid causing King of the Hill fights for it. On such layers, your team will need to capture at least one more flag past central, for the enemy to start bleeding tickets.
  - For map layers with even number of objectives, your team will need to capture more than half of them to trigger ticket bleed on the enemy team.
  - In the case of a “double-neutral" stalemate situation, all ticket bleed mechanics will be paused until the stalemate is resolved.
  - Once your team captures all Control Points of the map, the enemy team will begin to Mercy Bleed. It's a fixed value of 60 Tickets over 60 seconds (the tickets tick down continuously every second). Mercy Bleed will stop if the enemy team manages to capture back the last Control Points.
- Example:
  - Let's say there are 5 flags on the map (this doesn't include main bases, those aren't really flags).
  - If each team holds 2 flags, and the middle flag is neutral (white), nothing happens.
  - If one team captures that middle flag and now holds 3 flags to the other team's 2 flags.. that will incur a penalty of 1 ticket loss every 30 seconds to the enemy team with less flags.
  - If you've got 6 flags in your match, and you hold 4 flags to their 2.. then it doubles: now you make them bleed 2x tickets every 30 seconds (or about 1 every 15 seconds).
  - Every additional flag you own more than them, the bleed stacks.
  - So in a 6 flag match if you own all 6 flags and they own 0.. yeah the bleed is pretty intense. Matches end in only a few minutes.
  - Just keep in mind that a ticket loss every 15 second means the equivalent of losing a 9-person squad every 2 minutes 15 seconds. That's like really fast. That's a squad spawning in and getting killed like as fast as they can. If you only had 1 flag over them, it's 1 ticket every 30 seconds which is like a whole squad being wiped every 5 minutes. Still pretty fast. If you kind of visualize that ticket loss, you can understand why holding flags are so important. In addition to the bleed, capturing a point from the enemy gives you instantly 50 tickets and the enemy loses 20 tickets.
- RAAS - Even though the next objectives seems to show up randomly, there is a site which can help to predict the next possible objective: https://squadlanes.com

[Back to top](#squad-field-manual)


## Invasion
- Invasion - one team attacks and the other defends, attackers need to capture quickly or they lose.
- One Team has all flags from the start and a huge number of points. The other team is the attacker, has only 200 pts, but usually has a major advantage to what vehicles they have available. Attacking team gets 100 tickets per captured flag. Once the attacking team has captured a flag, it cannot be retaken by the defenders.
- Defending team wins, if the attacking team has 0 points left. Attacking team wins when they capture all flags or the defending team has 0 points left. This mode has a very well defined front line as everyone is fighting for one flag.
- Might also be good for a first game although the beginning of the round is very hectic for the defenders and usually attackers have a hard time in this mode.

[Back to top](#squad-field-manual)


## Skirmish
- Basically like AAS, but on a way smaller map with less players. Sounds good to train, but gives the wrong impression about scale, distances, vehicles etc in the game. Would not recommend playing this first.
- Starting tickets are much lower than AAS and RAAS, generally, 100 tickets for each team. When a control point is first captured, that team gains 10 tickets instead of the 20 found in AAS. When a team captures an enemy control point, the ticket gain/loss is +20 / -20 instead of 30. This is due to the reduced number of tickets each team begins with. When a team reaches 0 tickets, that team loses the match.
- Skirmish layers are useful for seeding servers or low population gameplay due to their small size. Engagements are much more frequent and matches end quicker.

[Back to top](#squad-field-manual)


## Territory Control (TC)
- Territory Control (TC) consists of a grid of Hexes (hexagons), which function like capture zones.
- Hexes require 1 person to capture an initially neutral zone, but 3 people to capture an enemy zone (also after neutralizing it).
- Enemy hexes take 40 seconds to neutralize, and neutral hexes take 40 seconds to capture.
- Capturing a hex zone unlocks all adjacent (bordering) hex zones for being captured.
- Hex capture status is invisible until you capture an adjacent hex zone (fog of war).
- Each team has a 'key territory' hex marked with a shield, at the base of their grid.
- If any (group of) hexes owned by your team gets disconnected from that key territory (because the enemy captures hexes in between), you will not be able to attack bordering hexes from them until their connection to your key territory is restored.
- If the enemy captures your key territory hex, all your remaining hexes lose their connection to the key territory, so you'll need to recapture your key territory hex to continue capturing enemy territory.
- For every two hex zones captured beyond owning 60% of all hexes, the enemy will start bleeding 1 ticket per minute, with a maximum of 5 tickets per minute for 10+ hexes captured beyond 60%.
- When your team captures 95% of all hexes, your team instantly wins.

[Back to top](#squad-field-manual)


************************************************************************
# Before Joining A Game

- If you don't have a mic, get one. This game is all about communication. Also, know that text chat can be disabled. People may not see what you write (or they don't focus on text chat since they're busy attacking the enemy).
- Get a call sign that can be easily pronounced. It makes communication easier and it can help others to remeber you more easily if you're interested in making friends. It's not super important, but it can help in situations where your SL or another friendly needs to address you quickly. Also, it can help with immersion ("CHARGER HIT THAT TANK AT 2-3-0" has a different ring to it, than "Ah man, wow dude, how, what, what's your name... XxxSniperxxX_HD? COME BACK HERE ASAP!"). You can search for "military call sign list" or check out this list here http://www.udxf.nl/MCL.pdf to get some inspiration.
- Try teamwork. It will make for a much better experience for everyone.
- The game has a learning curve but it's super rewarding once you're in the groove of things.
- Squad is about playing your role within a team. Sometimes that means rolling in kills, Squad-score, and glory. Sometimes that means sitting on a hill for 30 minutes watching the world go by. Remember: it’s not all about you. The game is not about you.
- When you’re playing Squad, whatever you’re doing and whatever your role, your actions should be, in some way, related to the team’s objectives and/or the objectives of the particular gamemode that you’re playing. You should be thinking about the objectives constantly and asking questions of yourself and of your Squad. “Is what I am doing right now positively contributing to the team?”, “What could I be doing better?”, “What could we be doing better?”. This focus on playing the objective should be your preeminent concern for the entire round. Irrespective of what the 40 other players on your team are doing, you can make a difference by playing the objective. Sometimes, one player is all it takes to tip the balance in a firefight, on a flag zone, or at a FOB. Get your arse onto the point. Get behind some cover. Dig in. Help out.

[Back to top](#squad-field-manual)


## Training
- Do the training. Then do it again.
- Practice on Jensen's range and practice a lot! Try weapons, mortars, tanks, fly the helicopter, have fun and explore everything. Get used to rifle optics and see how far you can shoot.
- If you want to train on a different map than Jensen's Range, open your console and type AdminChangeLayer - a list will show up with all maps and game modes and you can choose one of them. If the map has a timer that prevents you from getting into a vehicle or flying the helicopter open your console and type AdminSlomo 150, which will speed up time. You can set time back to normal speed with AdminSlomo 1.
- You can explore a map with Shift + P. Move around with your usual movement keys. Find more information below under ## Admin Camera.
- Want to check out being a Squad Leader? Create a squad in the deployment menu (just name a squad and you'll be SL). Make sure to grab a SL kit. You can use map markers and place structure foundations (though you'll need a non-SL role to build them (the SL does not have a shovel).
- Want to be a Commander and call in air strikes? Create a squad first, then click on "Volunteer as Commander" and get your binos out, open your radial menu and click on "Request Tactical Support from Commander". Then go to the deployment screen and approve the request (right mouse click on the target area).

[Back to top](#squad-field-manual)


## Steam Workshop Maps
- The Squads Steam Workshop contains several training maps. Here are two maps that you might like.
- Access the link below and subscribe to either map. Then restart Squad.
- ERENEJ's Aim Training - https://steamcommunity.com/sharedfiles/filedetails/?id=2065975972&searchtext=training
  - To play this map open the console and type AdminChangeLayer AimTrainingMod
- Helicopter Training 2.0 - https://steamcommunity.com/sharedfiles/filedetails/?id=1904812886&searchtext=training+helicopter
  - To play this map open the console and type AdminChangeLayer Heli

[Back to top](#squad-field-manual)


## Good Roles And Jobs For New Players
- [Rifleman](#rifleman) (suggested role for your first few games)
- [Medic](#medic)
- [Automatic Rifleman](#automatic-rifleman)
- Logi Runs
  - Bring build and ammo supplies to the FOB
  - Tell your SL that you volunteer for logi runs. Learn how to drive a truck first and how you can load/unload it.

[Back to top](#squad-field-manual)


## Finding a Server
- First join Jensen's Range (the map where you train). Then search for a server. Most good servers are usually full and have a waiting list and you have to wait a few minutes. While you wait for the server to connect, you can train on Jensen's Range. The game will connect you automatically to the server once it's your turn.
- For your first game: Jump on a full server (you might need to wait a few minutes in the Queue, that's fine, don't join if the queue is > 5ppl). Preferably you should join a server in your native language to make communication easy. Join a Squad. If none are open, be patient, there will be one available in a few minutes. Have fun! Tell your Squad Leader you are new and need guidance, do as the says, kick ass.
- Ping is not super important in Squad. You will still have a good experience with a 150 ping.
- Many servers specifically say something like "New Players Welcome". Those are a good place to start.
- Pick a server with the gamemode AAS or RAAS. Maps usually change every round. You will most likely join an ongoing game.

[Back to top](#squad-field-manual)


## Server Rules
- Be aware that all servers have rules. Make sure to follow those rules. Violations can result in bans.
- If other people are harassing you, you can send admins a message (open console and type ChatToAdmin <message>) or ask your SL for help.
- Most servers' rules most likely are similar to the ones below:
  - Be friendly, stay calm, help new people, have fun.
  - Squad leaders must use a mic, speak English and make an effort to communicate.
  - Do not teamkill or intentionally wound a friendly player. Mistakes happen. If it was an accident, immediately apologize in all chat.
  - All vehicles requiring the crewman kit need to be 2 manned (unless RTB).
  - We have zero tolerance for racism or griefing or confrontation. Do not make things personal, degrading or confrontational on our server.
  - No locked 1 man squads (except logistics).
  - Do not open a squad in the beginning of the round if you do not intend to lead it.
  - If you want to use a vehicle, but there are other people waiting; Get in line and wait your turn

[Back to top](#squad-field-manual)


# Joining a Squad
- Join a Squad that has "INF" in its title, or does not have "ARMOR" or "HELI" in its title. If a squad has a not so serious name it's usually a good team to join. Those are often led by experienced SLs that just want to have a good time. Should you end up in the wrong squad the SL will most likely let you know and you can switch to another one.
- Do not create your own Squad yet, unless you know the game inside out. Play all roles in live games first before you lead a Squad.
- Pick the rifleman kit. This kit comes with an ammo bag that you can share with your team (e.g. your medic to get more bandages or LAT to get more rockets).
- Get a weapon with a magnified optic on it. You will be at a severe disadvantage without a magnified optic. For close quarter battles an iron sight may be better, but don't worry about this yet.
- Find a good squad that is talking and is willing to help. If you find that people don't communicate (especially SL) consider joining another squad. However, sometimes it's fun to stay in these Squads and to join random firefights, to explore the map and try new kits.
- You can tell if your SL is good based on
  - Communication - he/she is talking to you guys but not too much
  - Clear orders
  - Map markers
  - Picking fireteam leads
  - Telling people to swap kits to round out the squad
  - Helping you guys adding value to the team
- There are rarely toxic people in Squad. If you come across anyone being too noisy you can mute them in the scoreboard. There's a little speaker by their name on the list. Click on it.
- If people are racist/abusive let your SL know. Also, report them to the servers admin. Those people usually get banned. To reach an admin type this in your console: ChatToAdmin <Message>
- If the game is already going on, ask SL where you should spawn, before you deploy.
- When you join a game and a squad at game start, don't instantly spawn in. Wait a polite 10-20 seconds for the squad to fill and the SL to open his mouth. For a number of reasons. (1) The SL may be a shitbag that passes the kit over in 5 seconds that results in a hot potato squad and ruins the match start. (2) The SL may be micless and/or clueless. You want to avoid that. (3) The SL may have plans that don't involve all 9 squad members spawning straight away, you take this option away by running out and spamming F on a logi to... wait another 130 seconds in it.
- Ask SL for vehicle permission BEFORE spawning at main during a game. If your SL doesn’t want you to use it and/or wants you somewhere else you are either stuck at main waiting for a ride or have to waste a ticket to respawn.
- Follow the squad leaders orders and stay close to your squad unless told otherwise.
- Follow someone. If you are a rifleman try to follow your squads anti tank guy(s) because they will need your ammo bag. Often, your SL will put you in a fireteam together with a LAT/HAT guy and a medic.

[Back to top](#squad-field-manual)


## Communication
- Use your mic.
- Say 'hi' to your squad mates. You may be the first person to break the ice. If the squad is all clammed up, someone saying anything can help kick start the comms and the banter. Be positive and be confident. If you’re not, wing it.
- Tell your squad that you're new to the game.
- Ask questions. People are usually willing to help.
- If someone talks to you, talk back. Act like you're in the real world and not a video game.
- Chit chatting and making jokes while you're on your way to the first objective is usually fine. But listen to your SL if they want to tell you about the objective.
- Tell your SL/Team if you had a good time. Squad leading is hard work and showing some appreciation can brighten someone's day. Also, you can ask your SL if they're leading again next round again if you want to continue gaming.

[Back to top](#squad-field-manual)


## I Am Too Shy To Speak
- If you're shy you're in a great place. This is a perfect game for you. It will improve your confidence in talking with others greatly. Try it.
- Squad really helped a lot of people overcome their shyness and also helped many players learn to speak more confidently in English.
- The community is very welcoming and you're most likely surrounded by other shy people (that may or may not yet be comfortable to speak into their mic).
- Just start with enemy callouts. This and following orders is a Squad Leaders dream.
- No one will call you out for not chatting about random stuff.

[Back to top](#squad-field-manual)


## I Cannot Speak (I Am A Mute)
- If you're mute we want you to join Squad nonetheless! We won't leave anyone behind! You're one of us!
- If anything, send a quick message to your squad when you join that you can't use your voice due to medical reasons.
- You can add [MEDICALLY MUTE] to your name to let people know that you won't be talking.
- If you run into an asshole, let the admins know.
- Play medic class for absolutely no need to talk, most other classes other than command or scouting don't really need talking unless you see something.
- While speaking is helpful, even more important is following orders and playing as a squad.
- There are plenty of squads without speaking. These are the squads where the SL is just a filler and isn't really a squad leader. They don't care if you can speak or not.
- Be aware that not a lot of people read text chat a whole lot or quickly enough. Text chat can also be disabled in the UI, so some people won't see chat messages at all.
- You could set up a soundboard to play the most common phrases (take a look at the "Callouts" chapter).

[Back to top](#squad-field-manual)


## Callouts
- Before you use voice chat remember this: A.B.C. Accuracy Brevity Clarity. Your squad leader will thank you, and the rest of the squad will too.
- Always check your map if you're looking at an enemy or friendly soldier.
- Don't ever say "101 degrees" in Squad Chat. Any degree direction in squad chat is just useless, anybody not in local range will just get a confusing direction to look at. Stick to local chat for degree information.
- The grid is the numbers and letters on the edge of the map, A1 being top left and J10 being bottom right. Keypad is a subdivision of the grid location which is numbered like the layout of a keypad on your PC keyboard. 1 is bottom left, 3 is bottom right, 7 is the top left, 9 is the top left and 5 is the center, just like the 1-9 on your keyboard numpad. It allows you to very quickly give a precise location without needing to reference a lot more numbers on a grid and is easy for the SL to find the location fast.
- Grid locations should be used rarely. It's time consuming to bring up the map to figure out what grid you're referring to. Better to say "Enemy BTR north-west of the objective, on the road" rather than "Enemy BTR A5-6-4". Grid coordinates are handy though when there's an enemy HAB somewhere without any landmarks to reference.
- Call vehicles out to teammates and SL with the minimum information you actually know. Does it have tracks? Mention that. Which way is it moving? Etc.
- The more effective you can communicate the location of the enemy, the more quickly and more efficiently that you and your team can deal some death in their direction. Weight of fire and accuracy of fire wins firefights.
- The basic format of a target indication is simple
  - Distance (Make an approximate guess about the range. This is not vital and can be left out in a desperate situation.)
  - Direction
  - Reference
  - Type of enemy
- So, to put this into practice
  - CONTACT! 100 meters (Distance)
  - 300 degrees (Direction - use the compass at the bottom of your screen)
  - Top of feature (Reference)
  - 2 infantry (tanks, APCs, HMGs, whatever) in the open! (Type of enemy)
- In the heat of battle you’re never going to get the format absolutely perfect. And that doesn’t matter. What’s important is that you convey the relevant information: How far away are the enemies? In what direction? What is the enemy? And how can I help my buddies find the enemy?
- Examples Local Voice Channel:
  - CONTACT! 300 degrees ... Top of the ridge ... 2 enemies in the open ... About 100 meters
  - CONTACT! 2 enemies ... 100 meters ... Top of the feature ... At 300 degrees from my position!
  - CONTACT! 100 meters ... 2 guys with AKs ... 300 degrees ... Watch my splash! (proceeds to smash 100 rounds from the SAW in their direction)
  - 2 infantry north of YOURNAMEHERE position
  - contact north 005, infantry
  - Contact northwest bearing 330
  - Contact on our right/left/on the rooftop
  - Enemy squad flanking from the bridge
- Examples Squad Voice Channel:
  - "Tank 200m west of village. Sector F-4 keypad 3."
  - "Tank in F4, keypad 4"
  - "Enemies on the bridge"
  - "Enemy FOB in house in G6 Keypad 5!"
  - "Tank 100m West of tower moving from South to East"
- More Generalized Callouts
  - North, South, East, West
  - Left Flank (Left side), Right Flank (Right side)
  - Rear, 6 o'clock (Behind)
  - Upstairs (Above), Downstairs (Below)
  - Entrance (Way in), Exit (Way out)
  - Door, Window, Room, Rooftop, Deck (Floor), Overhead
    (Ceiling), Hallway
  - Trench, Ditch
  - Hill
  - Gun (weapon/turret emplacement)
  - Nest (turret/emplacement position)
  - Fort (Defend-able structure built for war)
  - Road, Path
  - Clearing
  - Forest, Tree-line
  - River, Moat
  - Mountain, Ridge line
  - Chasm, Deep trench, Ravine
  - Hole, Pitt

[Back to top](#squad-field-manual)


## Lyrics
You're probably wondering why there's a chapter called "Lyrics" in this guide.
Let me tell you, this is a very important chapter. Maybe one of the most important ones.

Imagine at the start of the match you and your squad loads up in a truck and you're heading off down the road. After a little chit chat someone starts softly singing "Take Me Home, Country Roads" from the very beginning of the song. Everyone stops talking, then someone joins in. By the time he gets to the chorus literally everyone in the truck is singing along... Your whole squad just road tripping through a forest singing together. Beautiful moments like these make Squad a very special game.

Learn to sing the songs below (very badly is fine) or keep the lyrics handy :)

### Take Me Home, Country Roads - John Denver

```
    Almost Heaven, West Virginia
    Blue Ridge Mountains, Shenandoah River
    Life is old there, older than the trees
    Younger than the mountains, growing like a breeze

    Country roads, take me home
    To the place I belong
    West Virginia, mountain mama
    Take me home, country roads

    All my memories gather 'round her
    Miner's lady, stranger to blue water
    Dark and dusty, painted on the sky
    Misty taste of moonshine, teardrop in my eye

    Country roads, take me home
    To the place I belong
    West Virginia, mountain mama
    Take me home, country roads

    I hear her voice in the morning hour, she calls me
    The radio reminds me of my home far away
    Driving down the road, I get a feeling
    That I should have been home yesterday, yesterday

    Country roads, take me home
    To the place I belong
    West Virginia, mountain mama
    Take me home, country roads
    Country roads, take me home
    To the place I belong
    West Virginia, mountain mama
    Take me home, country roads

    Take me home, (Down) country roads
    Take me home, (Down) country roads
```

### Fortunate Son - Creedence Clearwater Revival

```
    Some folks are born made to wave the flag
    Ooh, they're red, white and blue
    And when the band plays Hail to the Chief
    Ooh, they point the cannon at you, Lord

    It ain't me, it ain't me
    I ain't no senator's son, son
    It ain't me, it ain't me
    I ain't no fortunate one, no

    Some folks are born silver spoon in hand
    Lord, don't they help themselves, no
    But when the taxman come' to the door
    Lord, the house lookin' like a rummage sale, yeah

    It ain't me, it ain't me
    I ain't no millionaire's son, no no
    It ain't me, it ain't me
    I ain't no fortunate one, no

    Yeah, some folks inherit star spangled eyes
    Ooh, they send you down to war, Lord
    And when you ask 'em, "How much should we give?"
    Ooh, they only answer "More, more, more, more!"

    It ain't me, it ain't me
    I ain't no military son, son, Lord
    It ain't me, it ain't me
    I ain't no fortunate one, one
    It ain't me, it ain't me
    I ain't no fortunate one, no no no
    It ain't me, it ain't me
    I ain't no fortunate son, no no no
```
[Back to top](#squad-field-manual)


## Radio
- Wherever your squad wants to create a new FOB, your SL needs to place a radio. Within a radius of 150m of this radio your squad can build structures.
- The radio hub can be incapacitated by firepower above a certain caliber or dug down by a holding down right-mouse-click with the Entrenching tool (shovel). Satchel charges set by a Combat Engineer and Sapper or the improvised explosive device set by a Sapper are also very effective at lowering the health of the radio hub. Deconstructing the radio hub to below 75% will make the Spawn Bunker unspawnable.
- Once incapacitated, the friendly team has 40 seconds to rebuild the radio before it is destroyed. The timer can be stopped by building the radio back up to a certain threshold, the radio does not have to be rebuilt fully in the 40 seconds. During this time the enemy team cannot destroy the radio and must defend the radio while the timer is running, friendlies are the only players able to destroy the radio while this timer is running.
- Once destroyed, all tech structures and emplacements placed within a radio hub's build vicinity will be destroyed as well. Fortifications such as sandbags and HESCO blocks will remain. If an enemy player destroys your radio hub, your team will lose 10 tickets.
- Only a Squad Leader with a Squad Leader kit can place a radio hub and is accessed through the deployables menu by pressing T. In order to place a radio hub, the Squad Leader requires one other member from the team to be nearby and a logistics vehicle to be within 30-meters. In addition, a radio hub cannot be placed within 300-meters from another radio hub. This radius can be displayed on the map from the drop-down menu. Once placed, the radio hub can then be supplied by a logistics vehicle with construction and ammo points. These points are seen in the top right corner when a player is within the 150-meter build radius. Unlike deployable assets, a radio hub does not need to be constructed with an Entrenching tool.
- If construction points are available, the Squad Leader can then place deployable assets within the 150-meter build radius, which then need to be constructed by other team members with the Entrenching tool. When construction and ammo points are depleted, a logistics vehicle will need to deliver supplies from the main base in order to continue building and resupplying ammunition.

[Back to top](#squad-field-manual)


## Building Deployables
- Deployables are structures that Squad Leaders can deploy within the 150-meter build radius of a Forward Operating Base.
- Your SL can only place the structure foundation and will need your help to build it. Approach the foundation and get your shovel out and start building with your left mouse button. The right mouse button removes the structure (don't do that unless told to by your SL).
- Fire Team Leads can also place fortification structures
- For each FOB you will most likely build a HAB and an ammo box. The radio, as mentioned above, does not need to be build.
- You can help other squad mates to build a structure. More shovels build faster. Engineers and Sapper kits shovel faster.
- If you see enemy structures, you can remove them with your shovel by using the right mouse button.

[Back to top](#squad-field-manual)


## Running Around
- Avoid the compulsion to run around all the time, movement is easily spotted by the human eye. If you are close to enemies, move slowly.
- Stop and Observe. Use binoculars or optics to spot enemy movements before they spot you.
- Check the map often for intel and to get your bearings. Also, to see where friendlies are and if you have an enemy in front of you.
- Manage your Stamina. It's the bar that's being depleted when you sprint. Without stamina aiming and hitting something is nearly impossible. Stop sprinting when you approach an area with enemies so that your stamina can replenish.
- If you hear enemy weapons nearby in the direction your headed stop and try to figure out another route, maybe you can flank them.
- Never profile yourself on top of a hill unless absolutely necessary. You should try to use the terrain as cover as much as possible.
- It's often better to take a slightly longer route in cover than it is to take the shorter one across an open area.
- Moving across an open area is how you die, run fast or smoke. Let smoke plume before you move.
- When crossing terrain, choose paths of movement that minimize your exposure to any potential snipers. Always move in a way that puts you near buildings and environmental objects you can put between you and your attacker and use as cover if you get surprised or ambushed. You know how rats and mice in houses will run along the edges of the wall and behind things to try to stay hidden as they travel, you gotta be like that. You gotta be the rat.
- Don't get discouraged if you don't know the maps or where you are getting shot from. You will learn the maps while playing.
- Stick together - This isn't Call Of Duty. This isn't even Battlefield. You need to stick with your squad. Especially medics. I understand if we just met up with another squad and they need medical attention but as soon as their medic is up regroup with your squad. I've had countless times where my medics are 200-300 yards away busy healing another squad when I need them on my own squad members. Also this game is called squad for a reason. Teamwork is essential! Sure you may get a lot of kills as a lone wolf but you aren't helping the team when the objective is lost because you could have been the one guy that noticed a whole enemy squad coming up on the back.

[Back to top](#squad-field-manual)


## Map
- Rebind your map key so that you can reach it easily. Use a mouse thumb button or a key close to WASD.
- Red markers on the map mean enemies, but they are placed by players. This means enemies could be anywhere near there.
- Use your map to make an educated guess on where the enemy is, and when you need to be vigilant, which direction you should be watching, etc.
- Find out where your teammates are looking. They are usually looking towards the enemy in a firefight.
- If you're SL or Fire Team Lead (FTL) you can place markers on the map.
- You can use the map coordinate grid for callouts (e.g. "Tank in F-8").
- Each grid has a smaller sub-grid. The smaller one consists of 9 squares and is called keypad and is read from 1 to 9 like the numerical keypad on your PC keyboard. The square in the lower left is 1, the square in the upper right is 9.
- If you hover with your mouse over a grid you will see the actual position of your mouse. When you open the minimap by running you will see your player position on the left up corner.
- If you want to see all maps and objectives go to https://squadmaps.com/

[Back to top](#squad-field-manual)


## Identifying The Enemy
- Learn uniforms, weapon and vehicle sounds. This will make it easier to identify enemies and what vehicle is approaching your position.
- Study the faction uniforms on the team selection screen. This screen can be accessed during the game from the deployment menu.
- Identify something that's both easy to remember, and easy to differentiate between the two teams. This is usually something like overall uniform color, brightness, or camo pattern. For example: "the enemy is lighter," or "the enemy is darker green," or "the enemy camo is more splotchy." These generalizations are especially useful at the beginning of the round when you haven't seen the enemy on the battlefield yet.
- Find finer details about the enemy uniform that can help identify them. These are usually harder to spot in the field, but can still be helpful. For example: "the enemy all wear dark sunglasses." Ideally, look for traits that aren't shared with any of the kits in your faction.
- Take a close look at a downed enemy. This is even more effective if you can see one of your teammates near the corpse at the same time.
- Check your map often to see where friendlies are and are not. When looking at the map, I try to make generalizations or rules of engagement about the battlespace around me. For example: "there are no friendlies to the west." This understanding allows me to open fire immediately if I see any units to my west. These rules are often very short lived, so I open my map frequently to revalidate them or define new ones.
- Make liberal use of the scroll wheel when using the map. Changing the zoom level provides useful adjustments to the level of detail and context provided by the map. I zoom out to make more strategic decisions about where to move, attack, or defend. For more tactical decisions and actions, I zoom in as far as I can so that I can take notice of nearby threats, friendlies, and environmental features that can provide cover and concealment.
- The map and scroll wheel also help me with vehicle identification. If I hear a vehicle or helicopter, I quickly open the map, zoom out, and look for green or blue vehicles in the vicinity. If I don't see any, then I take cover and proceed accordingly.
- If you're still in doubt, wait for verification from the friendly player name tag. Note that the tags don't always show up or are often hard to see.
- You will still make mistakes occasionally and fire on friendlies. When this happens, be sure to apologize, and do your best to revive them if they're down. If you TK someone type in the console ChatToAll Sorry for TK. Admins see that you killed a team member and if they see an apology they know it was not intentional. They can miss apologies via voice channel, therefore always apologize via chat.
- Staying still and watching for moving pixels is the best way to spot enemies.
- Call Contacts - You shouldn't really shoot at an enemy unless you've been given the clear to fire. One of the things a lot of new players don't realize is you may want to get the kill but then no one knows where you're shooting. You need to call out the contacts using the compass at the bottom of your screen like "Contact at 330". Saying "Contact left" isn't going to do anything to help and so is just shooting at an enemy. Now on the not firing til given the go to shoot, you don't necessarily know what your SL is trying to do and when you shoot and give away your position you may have just messed up the SL's plan to sneak around the enemy flank.

[Back to top](#squad-field-manual)


## Firefights
- Any time you are under fire you need to be shooting back, it is literally the only chance you have in some cases. This game is centered around one of the best suppression models I have seen to date in a game. If you are being shot at, shoot back. Can't see them? Guess. You might be right. If anything it might get his head down and gives you a chance. The moment you return fire, even if just in the direction of fire, you created a 2-way firing range, and the entire tempo has changed. You now have him surprised, off guard, possibly suppressed, maybe wounded, possible dead with enough lead and luck.
- Don't be too far away from or right on top of teammates when attacking and defending.
- As for spotting enemies, look for movement, not shapes.
- Hold your fire if you spot a group of enemies in the distance. Let soldiers around you know (local com), let your squad know if it's an armored vehicle (squad com). If possible let enemies come closer or let them move to a position where they hardly find cover. Coordinate the attack with soldiers around you.
- Always use single fire. In CQB (e.g. in a building) auto fire can make sense.
- Hide behind cover and use your lean keys to expose less of your body.
- Someone shoots at you? Don't fret, and don't immediately go prone, and don't immediately go to your bandage unless your screen is blood red and you are about to die. Instead, try to move to cover quickly, dodge back and forth to make their next shots miss, and with each shot you cooerce out of them, you get more information about where you are being engaged from. Get to cover, then bandage.
- When you're running for cover use your freelook button and look around where the shots are coming from.
- Tracers work both ways. You can see where your shots land, and the enemy can see where they're coming from.
- Change position every now and then after you shoot. Once a single enemy soldier knows where you are they will let their team know. Peeking the same angle on an enemy again is how you die.
- To get an accurate range ask the SL or an FTL to tag a specific spot to get an exact distance. Otherwise, if you can see an enemy player, most scopes/binoculars in the game give you a way to estimate the range.
- ADS before peeking or rounding cover - This tip is mainly applicable to scoped weapons. Being zoomed in simply gives you a closer look at a target, making it easier to identify them as friend or foe. Aiming down sights doesn't happen instantly, and you don't want to lose that precious time if you round a corner and come face to face with an enemy.
- If you are dying constantly it is probably because of positioning and awareness
  - You are moving past an enemy position you don't know about
  - You aren't moving close enough to cover
  - You are visible from too many sides
- Do not waste TOW/Kornet (the guided rockets) shots on infantry
- Watch out for IED bikes and drones. If a bike is making a beeline for you, shoot that guy immediately.
- Learn to identify where incoming fire is coming from by sound. Bullets move faster than the speed of sound, so if you get shot at, you'll first hear the supersonic crack of the bullet passing by you, and then you'll hear the dull "thump" of the rifle that fired it. If you hear a crack, get ready to listen for the thump.

[Back to top](#squad-field-manual)


## I'm Dead, Now What?
- Not dead yet and still on your feet? You'll bleed at 0.3 health points per second until bandaged.
- Stamina will not regenerate if your health is less than 5 health points.
- If you're shot and on the ground wait for a medic. If no one is close to you ask SL where to spawn.
- Say "Thank you" if the medic fixes you up (or dies trying).
- Don’t click the “call medic" button as it’ll alert enemies in the area to your/the medic’s presence. Instead, call teammates via local chat because the enemy can’t hear that.
- However, you can use the medic call to bait enemies. Just spam it if you are alone and maybe the enemy will wonder if people are still near you.
- Also don’t give up when there are teammates nearby. You literally have 5 minutes until you die. Even if it seems impossible to be picked up now, a lot can happen in 5 minutes and the coast will probably be clear to be picked up in a bit. Be patient, it’ll save you time & tickets.
- However, sometimes respawning quickly and throwing away a ticket to win an objective can make sense. Sometimes you need pressure especially on invasion defense. Check with your SL.
- When the medic heals you, give cover and look for enemies, don't look at the medic. Also, try to stay in place so the medic can properly heal you and doesn't have to follow you around (this can lead to both you and the medic getting killed).
- If a friendly is dead, you can drag them by their feet/shoulders by approaching them crouched and pressing F to drag them.
- Drag downed players to cover, so your medic does not have to risk their life and can focus on healing.

[Back to top](#squad-field-manual)


## Tactical Respawning
- Sometimes it is smarter to die and spawn shift to the next cap, than to sit on a point your team just captured. Ideally, leave all enemies on that useless cap point behind while spawn shifting onto the next offensive point.
- It takes 60 seconds to run 100m in this game with no stamina, so balance that with respawning. Travelling takes time and sometimes you're needed somewhere else immediately.
- If you're in the middle of nowhere and you need to get back to a FOB, open the console and type Respawn. This will kill you and your team will lose a ticket, but you can spawn where you're needed.

[Back to top](#squad-field-manual)


## Being a Fire Team Lead (FTL)
- You can use build supplies at FOBs to place fortifications
- You can place 3 enemy marks on the map that everyone on your team will see
- You can place 1 Fire Team mark that will appear on the compass for everyone in your Fire Team
  - Your Squad Leader and the other FTL will also see your mark
  - Unlike the mark for the entire squad, FTL marks do not show their range on the compass
- To place marks, you can either hold T for the radial menu or right click on your map
- You can give Fire Team Lead to someone else on your Fire Team
- Leap frog with the other Fire Team on your squad to move around

[Back to top](#squad-field-manual)


## What If I'm Given SL?
- If your squad leader leaves the squad, then the first person that joined the squad will automatically be given SL. This usually happens if your SL was an asshat. Best practice would have been for the SL to ask who wants to be the new SL instead of just abandoning the squad.
- If you're a new player, ask your team who wants to be SL and hand it over to them in the deployment menu (right click on their name).
- If you want to remain SL, get an SL kit ASAP. Additionally, teach the person who gave you SL a lesson and kick them from your squad.
- Also, see Squad Lead tips below.

[Back to top](#squad-field-manual)


## Best Practices
- Ideally don't change kits in the field - this causes the ammo on FOBs to melt away fast (even though 80% is being refunded). Change kits ideally at main. In the same vein, changing kits to solve a problem is fine. Your squad desperately needs a medic, a crewman to repair a vehicle, or AT to kill that BTR trying to wipe you out? The extra ammo won't help much if you're all dead. Just remember someone had to drive or fly all that ammo out there and try not to be overly wasteful. Next time you rearm, check the ammo point cost of each item. You can also select a specific kit to rearm rather than grabbing everything (click on the individual items).
- When topping off ammo at a FOB be mindful only to refill what you need. The ammo is being shared across all team members.
- Don't shoot from the HAB/rally. Don't draw attention to our spawn area. In fact, get away from the spawn area. Stop spending your entire game within 20m of the HAB.

[Back to top](#squad-field-manual)


## Do Never
- Never dig down your own structures, unless specifically ordered to
- Never solo a vehicle that requires crewman, especially Tanks and IFVs
- Never mine friendly traveled roads or friendly HABs. Put mines where enemies are going to drive please.

[Back to top](#squad-field-manual)


## How To Make Friends in Squad
- Be a regular on a server and have a positive reputation.
- Play on the same server.
- Have an easy to pronounce and remember name.
- Answer questions teammates have.
- Talk to teammates, they don't even have to be in your squad. Make casual conversation (at appropriate times). Ask about the situation as you come up on teammates in the game. Make callouts of enemies you see. (it's amazing how many conversations I try to start up and the other person is mic-less, or so they seem to be, but 30 seconds later they finally start speaking... this is a huge turn off... talk ingame like you would IRL... would you ignore that person standing next to you talking to you?)
- Know how to play Squad and play the objective. This leads to other regulars knowing they can depend on you.
- Rally the troops and pull random blueberries doing nothing into a useful task. Like when spawning on a FOB. Announce that our FOB 200m away is going down and everyone that can hear you should help push and save it.
- Play 1 step ahead of your SL so he doesn't have to ask for things.
- Have a good time and see the fun in losing at times.
- In short, build a positive reputation among the community you play with.
- This will take months/years to get to.
- You can find people you played Squad with in Steam -> Profile -> Friends -> Recently Played With -> Add your new friend!

[Back to top](#squad-field-manual)


************************************************************************
# Infantry
- Infantry is an army specialization whose personnel engage in military combat on foot, distinguished from artillery, and armored forces.
- Also known as foot soldiers or infantrymen, infantry traditionally rely on traveling by foot between combats as well, but may also use military vehicles (motorized, and mechanized infantry) or aircraft (airborne infantry) for between-combat mobility and logistics.
- Infantry make up a large portion of all armed forces in most nations, and typically bear the largest brunt in warfare, as measured by casualties, discomfort, fatigue, and both physical and psychological stress.

[Back to top](#squad-field-manual)


## Rifleman
- Use the rifleman kit if you're new to the game. It's a great way to learn the basics.
- Choose the basic rifleman role WITH OPTIC and run that for a long time until you get a better sense of the game.
- You have an ammo bag (your backpack) that you can put down. Your team can refill their supplies with it. Very important for LAT, HAT and Medic. Ask them if they need to refill medkits/ammo. You SL may put you in a fireteam with HAT/LAT.
- Always keep your gun on semi-auto. Full auto may only make sense in CQB.
- Communicate things that you see to your squad.
- Move slower than you think you need to. Whenever I rush or think I'm too safe I get killed. That also has to be balanced, going to slow won’t get anything done.
- Once you have experience as a rifleman check out medic/auto-rifleman. Auto-rifleman is all about positioning and suppression. Medic is self-explanatory.
- Most of all, don’t be afraid to fail. Try new kits or roles and accept that you’re probably going to be shit the first few times. Youtube tutorials are a godsend for the more advanced kits like AT or armor.

[Back to top](#squad-field-manual)


## Medic
- Communicate - Secure - Rescue
- The Real MVP - As a Medic alongside the Squad Leader you form the backbone of your squad. The SL gets the show on the road but the medics are the true MVPs who keep it going. I want you medics to recognize your value and learn to say "No." You don't need to revive everyone always and you definitely should not put yourself in such a risk where the most likely outcome is that you end up dead on top of your buddy. Your survival should be a priority for everyone in the squad and if you think it's too high of a risk to revive someone in the middle of the road, you should have the balls to say "no, I won't" and that's fine. ‘You should never end up in a situation where you die with a bandage in your hand, that means either you've misassessed the situation or someone who was supposed to cover you messed up.
- Basic Gameplay - Basic play as a medic is pretty straightforward, you bandage bleeding or incapacitated friendlies and bring them back to full health with the medpack (or the Force). On top of that you're expected to be the last man standing in most cases to get the most out of your ability to revive others. Few tips to help you achieve this are to stay in the middle or back part of your squad in order to not catch the first bullet that comes your way. You're better off letting someone else catch it and go pick them up when the coast is clear. You also want to stay separate from the other medic in the squad so that you don’t both get killed in the same instance or by the same enemy. This often prevents the squad from being wiped too quickly. It's common practice to have one medic stay close to SL and the other with the rest of the squad to keep a simple separation between the two. Revive priority is SL + Medic > AT > Joe
- Communication & How to be an asset to your Squad
  - The easiest thing to do in order to go from "Yeah, it's some dude playing a medic" to "Holy shit that guy is super useful how do we recruit him now and have babies in the progress" is 100% communication as you can both relay critical information that nobody else has and talking to the people you're trying to rescue ups their chances of survival quite significantly. Firstly you've got the Medic Vision which allows you to see downed players in about a 150m radius around you regardless if they're in your squad or not. This gives you the best overall picture of how the fight is going and learning to relay the crucial information from this to your squad members and squad leader can change the pace of the fight and save you from getting flanked or losing assets.
  - Secondly you should be in constant communication with your squad members and the other medic to get your reviving responsibilities handled effectively and safely. As a medic you have a certain amount of authority and asking/telling the other individual to cover you should be a routine aspect about your game. When reviving players they should preemptively tell you critical information about their status like "There is an enemy standing on top of me" or "I got sniped from West but am in good cover so clear to pick up". Good players do this, but more often than not you need to demand it if you're unsure of what you're getting into. Again, your survival is more critical than the random Joe's in the middle of the street there. Once you are reviving them, if the situation demands it, tell them what to do as they get up in order to survive the next 3 seconds as well. Nothing is more frustrating than busting your ass saving a guy and having them stand up and get shot in the face the moment they're back in the game. So tell them not to.
- You have a rifle - Use it - As a last gameplay tip, do remember that while you usually play the friendly neighborhood doc, you're still kitted out to kill, even better than a normal leman. You've got the same kit with extra bandages and the ability to heal yourself fully in between taking hits... you're literally the Terminator in the right circumstances. Use this to your advantage and if there is no one else to clear the enemies for you, go do it yourself. You're always better off dying in a 1v1 fight that while won allows you to revive a friendly than walking straight up to the friendly and getting killed on top of them because the enemy was still watching his body.
- Common phrases for a medic:
  - "Don’t look at me - look at the enemy"
  - "Where did you get shot from"
  - "Are you safe to pick up?"
  - "X, cover me, I'll get Z up"
  - "I can't (won't) get you X, give up"
  - "No, you're in a shit spot, give up"
  - "X coming up, stay down!
  - "X coming up, cover the door"
  - "Medic low/out of bandages"
  - "Hey, other medic, I'll get X, you get Z"
  - "I'm coming to get you X, don’t give up"
  - "Good job X, you gave up just as I was getting you up. Idiot."
- Using Medic Vision to aid Squad members and relay information to Squad Leader
  - "Everyone in the HAB in F2 are dying"
  - "Everyone in the west building in cap are dead"
  - "Squad 2 just West of us is getting wiped"
  - "Hey X, the blueberry in front of you just died"
  - "Most of the squad is down, give us a moment SL"
  - "Both medics down, everyone give up"
  - "All friendlies died in the cap we just left"
  - "No friendlies alive in the cap, grenades free"
  - "There are some friendlies dying behind us, we might be getting flanked"
- Common mistakes for a medic:
  - Double medic is the behavior where 2 medics go revive/heal the same person. Don't do it. Just don't. It is a significant risk of losing both friendly medics at literally no reward to be gained by doing it. It's a senseless risk you don't need to ever take. Stop it.
  - Smoking on top of the player you're trying to save. AKA "shoot here - marker" - In most cases you want to throw the smokes in between the player you're trying to revive and the enemies shooting at him or watching his body. This way the smokes block the enemy line of sight more than they blind you and you might just survive in there. Throwing it on top of the guy you're trying to save lets the enemy keep a better overview of the situation and you're making the downed player and yourself a bullet/RPG magnet. It has a time and a place.
  - I'm a medic so I must medic - mentality. This is when you tunnel vision on nothing but reviving people and run around like with your bandages or medkit in hand in the middle of combat. Or running to revive a player who is downed only a second ago. What do you think happened to the enemy who killed him? Fall asleep? No. Don't end up dead on top of your buddy. You have a rifle - Use it.
- You need to stick with your squad.
- Be aware of your surroundings, make sure you know where the enemy is so you don't get killed trying to revive a teammate.
- Prioritize! Revive other fellow medics first, if there are multiple people down, bandage them all at the same time so they don't bleed out.
- Your safety before others. This means you need to make sure you're not under any fire or threat. Make sure you are safe! No point in trying to revive someone when you're taking MG fire in your direction.
- Last but not least, communicate! Use your local voice channel to tell those who are down to keep breathing and not go towards the bright light.
- Medics are important to ensure a victory for your team, as I've had many close games where we end up winning with less than 20 tickets.
- You have a shovel and can build structures too. Though this shouldn't be your primary objective when your teammates are down.
- Ask if they know where the shot came from and how much time they have left.
- Don't smoke your position, always smoke as far away from yourself as you can, in the enemies direction.
- While bandaging, freelook in that direction and if you see movement, abandon the bandage, swap to rifle and shoot.
- Bandages heal bleeds (blood droplet symbol).
- Kit heals health.
- Have to fix the bleed first then heal.
- Right click with kit heals yourself, left click heals friendlies.
- Second medic kit has long range optic.
- Try to always have a visual on your squad leader. If they go down before they can place a rally or FOB your whole squad will most likely lose the precious ground they just covered.
- If you go down, the squad goes down.

[Back to top](#squad-field-manual)


## Automatic Rifleman
- Your main job is to suppress the enemy.
- The purpose of suppression is to allow your squadmates to maneuver.
- Go prone, increase accuracy, reduce recoil.
- Short bursts, 3-5 rounds, don't just suppress for the sake of suppression.
- Smart positioning and movement, don't silhouette yourself, cover choke points, reduce exposure, move often.
- Stay in rear of formation, will be easier to provide cover when friendlies move forward
- Suppressing fire will absolutely force people into cover, but it typically has to be focused on 1-2 discrete positions, you can't just spray back and forth across an entire area. This typically means you can't suppress an entire squad.
- If you engage enemies, lay down, get your bipod out and lay down rounds on full auto. You get a massive boost to recoil control while prone with any bipodded weapon.
- Shoot and scoot. When you shoot any enemies in the area will be able to see where you are firing from. So move after firing! Reposition yourself and lay down some more fire! That technique is best used in open areas that are non urban. So move yourself depending on the situation and where you are relative to the hostile position. In urban areas just cover an area while prone if possible and kill anything that moves in sight, just be sure the only place you can get shot at from is also a place where you can shoot to.
- I find the SAW is much better in wide open terrain or urban settings where you can place yourself more deliberately relative to the enemy. In forests and hedgerows, where the enemy can appear from any direction, the lack of subtlety is more of a liability, and the raw firepower is less of an advantage.
- Your tracers will make you an irresistible target for everyone who sees them. Move often or have a good hidden position.

[Back to top](#squad-field-manual)


## Grenadier
- Use your sighting range with X and send long range nades
- Your smokes are amazing for pushing or covering movement
- Your main challenge will be estimating ranges and adjusting your GL launcher accordingly. This is probably 50% of the skill. It'll come with practice. Probably most helpful will be getting used to how big a typical soldier silhouette looks at different ranges for common reference points. When firing at longer ranges, opening the map and counting the grids (and estimations for diagonals). Ranging will be important when trying to squeeze those GLs into doorways and windows.
- GLs should mainly be used against concentrated enemies but this will rarely happen if you're going against an experienced team that knows their spacing. However people still have to spawn at a HAB and this could be your moment to shine.
- Another part of your skill and survival will be managing when to switch to GL and when to switch to your scoped rifle. You can often get caught out by the enemy with your GL out and not enough time to switch back. This is when n00b-tubing comes in handy - basically quickly snapping onto the enemy and GL-ing right under his feet, praying he's far enough for GL to arm.
- Throw smokes not exactly on top of enemies but fairly close in front of them. It's useful to smoke up stationary MGs, etc since riflemen will just reposition and the smoke plume is pretty thin. Remember that sometimes it may be more beneficial not to smoke up an enemy, e.g. if you have a vehicle supporting from behind just waiting for the dude to peek and take him out.
- Do smoke up enemy MGs and vics, forcing them to reposition, especially if they are sitting at a very good camping spot and causing trouble to defenders.
- Bear in mind that you may run into SLs wanting an extra rifleman rather than GL (for that extra resupply for his LATs) so you may not always have opportunity to practice.
- Player movement is damn quick, so not only will you need to be calculating distance, but you also need to account for your targets movement, and at range this can be very difficult against a target sprinting full-bore. Splash damage is weak enough that if you are even a hair too short or too behind, your target will just keep running. At range it is often better to take 10 potshots and miss 9 of them than it is to launch one 40mm.
- It is also a very map-situational kit. On maps where with lots of elevation differences like Fools Road grenadier is often not as good as regular old bullets.
- Marking smoke can really shine on urban maps, though. On Narva or Basrah it can be hard to make accurate callouts that distinguish between different buildings. See half a squad run into a building? Stick a red smoke to the balcony and holler in local chat, “enemy in red smoke building!”
- If you want to get more accurate with the GL, I'd avoid changing the sight zero and just wing it. Load up the firing range and just sit there for an hour shooting grenades at shit
- The HE grenades are great to put into compounds, buildings or tree lines that you know contain enemies but are not visible. It's basically for area denial as opposed to shooting at singular targets.
- Grenades will not arm if you hit targets that are too close (less than 50m).
- Smokes should be placed in the sight line between the location you desire to reach and the enemy when assaulting. Smoke in close to the enemy can also force them to relocate.They are very useful to mask compromised positions when defending to allow them to keep firing or reposition despite being bracketed. It's a marker though and should only be used when your cover is blown/you're ok with blowing your cover. This will become even more true once the helis are in the sky looking for it.
- GL smoke is for marking, not concealment. For example, there's a sniper in a bush up on a hillside, you have one of your smokes land next to him and a bright blue plume of smoke will show up next to him and he will be forced to retreat.

[Back to top](#squad-field-manual)


## HAT and LAT

- In squad there are two infantry roles which carry anti-tank weapons.
- The Light anti-tank also called LAT has access to a heat projectile rocket launcher with medium damage and is considered a defensive role in a squad to disable or mobility kill vehicles. The maximum number of LATs in a squad is 2.
- The heavy anti-tank role also called HAT is limited to two players for the whole team and is a far more offensive role which can outright destroy light vehicles and cause great damage to heavily armored vehicles.
- Both roles are crucial for the team to succeed, they can protect your squad from deadly vehicles and inflict heavy ticket losses on the enemy. Oftentimes a squad leader calls for an AT to be in the squad and for a 9-man squad it is frequently happening that both LAT roles must be taken at the beginning of the round. With the HAT role you are taking even more responsibility for your team and it is expected from you that you know what you are doing.
- Actually fire all LAT and HAT on Jensen's Range and learn the sight markings. They are different for each type of launcher.
- Learn what you can damage and where the damage will work.
- Rockets have an arming distance. Don't be too close to the target.
- The scroll wheel is critical for quickly selecting the proper rpg warhead. If you use the number keys, which many people do, the frag rocket is selected by default which can waste valuable time.
- Also at round start, if the squad leader has asked you to spawn, it's often a good idea to get into the vehicle with your heat warheads equipped, because you might run right into an enemy vehicle. The best way to do this is to sprint straight to the vehicle and select the heat rocket right before getting in, this will let you skip the lengthy animation, so your squad doesn't have to wait or leave without you.
- A loaded logi is your high value target. Here's a simple way to Identify a logistics truck, if you see barrels and some boxed stuff in the back, it's definitely a logi truck. You can prevent your enemy from building or supplying a FOB.
- Take a look at the vehicle models in Jensen's Range. Armors with different thickness are colorized on every vehicle. As you could see, frontal and turret armor are always the thickest, side armor will be thinner, and rear armor will be the thinnest one. To maximize the efficiency of Anti-Tank rockets, it's always the best to aim for the weakest part.
- Check the map for enemy vehicle positions.
- Clear your back since all of the launchers have back blast and can severely injure or kill your teammates.
- Always reset your zeroing after you have shot your rockets, if not this can lead to awkward situations where you overshoot way to far above your targets
- Run around vehicles if you are close to an immobilized vehicle if you have no ammo left, to distract them from other ATs, Some Turrets turn very slow and can be easily outrun
- Crewman’s that are trying to repair the vehicle are always exiting behind the vehicle or in case of tanks on top
- If crewmen are repairing the vehicle in cover out of your line of sight use a grenade to injure or kill them or fire a fragmentation rocket at the ground close to the vehicle the large splash damage area will kill everything behind the vehicle

[Back to top](#squad-field-manual)


### HAT
- The Heavy Anti-Tank is the most effective anti-vehicle role in Squad, equipped with the most powerful and greatest number of rockets. Given the kit's greater firepower compared with LAT, each team is limited to just two Heavy Anti-Tank kits. The primary Heavy Anti-Tank kit is unlocked when a team reaches 15 players and the secondary kit is unlocked when a team reaches 20 players. Each squad requires a minimum of three players in order to claim each kit. One squad can claim both kits, although allowing two squads to claim a kit is generally preferred. The HAT role falls under the Specialist role type, which is limited to two per team.
- Rockets specific to the HAT role include the M3 MAAWS 84mm Tandem rocket and 84mm High Explosive Anti-Tank rocket, (US Army), RPG-7 40mm RPG-7V2 Tandem Heavy Anti-Tank rocket (Russian Ground Forces, Irregular Militia, and Insurgents), and RPG-29 105mm Tandem Heavy Anti-Tank round (Irregular Militia, Insurgents).
- The minimum arming distance of HAT rockets is 40 meters. This means your target must be at a distance of greater than the arming distance in order to explode. Heavy Anti-Tank players need to be able to visually know how far the arming distance is in-game so as to not waste a rocket by firing on an enemy vehicle that is too close. The RPG-29 has a greater arming distance, closer to 25 meters.
- When playing as the Heavy Anti-tank, it is imperative that you know where enemy vehicles are on the map. Players in a squad and Squad Leaders themselves need to communicate with one another regarding the location of enemy vehicles, particularly Main Battle Tanks. Enemy vehicle markers should be placed by Squad Leaders whenever possible and deleted when unnecessary.
- HAT is one of the most valuable roles on the battlefield given its ability to destroy heavy enemy armor. The most important skills a Heavy Anti-Tank player can acquire is proper ranging and use of the Russian PGO-7 2.8x optic. Practice on the Shooting Range before playing on a server. Similarly, the same can be done with the M3 MAAWS of the US Army, with the only difference being that the sights can be adjusted to fit the target range, and the range markers on the sight change depending on the type of round that is loaded. Please refer to the RPG-7 page for information on how to properly range targets using the PGO-7 2.8x reticle, and the M3 MAAWS page.
- When possible, have a Rifleman remain close to the Heavy Anti-Tank, especially if heavy armor such as a Main Battle Tank is nearby. This will allow the Heavy Anti-Tank player to quickly reload using the Rifleman's ammo bag in order to fire another rocket if necessary.
- The Heavy Anti-Tank is often abbreviated as HAT.
- Helicopters may be hit mid-air with practice. For a 100m target flying straight at normal speed, one must aim 2-3 helicopter lengths ahead. Helicopters may seem closer than they actually are.
- Most HAT kits have both a stronger and a weaker rocket. If possible, fire a ranging shot with the weaker rocket first, aiming to disable tracks or wheels. Hold the rocket launcher still after firing, and observe which range mark the rocket lands on. This can be used to quickly and accurately calculate distance. Follow up with the stronger rocket.

[Back to top](#squad-field-manual)


### LAT
- Although LAT is not as powerful as HAT in terms of anti-vehicle capabilities, it is still a crucial role. LAT is a much less restricted kit, offering eight total slots per team compared with just two Heavy Anti-Tank kits. Also, more LAT kits come with a rifle equipped with an optic, making them more effective at long-range engagements as a riflemen.
- Each faction offers two types of LAT kits; a primary and a secondary. Every squad is limited to one primary and one secondary kit, unlocked when a squad reaches three and six players respectively. Teams are restricted to four primary kits and four secondary kits total, unlocked when the team reaches six, twelve, eighteen, and twenty-four players total respectively. The Light Anti-Kit kit is considered a Fire Support role, which is restricted to three per squad.
- The rockets used by LAT are the M72 LAW (US Army and British Army) 66 mm High Explosive Anti-Tank rocket, the RPG-26 (Russian Ground Forces) 83 mm High Explosive Anti-Tank rocket, and the RPG-7 (Russian Ground Forces, Irregular Militia, Insurgents) OG-7V Fragmentation rocket and PG-7V High Explosive Anti-Tank rocket. Please visit a faction's respective Wiki page for more information on specific kit load-outs. These rockets all deal High Explosive Anti-Tank type damage, whereas the rockets exclusive due to the Heavy Anti-Tank deal Heavy Anti-Tank type damage, which is calculated differently based on a vehicle's type and armor.
- Given the increase in the number of Vehicles in Squad, including Main Battle Tanks, the ability to destroy or disable enemy vehicles is increasingly vital to the success of a team. On Maps (layers) with a large number of vehicles, as many LAT kits as possible should be claimed. A team that is not able to effectively deal with enemy vehicles often loses a match, given vehicles ability to ferry troops across the map, supply Forward Operating Bases, and provide massive fire support on the battlefield.
- LATs should stick close to one another to provide sustained fire against vehicles since many vehicles require multiple hits from their rockets in order to be destroyed.
- Before firing a rocket, make sure none of your allies are behind you in order to avoid damage from back-blast. In general, players warn others in local chat by saying something like, "About to fire, clear back-blast!" before firing.
- Although LAT is not as capable at destroying vehicles as HAT, LAT rockets cost half as much to resupply as the rockets exclusive to the Heavy Anti-Tank. So although LAT rockets do less damage, they are less expensive to rearm at an ammo bag or ammo crate. See Ammo Crate for a full list of resupply costs.
- With the introduction of persistent ammo, players who spawn at a Forward Operating Base or Rally point will not spawn with any spent rockets. They will need to seek out an Ammo Crate, Vehicles with ammo points, or a rifleman's Ammo Bag in order to resupply. Switching to a LAT kit also means you will also spawn with no rockets, unless you spawn at Main Base.
- LATs are most effective when used to disable tracks/wheels, allowing follow-up shots from fellow ATs or vehicles. Crewmen will be forced to disembark to repair the vehicle, and may then be engaged.

[Back to top](#squad-field-manual)


### Engaging The Enemy With AT
- Always have cover - Try to get near a wall, a bush or inside a building, it is important for your success as an AT to survive the initial attack, and reload out of cover or get ammunition. Vehicles have a limited field of view and oftentimes a slow turning rate of their turrets, abuse that by hiding behind cover after you've shot your rocket. Gunners will have a hard time locating you if the distance is below 100m. But be weary of windows or trenches that can lead to death if a vehicle fires high explosive rounds at you. I recommend immediately falling back if you have successfully hit your target to reload. If possible, run back to an ammo crate or a Rifleman to resupply, avoid running over open terrain and if it's not possible to get to one just wait. Armored vehicles will often keep moving to avoid further hits from ATs. You can also use a nearby MRAP, or BMP nearby to resupply your Rockets. All vehicles except the Tank will always carry enough ammo to resupply you. It's also common for Insurgent and Militia Heavy ATs to park a bike or a technical nearby to resupply, as they consume a lot of ammo.
- Don't be too close - All Rockets have an arming distance, which means they can only explode after they have traveled a certain distance. For all Heat rockets the distance is 25 meters, for all heavy tandem rockets it's 40m. If the vehicle is too close to have, take distance or let it pass by you and then take the shot. Sometimes vehicles will try to use that to their advantage and will drive close to you so you can’t arm your rocket, oftentimes this results in the vehicle not being able to kill you because the turret can't reach that far down. The key to that problem is patience. Don't panic. If you have a launcher that doesn't take long to prepare like the law or the RPG-26, just take out your rifle and wait for a mistake by the driver then reposition. and get your Launcher back out.
- Don't give up    - Oftentimes it is tempting to just respawn after you missed your shot and died to a 30 Mill, just to resupply your missile. Don’t. if you do that ten times over and over it was not worth ticket wise to destroy that 30-mil BTR. You are still infantry whose main goal is to capture objectives and kill enemies. Wait for the medic and continue on fighting infantry instead of suiciding to get that one kill on the vehicle. Be patient and wait for mistakes of the vehicle crew like pushing your spawn hub or staying in an area where they have no infantry support.
- Mobility kills are important - Most of the time as an AT you will not have the opportunity to destroy a vehicle in two shots, you either have to do low damage as a LAT or you will not get the chance to shoot twice since the vehicle has already escaped. To mobility kill a vehicle you have to damage certain parts of it to stop it from fleeing. A rule of thumb is that aiming for certain parts of the vehicle is only important if you are below the 100m distance. Beyond that distance you will have troubles hitting targeted compartments, and probably miss on moving vehicles. Just get close to the vehicle or don't even try to get a mobility kill, it is more important to do damage instead of missing completely.
  But if you are getting a close shot onto a vehicle that is moving slowly or static, aim for important compartments.
  Vehicles with tracks like a tank, IFVs or the MTL-B and the Bulldog can be brought to an immediate halt by destroying their tracks.
  Every rocket is capable of damaging and destroying tracks of any vehicle, which makes mobility kills very easy.
  The crewmen have to exit their vehicle, and repair over a long time the tracks from outside to get the vehicle moving again. In this time, they are sitting ducks for any enemy vehicle or to more ATs that are then focused on damaging the vehicle. Oftentimes ATs will even push around the vehicle to kill the guy trying to repair it.
  If he is killed the armor is almost always lost, if no one comes to rescue them the gunner is either trapped in one position and forced to endure further attacks of rockets or he also tries to get out and risks to lose the vehicle altogether if he gets killed.
  Always destroy the tracks of the vehicle first. I even recommend for the Russian ATs to first use their normal heat rocket to track the enemy and then use their slow flying tandem on a static target to get a better chance of hitting it.
  If you encounter vehicles with normal wheels like a Stryker or a BTR you can try to aim for their engine to make significantly slow down. A vehicle with a damaged engine can't accelerate anymore, and also needs to be repaired from the outside.
  To hit the engine is far harder to hit and can be missed pretty easily. If the vehicle is moving too fast to be hit precisely in the engine, I would consider not aiming for the engine but for center mass. For MATVs and Scout cars it is not so important where you hit them because they get to a burning state in just two rocket hits. Lighter vehicles than these can be very easily destroyed by mass center hits.
  There is another option to hinder the capabilities of a vehicle by damaging their turret to a point where they can't properly turn it to engage targets. The most effective vehicle is the Crows system family, like the Stryker or the MATV-Crows, if the rocket hits right on the turret it will destroy the turret completely and render the vehicle useless, however the Vehicle will receive no damage and can safely return to base to repair. This strategy can be used for situations where the vehicle's body is behind hardcover or you have no prospect of getting any more ammunition to destroy the vehicle.

[Back to top](#squad-field-manual)


## Marksman
- The primary objective of the marksman is to provide long-range combat support for the squad. The secondary objective of the marksman is to conduct scouting operations in tactical vantage points against the enemy. This role is equipped with a rifle featuring a high-powered optic for long range engagements, a sidearm for emergencies, two field dressings for wounds, grenades (two variants), a shovel for construction of deployables, and a pair of binoculars for scouting and ranging targets. This role is strongly recommended to be used in large, open maps with little cover or urban maps with tall buildings. It is strongly discouraged to use the marksman in close quarters combat. If used correctly, the marksman can be the most lethal member of the squad and can inflict heavy casualties on the enemy when least expected. Resupply costs 50 ammo points.
- Stay near your teammates.
- Great for watching no man's land, like highways that infantry needs to cross.
- Surprise attacks are a must when using this role, use the opportunity to your advantage at all times.
- Using cover while on the move is also very important. Without it, you will be spotted and eliminated.
- Shoot and scout tactics should be taken into consideration. Staying in one spot during an engagement for too long will eventually lead to your death.
- Always make sure you have a safe spot to retreat to in case your engagement backfires.
- Be sure to keep a close eye on your ammunition, you do not want to be engaging the enemy on an empty magazine.
- Always be sure to stay close to your squad, fighting alone will guarantee no victory against a force larger than you.
- Make sure you always have the high ground, this will secure a better chance of victory in any engagement.
- Keeping clear communication between you and your squad leader is very important and will prove very helpful.
- Do not bite more than you can chew, think twice before you make a move against the enemy.
- You are the eyes and ears of your squad (and possibly others), your awareness as a marksman is crucial to the survival of your teammates.

[Back to top](#squad-field-manual)


## Combat Engineer and Sapper
- This is one of the only classes where you are allowed to roam.
- You should be hunting FOBs or laying mines.
- Place explosive devices to destroy enemy FOBs or objectives.
- You can also dig faster than other classes.
- And you can repair vehicles!
- The sapper/ combat engineer is a very situational role in Squad but is also one of the most important roles depending on the game mode.
- There are two different kinds of explosive specialists.
  - First the sapper for the insurgents and militia faction. The kit has 1 anti-tank mine, 1 C4 and 1 IED and a binocular.
  - The combat engineer which is available to the US, the British, the Russians, and the Canadian forces has 1 mine 1 C4, a repair kit, binoculars and a sandbag plus barbed wire.
- Both roles are not meant for direct combat, you are either in the backline doing logi runs, shoveling structures and pushing FOBs with your team or you are in the enemy’s backline disrupting logistics, placing mines, or destroying FOBs.

[Back to top](#squad-field-manual)


### Mines
- You can place up to 10 mines on the map.
- If the limit is reached a mine has to be blown up or destroyed to place a new one.
- To hide your mines, you can dig them into the ground with a shovel by pressing left click.
- The only way to disable mines is to dig them back out, use the right click for that.
- The mines are marked with a white skull on the map to help your teammates to avoid them because they do not ignore friendlies.
- Place your mine on crossroads, bridges or on entrances to objectives to destroy enemy logis and light vehicles or to damage armored ones.
- Don't place your mines in the way of: supply routes of your own team, backline objectives of your team or areas with friendly vehicles.
- Hide mines with rocks. However don't do that on asphalt roads as the rocks are sticking out and are spotted quickly. The rocks can also be used as a dummy to scare off drivers or to funnel them into another direction, where you placed mines.
- Place mines together in a line to blow up any vehicle instantly that comes across.
- Place mines behind and in front of abandoned vehicles, this way logis are taken out of circulation, and if rescued they get blown up.
- Use a disposable vehicle like a transport truck or a techie to get behind enemy lines and use it as an ammo dispenser for your mines. For the sapper I recommend a techie or a bike and for the combat engineer you could take a transport, a scout car or a MRAP to get behind the enemy. It is also useful to have someone with you if you are using a light armored vehicle. This way he can cover you and you will be able to shoot at vehicles while driving.

[Back to top](#squad-field-manual)


### C4
- C4 is an explosive charge that can be placed on the ground. It has a timer that takes 30 seconds to blow it up.
- The explosive has a killing radius of about 5 meters but deals only 75% damage to a radio.
- To fully destroy the FOB, you have to shovel the radio completely down which lets the enemy team lose 10 tickets.
- C4 also ignores walls and you can place them near the wall or below the radio to damage it.
- Spawn Hubs are also deactivated if the radio is damaged by 25% percent.
- This is visible through their model: at 75 HP it changes its model and at 25 HP the model changes again.
- You can also deactivate the spawn HAB if you can't reach or find the radio.
- However, the spawn hub only takes 25% damage and doesn’t get deactivated if you place C4 on it, you have to shovel it a bit down so it will be deactivated also any enemy can just activate the spawn hub again by just shoveling it for a few seconds.
- Since enemies will often push back to their FOB when it gets deactivated, have a teammate cover you while you destroy the radio. This way no one can spawn in if you both stay in a 30-meter radius of the HAB but the downside is that the enemy knows you there and will try to stop you.
- It can be stuck to vehicles which deals low damage to them and destroys any tracks.
- But for that purpose, there is another gadget that is only available to the sapper: The IED

[Back to top](#squad-field-manual)


### IED
- IED are remotely detonated explosive devices that have a very large kill radius and deal way more damage than C4.
- You can place up to 5 IEDs at a time,
- They deal enough damage that the radio is destroyed immediately and you need 2 IEDs to destroy anything but a tank.
- Because you can detonate them remotely some people use them strapped on vehicles as VBIED. Bikes are most suited for these use cases as they only cost 1 ticket, are harder to spot and are easy to maneuver. I don't recommend using any other vehicles for a VBIED as all cost 5-10 times as much tickets to use as a car bomb. The only exception is on invasion, where you have almost unlimited tickets as the defender and you can afford to lose some vehicles. Just don't use any logis or BRDMs as a VBIED because they are crucial for your team.
  Let someone else drive your bike into the enemy radio or positions as they can stay on the bike until they reach the target if you are doing it yourself you have to exit the vehicle first and then call the IEDs. During this time you can be killed and your IEDs be shoveled down.
- Another powerful option to destroy FOBs is to place IEDs on the top of the commander drone. He can fly the drone directly into enemy FOBs, where you can detonate the IED and destroy radios precisely and most often unnoticed because the drone is very silent and hard to spot in the sky.

[Back to top](#squad-field-manual)


## Raider
- The Raider is a kit only available for Insurgents in Squad.
- The primary task of a raider is to apply pressure on the enemy when it comes to close quarters combat. The raider is armed with a fully automatic, fast-firing PPsH-41, HE grenades for flushing out areas of enemies, smoke grenades for cover, field dressings for wounds, and a shovel for construction of deployables. This role can prove extremely lethal when clearing out rooms or tight spaces in urban areas.
- The raider should be the first one to enter a room and should be expected to die in the process. It is highly discouraged using this role beyond urban environments.
- Close quarter combat is the strong point of this kit, not open fields.
- Your PPsH-41 comes with a high rate of fire, use this to your advantage.
- Always be on the constant move but remain cautious as well.
- Use your grenades to clear out rooms and small spaces.
- The immense recoil created by your weapon will prove difficult to control at medium ranges, fire short bursts to counteract this problem.
- Surprise attacks should be taken into considerations as well. By doing this, not only will you cause confusion among the enemy, but fear as well, especially in tight spaces.
- Always keep your weapon raised during tight combat, quick reactions will save you in many situations.
- Always keep clear communication with your squad, update them as you sweep an area.

[Back to top](#squad-field-manual)


## Crewman
- The Crewman is a Specialist Kit available in Squad. Selecting the Crewman kit is necessary to gain access to many of the vehicle crew positions (driver, gunner, commander, loader) in the game.
- Equipping the Crewman kit grants access to many of the heavier vehicles in Squad. Infantry Fighting Vehicles and Main Battle Tanks require every crew position to be manned by a Crewman. Armored Personnel Carriers generally require a Crewman to drive the vehicle but only require a Crewman if the gunner is in an enclosed turret.
- There is also a crewman kit available for Squad Leaders.
- Like other kits, the crewman can be sourced from ammo crates and vehicles. The latter means that if a vehicle has the necessary ammo points, a player can switch to a crewman kit in order to crew a vehicle. Note that light vehicles and Main Battle Tanks only allow the Crewman kit to be selected.
- The Lead Crewman is one of the Kits available in Squad. This kit is necessary for crewing APCs, IFVs and MBTs in the driver and gunner seats. It basically is a Squad Leader kit with Crewman abilities.

[Back to top](#squad-field-manual)


## Pilot
- The Pilot is a Specialist Kit available in Squad. Selecting the Pilot kit is necessary to fly the helicopters in the game.
- Equipping the Pilot kit grants access to helicopters in Squad. Infantry Fighting Vehicles and Main Battle Tanks require every crew position to be manned by a Crewman.
- Players can change to a pilot kit from a helicopter. This means that if a helicopter has the necessary ammo points, a player can switch to a pilot kit in order to fly a helicopter.

[Back to top](#squad-field-manual)


## Mortar
- Mortars cost 250 points each.
- Only two mortars per FOB are permitted.
- Each reload (3 rounds) costs 90 ammunition (1000 ammo = 11 reloads)
- Right click to view crosshair (decreases aim sensitivity). The numbers on the left are called milliradian. The numbers on the bottom (your compass) are called degrees/bearing/azimuth.
- Left click to fire, you can shoot three mortars at a time.
- Mortars take 20 seconds to land once fired.
- Mortars have a minimum range of 50m and a maximum range of 1250m.
- What you're planning to hit is very important. From the time you decide to shoot something to the time you hit it there's about 40 seconds so don't shoot anything that's moving. Emplaced positions are best, HABs are the #1 thing you should be shooting at.
- Running a mortar squad requires a bit of work on everyone's part. Here's what you'll need:
  - A surplus logi that your team does not absolutely need. Mortars are a luxury. Do not make your team lose because you took the only logi.
  - Good FOB placement, and usually on a small/medium map (for rapid logi runs).
  - Mortars built in a safe/hidden and distant position.
  - People willing to shoot mortars all game.
  - Person willing to do logi runs all game.
  - People willing to spot/follow SL all game.
  - Valid and accurate targets.
- Team Structure
  - Name your squad "Mortars".
  - Keep the squad members to a minimum amount.
  - You'll need one person doing logi runs (for ammunition).
  - Two people shooting the mortars.
  - Spotters, preferably multiple fireteam leaders.
  - Multiple fireteam leaders are very beneficial. If you put a spotter and mortar in each fireteam, the mortars can basically work independently. It takes lots of weight off your shoulders as the squad leader.
- Make sure you're using a mortar calculator, you're not going to hit much without one. SquadMC is a great one, but you may want to check out some others.
  - https://squadmc.ende.pro/
  - https://squadmortar.xyz/
  - https://mortar.sharkman.info/
- Basic Firing
  - Mortars disperse by about 15-20 meters from where you aim.
  - This is not enough deviation unless you're shooting static objects.
  - You must spread the mortars out to be effective.
  - Keep in mind what your goal is (Suppressing a compound? Killing a HAB? Providing smoke cover?)
  - Adjust volume, spread, and type of shells to your team's needs.
  - Timing. Time your shots if necessary. Don't waste ammo if your friendlies won't be there for a while.
  - As a mortar squad leader, you MUST be able to see all rounds coming into your targets. So I suggest using a vehicle on the fringes of the map to get to a good observation point. The Afghan maps are by far the easiest to find a Forward Observing position (FO - Forward Observer) but most maps will have some type of high ground you can utilize - it's important to not reveal your location by being seen or firing your weapon unless it's 100% crucial.
  - Let your other SL's know that your mortar team is available for fire missions - and that they should use the num pad keys to communicate directly with your squad to request it. have them put a marker on the map requesting a fire mission. From there confirm with the person requesting the fire mission what is there and what the target is. Once you confirm the mission, try to be in a position where you can observe the rounds falling if possible. Place an observe marker on the map centered on the location for the fire mission and direct your mortar team to "standby for fire mission, orient on observe marker, standby for mils."
- Adjusting Fire
  - Mortars, by their nature, won't always land directly on the target, which is to be expected. That being said, they are still accurate enough to take down HABs, vehicles, and even radios. If your shots actually are off, you'll have to adjust fire. Think about where your mortars are, and where they're landing. Telling them to add 10 milliradian will make the mortars land a bit closer, whereas moving one degree will cause the mortars to land a bit to the left or right. This all depends on the range of course, and you'll want to remember that even a half degree at 1000 meters will be significant compared to a half degree from 150m. Adjusting fire takes some getting used to, and you'll get better with experience.
  - Add milliradian = mortars land closer
  - Subtract milliradian = mortars land farther
- Targets
  - Infantry/objectives = dispersed, conserve ammo (unless you have enough ammo)
  - Stationary targets = no dispersion, rapid fire until out of ammo (if accurate)
  - The best target of all is a HAB. Taking down an enemy HAB puts them in a very difficult position, so long as you keep firing. If your mortars can hit their HAB, you'll usually be able to kill it, so long as you have ammo. Even if enemies stay inside and rebuild it (which is very rare considering how fast HABs will fall to mortars) you'll still be killing everybody else who leaves it, bleeding their tickets. Only two things can stop you: They find your mortars, or you run out of ammo.
  - Killing enemy mortar crews with your mortar crew is kinda fun, too.
- Complications
  - Height Offset - One thing to consider with mortars is the height at which you are firing. If you're firing from the top of a mountain, to a flat spot on the map, then you may end up overshooting. Calculators such as https://squadmc.ende.pro account for height differences, but you may want to stick to flat areas just in case.
  - Degrees At Range - Say I'm shooting a mortar at 150 meters, then I aim right one more degree. There will be a slight change to where the mortar lands. However, if I fire at 1,000 meter and aim right one degree, the mortar will land significantly farther than before. This is something to keep in mind when you're adjusting fire, and is a reason why you may want to use half degrees, or quarter degrees.
- Having a dedicated mortar team with experienced players that understand what they're doing, good drivers that can stick to the route and avoid enemy ambushes to keep the supplies flowing, and good intelligence to feed to other squads from a few guys with optics/AT roaming around behind enemy lines can turn close games into clear wins. These squads are great because they can get players who would otherwise be lone wolves on an important task that contributes directly to victory.
- Always remember, there's going to be games where your mortars are just useless if your team can't get organized well enough to even use them and you keep getting gunned down trying to FO. You have to be willing to just say screw it, and just send your full squad into the objective when you need it.
- Commands to test mortars in firing range
  - AdminChangeMap Fool's Road AAS v1
  - AdminDisableVehicleClaiming 1 (allows you to claim any vehicle)
  - AdminAlwaysValidPlacement 1 (allows you to place anything you want)
  - Adminslomo 20 (speeds or slows in-game time)

[Back to top](#squad-field-manual)


************************************************************************
# Vehicles

- To enter, exit, rearm, or switch kits off a vehicle, press and hold F.
- To switch seats, press F1 to F12. For a short moment, you will also see a list of the current passengers of the vehicle.
- Entering or exiting vehicles and switching seats inside vehicles is not instantaneous. The duration depends on the vehicle and the type of seat. This greatly reduces the effectiveness of soloing vehicles when a vehicle is flanked or ambushed. Either it will not be able to drive away or it won't be able to return fire instantly.
- To drive a vehicle, you must first claim the vehicle, you may then enter the driver's seat and start the engine.
- To start and turn off the engine, press and hold E. To be able to start the engine, make sure you have assigned a keyboard key to the vehicle control "Vehicle toggle engine" in the settings menu (default E).
- To maintain the current gear, press and hold ⇧ Shift.
- If you are a gunner and your vehicle has zoom mode, zoom in by pressing Q.
- If you are the gunner in specific vehicles you can stabilise your view by pressing Z
- The WASD keys control traverse and pitch on all vehicle turrets except for the KPVT, NSV-T, PKT turrets, and open turrets.
- Most vehicles also carry some amount of supplies. While the vehicle is stopped, any teammate in or next to the vehicle can load and unload the supplies using the radial vehicle interaction menu (press and hold F). Multiple players can load or unload the vehicle faster than if it were just one player.
- Unoccupied vehicles that are not in 150m of a Rally point or a Forward Operating Base will start to burn after 20 minutes.
- Different surfaces provide different amounts of traction and rolling resistance, referred to as Physmat. This means that going off-road will make a vehicle much slower than staying on the roads. Wheeled vehicles are more affected by this than tracked vehicles.
- Wheeled vehicles will roll much better on asphalt than on mud or snow. The lowest resistance is on asphalt, concrete, and solid wood. Gravel comes next, then dirt and grass. Sand and snow are where you're really starting to suffer. Lastly, mud has the highest resistance and is terrible to drive on.

[Back to top](#squad-field-manual)


## Vehicle Types
- This is the vehicles section of the guide, which gives a brief description of each vehicle type in Squad.
- APC: Wheeled with .50 cal (Armored Personnel Carrier). APCs are usually wheeled, some have tracks, but they have a smaller gun than other vics. Medium armored with armament that can pierce other APCs and other vehicles with lower armament ratings; can carry a squad of men; includes Stryker with CROW, BTR-80, and most MT-LB variants. Have 600 ammo for resupply.
- AT vehicle: Techie/MRAP w/ ATGMs (Anti-Tank Guided Missile)
- Helicopter (Helo) - a flying machine used for resupply, FOB creation, and troop transport. Can also do recon or provide light CAS, but weak in terms of armor and armament. More on helicopters in the next chapter.
- IFV: Tracked or wheeled with canon above .50 cal (Infantry Fighting Vehicle). The Russians have a BTR IFV (wheeled) and a BMP IFV (tracked) (Russian Armored Transporter). IFVs are usually tracked, with a lot of good offensive options. Medium to high armor with armament that can pierce other IFVs and other vehicles with lower armament ratings; some have HAT capabilities with ATGM systems (Anti-Tank Guided Missile); include Bradley, MT-LB with 30mm, and BTR-82A. The difference between APCs and IFVs is a little bit of a gray area since IFVs are technically a subclass of APCs.
- Logistics Truck - open roofed truck with supplies in the back; include Ural and M939 variants that can hold 10 people and 3000 supplies.
- MBT: Tracked with one big fat gun (Main Battle Tank). Heavily armored fighting vehicles that carry heavy armaments able to pierce other MBTs and other vehicles with lower armament ratings; sacrifice men capacity for armor and armament; include the M1 Abrams and T-72 B3.
- MotorBike - fast and agile bike that can glitch out sometimes and get you killed; holds 2 people
- Scouts are wheeled vehicles with a small gun
- Techie/MRAP: Four-wheeled with .50 cal or 7.62mm, fast and lightly armoured (Mine-Resistant Ambush Protected). Have 150 ammo for resupply.
- Technical Logistics - small truck that carries supplies; holds 5 men and 1400 supplies.
- Transport Technical - small truck that can carry a lot of men; includes the Transport Technical that holds 8 people. Can also carry a small supply of ammo for resupply.
- Transport Truck - open roofed truck that can carry a lot of men (compared to the other vehicles); includes Ural and M939 variants that can hold 18 people. Also carries a bit of ammo for resupply.

[Back to top](#squad-field-manual)


## Vehicle Basics
- Any vehicle other than scout ones need a minimum OF 2 crewman roles to operate effectively. A 3rd vic member can be a HAT, LAT, or Medic, and should be on the commander seat of the vic to mark targets and keep lookout.
- Protect your vic and don't fall for your team's pressure. Sometimes you have to make decisions in order to save the tickets of your vehicle or to make sure your team won't lose the asset and people will get mad at you for "not helping the team". It's not common, but it happens and you must not fall for it. YOU are the one using the asset, you should know where you can put it and where you can't. If a situation feels disadvantageous, leave and search for a better position to engage. Your team located an enemy tank, but your hull is at 35% and you can't engage at long range? It might be a bad idea to engage that vehicle at this time. It's a map with 2 tanks each side and the other allied tank got completely destroyed without hitting any of them? Play defensively until an opportunity arrives. Decision making is important in these sorts of high value assets because losing them is costly for your team. You don't want to give your enemy tank free reign to destroy your team by losing your tank in a stupid situation/stupid call from a SL. You might not be as useful as you start practicing but, in time, you will learn the dynamics of tank warfare and you will be much more useful to your team than just wasting your tank after 5 mins of a match.
- Always try to get a fully manned MBT. More eyes in the field, more protection against HATs, more people to fix it up should you get in a bad situation, more people to dig up Repair stations in forward FOBs. There is no reason to not run fully manned tanks, not doing it is just making your asset weaker, especially if you have friends/groups/clans that can play with you.

[Back to top](#squad-field-manual)


# Training
- In Jensen's Range there is a vehicle hitbox reference table next to the line of vehicle tents. Use this to see where vehicles can be damaged. Each vehicle has unique armor zones and weak zones.
- Practice/play all roles within a tank, also practice different tanks. If all you want is being a gunner, you might not understand what the other crew members need to be doing and it might lead to frustration and defeat. Try to find a group/clan to play together often, it will increase your effectiveness by far.
  - Both T-72s are very slow when reversing, the cannon round goes off a bit to the right and its autoreload is slower than the manual reloads of the Abrams, for example, but its low profile, it only requires a crew of 3. The top gunner is remote and it's quite fast moving forward (for a tank, that is).
  - The Abrams is very loud and high profile, very easy to distinguish, the range finder is a bit weird, but the front armor has a greater chance of deflecting rounds than most tanks and its top gunner is also remote.
  - Challenger has a weird measurement of range, it can't fire backwards effectively and its quite high profile as well, but it's quite fast moving in any direction and very maneuverable.
  - Leopard has a very different ranging system that gives him quite big of an edge in long range engagements but it's awkward to use at close range, but it has a somewhat lower profile than most tanks
  - The T-62 is very exposed, but its very low profile, making the least noise, its fast, requires only 3 crewmen and of all tanks, this is the one with the greatest chances of deflecting rounds directed at its turret.
- Also, practice all tanks so you know their strengths/weaknesses and how to range/maneuver them.
- Good drivers are good gunners. Swap roles mid match if possible so you both understand each role.

[Back to top](#squad-field-manual)


## Moving Around
- If you have friendly infantry nearby it doesn't mean you are safe, ALWAYS keep moving.
- It's a good strategy to keep vehicles out of the city because they're easy targets.
- Urban environments are dangerous - Ideally, you want to have the range on your side, since it's one of the greatest advantages of a tank over most enemies and urban environments are the antithesis of that (also true for real life engagements, MBTs don't usually go inside a city unless it's a hard push of combined arms, meaning they have support of infantry/air and information about enemy positions). Unless you are supported by a lot of infantry, it is usually best to secure the outskirts of a city/town/village, providing fire support to the troops going in. If you have to get inside an urban area, search for areas where you can put some distance between you and buildings/enemy vehicles so as to not be surprised by ATs/enemy vehicles. Whatever you do, urban areas are bad and the chance of being tracked/destroyed are higher than in any other environment. A somewhat decent strategy in urban areas is playing defense of a point while your team attacks the next point, it allows you to pick a position and turn the engine off, playing overwatch of a certain road/building/point.
- Don't stay in the same area for too long. This is especially important if you know that there are enemy MBTs/IFVs active and relatively close to you. Your gun makes A LOT of noise and when you start mowing down enemies, they will know you are there, they will mark the shit out of your position. One of the strategies used also in real life is finding a position to fire, fire a few rounds and reverse to a safe spot using smoke, then relocate to a new spot. Standing still is just making it easier to your enemy. There are situations where you can stay longer, like for example, you have put pressure on a capture point, your troops are moving in and the enemy is retreating. Stay a while to make sure no one tries to take the point back from another direction, then move as soon as possible.
- If you are not relocating soon, turn the engine off. Tanks have a loud gun and a loud engine, try to reduce your signature as much as you can. If they can't see you and can't hear you, you have the element of surprise, which is a decisive factor in many engagements.
- Move as fast as possible whenever possible to avoid enemy fire.

[Back to top](#squad-field-manual)


## Engaging The Enemy
- Use the right ammunition types for the right target, fragmentation is great for infantry but isn't going to do shit to vehicles.
- MBT vs MBT - I see so many people get tank fights totally wrong and it leads to their demise. If you are playing a T-62 and your enemy has a Leopard, for example, you must know how to engage, otherwise things will go bad for you. First of all, IF YOU CAN, engage the other MBT at long range. If they can't see you and you can make the first shot, it's a big advantage and you should use it when you can. If the engagement is at medium or small range (less than 500m I would say), focus on disabling it, usually it goes like this: tracks/engine, turret, boom. Why? Why shouldn't you just shoot whatever and take them down, especially if 4 good shots are all you need to take one down? Because you might be in a situation where you were engaged first and the only advantage you can have in this situation is disabling that tank and outmaneuvering it. If they can't move, you can relocate to a better position where it will take them more time to acquire you and shoot you down, also they are a sitting duck for anything else in your team to disable it. Disabling turrets is not as easy as tracks/engine, but it's the biggest advantage you can have, maneuvering on them and finishing the job is a lot easier if you can manage that. Also, unless you engaged first, KEEP MOVING. This is very important and people don't do it enough. The gunner needs to practice firing while moving, because standing still is like asking to eat enemy rounds. If they already see you, while make it easier to the enemy by being a stupid target practice? If you can put a hill/rocks/buildings between you and the enemy, even better, you can use the smoke strategy I've mentioned earlier to keep engaging/disengaging as needed and might not need to move as much.
- You can't really help infantry unless you kill the enemies armor first or know they won't be in combat near you. The IFVs are called IFVs for a reason, so it's smart to let them kill infantry instead and protect them from enemy armor.
- When using tanks stay away from objectives and flank. Knowing what roads the enemy armor might take or places they will go to helps (you'll learn this with map knowledge and just trial and error).
- Also, avoid being spotted or being too close to enemy infantry, these can ruin a tank run.
- Talk to command and ask for enemy armored locations helps but it is usually called out anyways for all squads to know (and marked on the map). Use this knowledge to guess the enemy's intent based on location (to objectives or friendly's) will aid in your survival and their death.
- Tanks can ram and move smaller vehicles.
- Kill infantry with HE rounds and machine guns.
- Check your map , anything relevant will probably appear there right.
- Use your zoom optic.
- Try to spread armour squads out so you don't lose both your tanks in one spot. This also allows your tanks to cover more ground and kill more infantry.
- Don't fire the ATGMs first they take too long to reach their target and you may be hit with two tank shells by then. Primarily use ATGMs against helicopters.

[Back to top](#squad-field-manual)


## Damage and Repair System
- Engines, tracks, wheels, ammo can, turret; can all be damaged and have different effects on the vehicle.
- Damage has an angle of incidence, meaning how square you hit your shot matters. A nice perpendicular angle to your target on a weaker armor spot matters big time. A shallow angle shot will cause your rocket to bounce off. Dark black smoke means you got a good hit on enemy armor.
- Do not get out of your vehicle to repair it until you are back at a friendly HAB or at least have cleared the area
- Ask other SLs to make a repair station so you don't have to go back to main

[Back to top](#squad-field-manual)


************************************************************************
# Helicopter

- For the love of god load up Jensen's Range again and practice taking off, landing, and flying helicopters. Do it fast and quickly, get good at it, THEN FLY IN AN ACTUAL GAME.
- Name your squad HELI so every SL knows what you're doing.
- Assist with the back cap - On maps like Gorodok, the first couple of back cap points can not only be far from main, but also far from each other. After you drop a squad at the midpoint/get a HAB setup, drop a fireteam or a buddy team at each of the back cap points. Speed of back capping is key in RAAS especially. This frees up your other maneuverer elements to screen for the main force, and gives your team the opportunity to know about that key center point a few seconds or even minutes faster than the other team.
- Be a champion for airlifts and logistics support - A good commander is going to be focused on both logistics, and coordinating the main effort. Don't wait for him to tell you what he/she needs, if you see an opportunity to airlift a squad or set up a HAB let them know what you intend to do and then do it. Your commander will appreciate having another squad keeping a birds eye view of the battle, and it will take that pressure off other squad leaders so they can focus on coordinating their fireteams.
- Gather Intel - The general rule of thumb is that your heli squad can have a max of three people. If that is the case, give both your gunner and your copilot FTL. Between the three of you, you can mark enemy HABS, armor, and troop movements. The drone can only be up in one area for 15 minutes at a time. You can be anywhere.
- Master the J-Hook - Go on the training server and use the admin commands to change the map to whatever you want to practice on. If you can pull off a quick J-Hook turn into a landing in a small area, you will be much harder to hit, and the squad your transporting has a much higher chance of surviving the journey
- CAS - This might be an unpopular opinion, but I do think that there are two situations where the current helicopters can provide some sort of close air support.
  - Taking out enemy logistics trucks - If you spot one, and are confident it's not being escorted by any armor, it is quite possible to pull up alongside and shoot the driver out of a logi truck. We have all been in games where logi trucks are left all over the map, people generally don't take the time to go back and get them when they are lost. If you see an opportunity to paralyze the enemy's flow of supply, take it.
  - Attacking Mortar FOBs - Mortar FOBs are usually very hard for infantry to get to, and can be devastating if manned by a coordinate crew. If you spot one, you have a decent chance of being able to silence those mortars and mark the FOB for an A10. If you're feeling saucy, keep a combat engineer in the bird with you so you can insert him on the FOB once you have killed the mortars.
- Helicopters are great at logistics (transport BPs, ammo, troops) to a central point. From there logis can distribute supplies to (stealth) FOBs.
- Flying 101
  - Collector at 45% = hovering
  - Pitch at 12-15% up/down = max speed without losing altitude (if pitch at 80-90 degrees heli will crash)
- Heli binds
  AxisMappings=(AxisName="MoveAileron",Scale=-1.000000,Key=Left)
  AxisMappings=(AxisName="MoveElevator",Scale=1.000000,Key=Up)
  AxisMappings=(AxisName="MoveAileron",Scale=1.000000,Key=Right)
  AxisMappings=(AxisName="MoveElevator",Scale=-1.000000,Key=Down)

[Back to top](#squad-field-manual)


************************************************************************
# Squad Leading

The Squad Leader is a command and support role whose primary responsibility is to lead his squad of up to 9 players in coordination with other squad leaders to accomplish their team's objectives. It is available to all factions.

[Back to top](#squad-field-manual)


## What is a Squad Leader?
- A Squad Leader is a player who creates a squad and is assigned the Squad Leader role and thus accepts the responsibilities that come with it. The role is the most demanding in the game and requires a firm knowledge of the game mechanics and a willingness to be vocal and to be directly in command of 8 other players. You set the initial mood in the squad from serious and focused to joking and relaxed and determine the amount of BS that you tolerate from your squad members. Don't underestimate this as it has a direct consequence to your own enjoyment of the game.
- Your role is to communicate with other SL's and form a simple plan for the first minutes of the game, consisting of which squad uses what assets and takes care of what responsibilities both initially and throughout the match, like setting up FOBs, capturing each of the neutral flags and contesting the enemy forces.
- Then you communicate the part that is relevant to your squad to them and start the game by getting into action in your designated vehicles.

[Back to top](#squad-field-manual)


## Squad Leader Meta
- How to win a match? - Drain the enemy team's ticket count to zero.
- What's the best way to do that? - Capturing flags yields a net 70 tickets for your team (-20 for the enemy, +50 for your team).
- How to capture a flag? - Members of your team need to control both the offensive and defensive flag.
- What do they need to do that? - HABs!

[Back to top](#squad-field-manual)


## Creating a Squad
- Don't create a squad you don't intend to lead.
- If you want a certain thing out of your squad like "No marksman" or "2 LATS, 2 medics" then make sure to name your squad accordingly so if you don't have two LATs and two medics then you can tell people on useless roles such as autorifleman or marksman to switch off.
- Don’t be afraid to say what kits you want. I like hearing “I need 2 medics and 2 LATs and a rifleman please. No marksman needed for this map sorry."
- Make sure you pick the SL kit. Big must. The squad leader needs this kit to place FOBs and other structures.
- Every squad should have at least a single medic and AT. After your subordinates have chosen their roles, and you see none of them chose AT or/and a Medic then choose who will switch, by name (don't ask for volunteers).
- Keep in mind Fire Support category (AR, LAT, Marksman) has a limited number of slots per squad, you might need to ask your AR or Marksman to switch because others won't be able to). Specialist category (Machine gun, HAT, Engineer) is limited to 2 for the whole team, if you see two HATs in your squad order one of them to switch.
- Make sure every person in your squad has a microphone and uses it. Name your squad MIC REQ always. There is no point to a squad if you can't communicate with each other. It makes your life a billion times easier and your squad much more effective.
- Do mic checks on the way out of spawn once all the comms are cleared. You can also get your fireteam leaders to do them if you're busy with command chat.
- It is possible that a player is a mute and is not able to communicate via voice. Do not kick players just because they don't have a mic. Kick players only if they aren't following orders or if they give you and the team a hard time. Also, leave your text chat on and check if squad members are trying to communicate with you via chat.
- Never have just only one medic on your team.
- Kick troublemakers. If they don't want to play with you, you don't want to play with them.
- Don't be afraid to kick people from the squad. It is your discretion. Of course use your own judgement and give them a few chances. Kicking people who don't listen or are disruptive or defiant will make your life easier. It will also ensure that people aren't questioning your orders excessively.
- Squad composition and positioning - You want to make sure you have a good mix of roles, and not just a bunch of rifleman and a medic, this is how your squad should look: 2 medics, 1 AR gunner, 2 Optics (ACOG), 1 LAT, 1-2 Grenadiers and the rest rifleman You want to make sure you keep the AR gunner at the back and always have him stay in position and give support fire while moving up on the enemy. The enemy will usually think you're still there and be pinned by the AR gunner, you are good to leave a medic with him as well. When you engage the enemy, have LAT and grenadiers pop explosives at the enemy and then move up to flank. When moving, always have your medics in the back and spread out among the squad, you don't want both of them getting taken out at once.

[Back to top](#squad-field-manual)


## Leading a Squad
- The majority of the game will be spent with your squad, consisting of 2 to 9 people depending on what your role is.
- For a basic infantry squad the things you want to consider at all times are:
  - Is my squad being useful = are we doing something that benefits the team as a whole. Safest bet is to play on objectives, but for example flanking is very effective, as long as it's done in a way that doesn't jeopardize the active flags. This means that if you are doing a flank that has turned into a prolonged fight, you may need to cut your losses and fall back if the team is losing the critical objective fight behind you.
  - Does my squad have a relevant spawn point = keep those Rally Points updated and away from the enemy hands. Walking another 10 seconds to place one is a lot better than losing it because an enemy flanked your position and accidentally hit it. Remember FOBs benefit the whole team, but placing one just for you might block others from placing an even more useful one. Communicate with other SLs.
  - Could we be doing more? = Always try to use all your assets to their fullest, this means both vehicles and players. If you're having a more silent period and are happy with your defense perimeter, offer assistance to others. Sharing is caring, this goes for transports, medics, anti-tanks, anything you can spare, someone has a need.
- Keeping a track of these 3 things will have your squad being very proactive and being able to adapt most situations on the fly. Remember that you're not the only one responsible for the whole squad, the other 8 players are still human beings capable of their own decision making. To put it very simply, your job is to get the squad into a spot where you're contesting either an objective or enemy forces/assets, point them into a direction and make sure they have a place to spawn on.
- Name your squad when you make it, something like MIC REQ INFANTRY gets the point across
- You can usually claim a logi truck and go make a FOB at start
- Place your rally before you engage
- Rearm your rally, you only get one at a time
- Enemies can squash your rally if they walk close
- There needs to be attacking and defending squads, pay attention to what other SLs are doing
- Nobody defending? Well the enemies are going to notice that
- Tell someone to go do a logi run if you notice stuff is getting low
- Order people by name instead of asking for volunteers (also applies to other SLs).

[Back to top](#squad-field-manual)


## Leadership Tips
- Tell people what to do, don't ask, this isn't a democracy (that being said you don't have to be a dick about it).
- Manage your team's kits.
- You should have a broad range of kits, and you need 2 medics.
- Tell people to switch kits.
- Don't be afraid to boot people if they aren't listening.
- Give clear orders, and mark them on the map.
- Don't be indecisive, make a decision and follow through.
- Don't micromanage, let your people use their own brains.
- Don't belittle or rage, cool heads are good SLs.
- Ask during the staging phase if anyone's new and go over basics with them

[Back to top](#squad-field-manual)


## Where Should You Go?
- Advance And Secure - AAS - Drop one soldier per flag until you get to one of the frontline objectives. Plan ahead to have enough space for two FOBs. Preferably go for the defensive objective (closer to your main compared to the enemy's). Never rely on other squads to take care of defense without being asked to do it. Either do it yourself or coordinate using the command channel.
- Random Advance And Secure - RAAS - squadlanes.com is going to be your saviour here. Go to one of the possible locations for the middle flag (don't forget about back capping). If you find yourself away from the objectives, relocate as soon as possible. Ask for a Heli transport and leave one guy behind to drive the logi if you are a large distance away.
- Invasion Offence - Flank, go the long way around and make as many FOBs as possible around the first flag. Don't abandon your logi, keep it running or hide it somewhere safe, if friendlies nearby are in danger of being overrun evacuate the logi back to main. It's better to have the logi destroyed than abandoned unless you are low on tickets.
- Invasion Defence - Plan ahead and try to fit at least two FOBs next to the flags. It's crucial you get to the first (closest to enemy) objective swiftly, it's easiest to win by stopping the enemy on the first point. Again, keep your logis safe and accessible, definitely destroy them if recovery is unlikely to succeed.

[Back to top](#squad-field-manual)


## SL Best Practices
- Having good spawns for you team is #1 priority.
- Your main job is spawn management and big-picture coordination with other SLs. Low-level tactical coordination is far less relevant.
- Rally Points - One of the most important jobs you have as squad lead is making sure your squad has a good rally up at all times. Rally points have a cooldown of 2 minutes and require one other friendly within about 3m of you to place. They are free and give 10 spawns on that location. They provide freedom of movement and convenience for your squad. Put them down in buildings, in gullies, bushes etc so you wont get lit up as soon as you spawn. You can disable an enemy rally by getting within close proximity of it. Enemies can do the same so don't place your rally it too close to them.
- Place rallys. Refresh your rallys. Always have a rally up.
- Make sure you resupply your rally point off of rifle bags and ammo crates. Recent updates have made rallies harder to spam. Start placing then further back from the enemy. You can also pick your rally point back up and move it to try a different angle of attack.
- Use your binoculars a lot.
- Every ticket and life counts. If you are unsure of a situation. Keep your squads heads down and only YOU peak so your whole squad does not get wiped by an MG on a ridgeline.
- Use transport time (logis or Helo) to relay INTENT and orders. For example when getting a Helo drop I tell my fire support group to dismount, move for example north west off LZ and set a perimeter with bipods facing west while my AT fireteam helps with shovels on the Hab.
- Don't be afraid to ask your squad for their thoughts on a situation. I often ask if people know a good hidden radio spot or a nice angle of attack. Just make sure when you give a final order, people do not rebel.
- When moving across open ground, keep your fire support back and let the assault push. Then keep bunny hopping.
- Communicate the plan, mark the map, create spawn, put down rallies.
- Do the back caps, play defense, build FOBs/HABs for defense. From there you’ll learn.
- Don't shoot from the HAB/rally. Don't draw attention to our spawn area. In fact, get away from the spawn area. Stop spending your entire game within 20m of the HAB.
- If you are defending a point with your squad, be firm and tell them to stay around the cap point, if they start to run off and not listen to you, either (A) kick them from the squad or (B) ask them why they are running away. If they have a reason such as "I want to place a mine on the road" or "I thought I heard a logi over here so i'm going to check it out" then leave them to their own devices.
- It's your squad. You call the shots and play in whatever way appears most fun / effective to you. If squad members want to play in a different way, they're free to open their own squads. (Asking for tips and being open to suggestions can still be helpful. But don't let others ruin your playtime.) Just don’t be a pushover or else people won’t feel like there’s a leader.
- Always, always, always retain mobility for your squad. Whether that’s working closely with a friendly APC or keeping your squad’s logi/transport nearby at all times, you should always be able to quickly relocate to a different part of the field as the battle develops and your game state changes. Unless you’re fighting in an urban area or on one of the small maps, a squad that walks is a squad that loses more often than not.
- Do not tolerate racism/abusive behavior in your squad. It's (A) not funny, (B) obnoxious, and (C) makes the squad unfriendly. Kick those players right away. Also, report those players to admins.
- A lot of good squad leads make it look easy, and they always seem to know what they're doing. They don't, at least not all the time. You have to be confident with your decisions and sound confident about them. I've found myself in a lot of situations where I have absolutely no idea what to do. Don't freeze up and let your squad split apart. Act like you know what you're doing, even if you don't. You can admit what you did was stupid afterwards. You'll eventually get to the point where you'll always have a backup plan or two in case something doesn't work out.
- Lastly, always have some mode of getting around the map. The worst mistake a lot of SLs make in this game is being off of a relevant point for too long. Learn to be able to disengage and retreat somewhere more important. If you are needed somewhere else, keep a logi or transport nearby, radio some armor or a helicopter for a pickup, and if none of that works and you have the tickets, find some way to die and respawn somewhere relevant.
- Backcap (AAS or RAAS) - Check your map, if you don't see any other squad placing their marker on the first flag, and no one said they are going to backcap then you are the one who will have to do it. Either order one of your guys to grab a scout car, or choose one squad member who will dismount from the logi and capture the flag, while the rest stays with you in the truck.
- That's your most important job as a SL, creating spawn points for your team and squad. The ability to place FOBs and HABs (also RPs) is the most influential tool you have at your disposal.
- The second most important part of your job is to keep your squad fighting close to one of the active objectives. You must be quick to relocate your squad mates when a flag is captured or lost, use your logi, alternatively ask for a Heli or APC transport to give you a ride (check the squad list and use direct radio to SL).
- Incompetent Squad Leaders often get snowballed after losing a struggle for one of the middle flags, all it takes is one enemy squad getting to the next objective before the defenders. The process repeats itself until all of the flags are captured.
- Don't expect other squads to go back defending on their own, you can only count on yourself. Other SLs must be made aware by you that they need to relocate their squads ASAP.
- Check your map constantly, the sooner you realise that a flag will be lost (or that your team will capture one) the sooner you can reposition your squad to newly relevant places of the map (notice that if FOBs are already prepared you can simply tell your squad mates to get shot and respawn)
- SLs from the other team will be doing the same thing, being quicker than them will yield you an advantage.
- Make FOBs and Rallies instead of getting into firefights like some ordinary grunt.
- Constantly analyse the map.
- Be more mobile than the enemy when active objectives shift (a flag is captured).
- Always watch your map - You see it in all the squad play throughs but I constantly see 1 or 2 squad members off in the distance and I have to wrangle them back in. Normally this isn't the case with a well organized squad but we still have new players so I don't put them at fault. But again, pay attention to your map there's more than one reason than just having your bearings. You need to see where your team is so you know whether or not it's a friendly or an enemy. I usually pop my map up every 10 seconds to check where everyone is and I rely on my squad members to be my eyes on the battlefield when we're moving.
- Formation - you do not always want to be bunched up. Squad leaders this is where checking your map is important. Always be aware of how your squad is positioned and formed and correct accordingly. I usually have mine fan out a bit when we are sweeping. You don't want one RPG to take out your whole squad now.
- HELP OTHER SQUADS - You need to be at the ready if there's a squad that needs help. Even if you're moving to the next position you may need to fall back to help another squad out.
- Be the teacher - If you have a new player to a MilSim or even FPS teach them. Don't just shun them and tell them to go do whatever. Be engaging and help them out. Give them tips, teach them how each role works and where they should be at all times. Make sure you give them the experience that keeps them playing and understand this isn't your average FPS. That you can't just lone wolf and that teamwork wins the game.
- Make it fun, but maintain control - At the end of the day, you're playing a game. Play tactically and engage with all members of your squad. Include them and offer suggestions for their roles (AR take that building and take a medic with ya, LAT feel free to go hunt that APC, etc). Talk with your squad, joke with your squad. If someone misses an important LAT shot, don't ridicule, perhaps they're new to the game. Embrace new players and offer help from yourself and other squad mates if they have questions. That being said, keep your squad on task. Continuously monitor what they're doing and if people are running off on their own without communicating to you (and you permitting) as to why, turf them from the squad. Very few scenarios will call for a squad to split up, so have everyone stay relatively close.
- Talk a lot, and realize that you (kinda) don't matter any more. - Your main priority is utilizing your squad to it's best ability. You absolutely must communicate constantly with your squad and other squad leaders. Be polite and follow server rules.
- You will be looking at your map a lot, it's your best friend.

- Mark significant contact on the map for your team to see using your radio. In short, communicate and reinforce that your squad mates communicate to each other (especially locally, in fire-fights). Keep track of your squad's needs (ammo, medics, ranges) and get them what they need.
- Politely ask other squads for assistance when needed. Sometimes you'll get it, sometimes you won't. Provide assistance to other squads when you can. If CAS is in the air and you have a target, reach out and see if they are available to hit an LZ. Report armor and FOBs regardless of other squads locations - this is information they need to know.
  Ask for your squad's opinion sometimes - Be open to reasonable suggestions from your squad (especially when starting out). Maybe you're not familiar with the map and they know a good spot for a FOB. I'll usually ask my squad if they want to attack or defend, if no other squads have made it clear what their intention is yet. If it's not a reasonable suggestion, shut it down.
- Play the objective - Don't be that squad out in the middle of nowhere chasing down a ghost FOB. Stay on cap. Destroy or defend the caches. Deviate from objectives to deal with FOBs on hard intel only, and you may even be able to send a few guys out to hunt it down. Objectives crawling with friendly and no enemy coming? Talk to other squad leaders to confirm they will stay and you'll scout around.
- Drop rally points a fair distance from objective - Pretty self explanatory.
- You're gunna fuck up - You will make bad calls. Your whole squad will get wiped. Look back at what happened and learn from it.

[Back to top](#squad-field-manual)


## Fireteams
- Ask if anyone wants to be fireteam leader, this enables them to place and delete markers on the map, and also build simple structures (such as sandbags) in the FOB radius.
- When making fireteams I usually split my groups into fire support and AT/assault. Direct your fireteams as a unit, but split them when assaulting or defending in order to cover more ground or put the enemy in a crossfire.
- Remember, even though you are splitting your fireteams up, you are still ONE squad. Each fireteam should be able to support each other and work on the same major objective. In the example above, I could ask my alpha and Charlie squad to do a wide flank on the enemy position and catch the enemy push in a crossfire with bravo and squad 5
- If you don't want people to ask for Fireteam lead all the time a good thing to do is to split your squad into the two fireteams then make them give it to one another. Fireteam leaders can give Fireteam lead (FTL) to other members of that fireteam which should make it a lot less stressful.
- Personally I find that assigning fireteam leaders to people who are competent, communicating and giving orders is much more effective than automatically giving the role to a marksman or AT. Again, it makes your life easier if your ftls can round up their fireteams and move on your orders while you are doing other things on the map or command.

[Back to top](#squad-field-manual)


## Building FOBs and HABs (Spawn Points)
- A SL can only place the structure foundation. Another team member with a shovel has to build the structure.
- Do not build a FOB inside a CP. Not only It's impossible for the enemy to miss it, you make a fishbowl FOB where your enemy can use your own walls as cover and shoot you/throw grenades inside your spawn. You are wasting your time building it where you could be useful doing something else and you are bleeding valuable tickets plus the 10 points when the FOB goes down.
- FOB (radio) location - place it either inside a building for protection against artillery and vehicles, or in foliage for stealth.
  HAB location - needs some cover next to it (rotate with arrow keys to fit in tight places). Whatever is close to the HAB is gonna be protected by spawning soldiers, be it the radio or a flag. At the same time enemies attacking one, also attack the other for free.
- HAB (spawn bunker) costs 500 CPs while an ammo box goes for 100, therefore a minimum amount of CPs required for an FOB is 600. Personally, I take an extra 100 for another ammo box away from the HAB. By default I recommend to take enough supplies to make either 2 or 3 FOBs (1200 or 1800 CPs minimum).
- FOBs can be used offensively or defensively, allow for unlimited spawns, need shovels to be removed, allow for building of base parts within 150m of the placed radio, cannot be placed within 300m of another friendly FOB and require friendlies with shovels to place.
- For each FOB you'll need
  - 500 build for HAB
  - 100 build for ammo box
  - Ammo, as much as possible
- You build a FOB by placing a radio using the radial menu T. Then you can use the T menu to build other things.
- In your map menu options (right hand side) turn on FOB Radius Indicators to see the full radius of FOBs, this will let you place them as close to each other as possible.
- You can make a quick FOB with just a HAB and ammo and it will function well depending on where you placed it.
- Fortifying a FOB is often a waste of time because some sapper will just blow up your radio.
- You can wall off the radio with hescos/barrels/etc. to keep a sapper off of it, preferably in an enclosed room with one entrance.
- You can hide your radio in a bush or something, but it makes noise and a sapper can find it.
- You can make a FOB far away and have it be for mortars, with a good crew they can do work.
- Emplacements are a mixed bag
  - TOWs are great against vehicles but really obvious and you can easily be shot out. Also consumes a lot of ammo from the FOB.
  - MGs can do work but again, you can't move and can be easily shot out.
  - Mortars are good, but you need an external calculator to use them effectively. Have logis or helis resupply them, if nobody is doing this you can always help the team by doing it yourself.
- In game marks are not accurate, they are in bad increments for precision ranging.
- Always build more than one FOB. In Squad two is one, and one is zero.
- If you put your FOB into a building make sure the building has more than one exit. Otherwise it will become a deathtrap if the enemy sits in front of the only door and shots anyone that tries to leave the building.
- Make sure in your logi you take 1200 build and 1800 ammo. Doing this will let you make two FOBs because it costs 500 build for a HAB and 100 for an ammo box. After that you can dump 900 ammo on that fob and make another after.
- Make sure that your HABs have multiple exits.
- Don't drop your Logi after the first FOB, use it to continuously construct spawn points when needed.
- A logistics truck is your best friend, and it can build 3 habs while still carrying a decent amount of ammo. Any point you intend to hold ideally needs 3 fobs, 1 on or near cap range and 2 on the flanks or to the rear of the objective. Keeping your guys in the fight when they die (and they will die) is your number one job as SL as you are one of the few people who can place spawns. 90% of flag losses occur because the enemy team has disabled the defending squad's spawn. Don't let that happen to you.
- Furthermore Super FOBs are useless, as are most emplacements except in certain situations. A FOB the enemy knows about is a dead FOB, it's only a matter of time until it's airstriked or proxied. Multiple backup FOBs are infinitely more useful for this very reason.
- As soon as you have your spawn network built, work on getting your truck resupplied as soon as possible and keep it on standby, coordinating with helicopters is a quick way to do this if the team and layer allow for it. Don't get distracted by the firefight in front of you, your squad can deal with the enemy, you need to keep an eye on the bigger picture and make sure the fight they're in is actually useful to the team overall and that they're in a good position to win it.
- The Building Procedure:
  - Choose a single squad mate (make sure he understood you) who will unload a specified amount of supplies (most likely half, start with CPs), and shovel the HAB up.
  - Tell the others (and mark on the map) where they are supposed to go (create defensive perimeter around the FOB or attack enemy positions).
  - Get out of the logi, hold T and select the FOB radio (1 o'clock), place it. When CPs are unloaded, place the HAB and don't forget about the ammo crate. If enemy contact is likely, place a Rally Point 100/200m away from the HAB in case it's overrun, look at the map and order a specific member of your squad to come to you.
- Use the yellow "create FOB marker" to plan your FOB placement. The marker shows the FOB range, which enables you to create 2 FOBs with minimal distance to each other, as well as showing the range in which you will be able to place the HAB in.
- Helicopters are not a great choice for stealth FOBs. They are loud and easy to spot. Better to use a logi to build a stealth FOB.

[Back to top](#squad-field-manual)


## Team Communication
- Mic check at the start of each round. Ask your team if they have a mic.
- Ask if anyone is new to Squad. Help new players with the basics. A little help can go a long way.
- Keep your squad informed as a squad leader. I never have a squad member ask what we are doing. And if you do you are wrong. You have a mic and a squad channel for a reason. Let your squad know the plan so they can be one step ahead of you. Let the other SL's know what you are doing. Keep your Squad members informed as to where you're going and potential contacts and always remind them to keep their eyes open and on the horizons. Your squadmates are your eyes and ears on the battlefield.
- Politeness goes a long way. "Please" and "thank you" should be your primary means of leading the squad. Call people by names to get things done. "Someone" will never dig that HAB and "someone" will never do that logi run. Bob the rifleman will do both, usually gladly. You just have to ask.
- Getting people on board - Being a good squad leader in a pub group with a bunch of people you don't know and getting them to work together and follow orders takes some social/emotional intelligence and maturity. Most people (95%) know this is a team-based/highly communicative game and many are also new to it so they are in-fact SEEKING someone to take charge and give them orders. All you need to do is be cool about giving the orders out. be nice !! but also be confident, understanding,speak with a clear/respectful voice and be willing to listen to others ideas/advice.do this and people will follow you all day without a second thought. the calls you actually make are secondary to the way in-which you deal with dishing out the orders themselves.
- Be clear with your messages:
  - “We’re going to back cap x then push off to y"
  - We’re going to be defending this round"
  - “spawn off y hab. Move south so we can get a rally then we will move on x"
- Ask your squad for advice. “I haven’t played this map as much as the last one. Where should we set up this HAB?"
- Start of the match:
  - Mark where you intend to go with move markers at match start. This is an efficient nonverbal communication.
  - Place move markers on which vics you’re headed towards
  - Naming your squad after the asset you’re claiming may not be required in every server but it’s good etiquette to do
  - Take supplies in increments of 600, it’s cleaner for all of us when we build in the field
- During match:
  - Direct Comms when possible
  - Mark your map and delete your marks. Keep a clean map
  - Don’t just use logi for transport.
  - Recover your vehicles if you lose them
  - Don’t blindly rely on other SLs to defend/set up Fobs
  - Keep command chat relevant and concise.
- Repeat contact reports from other squads to your squad if relevant. Inform other squads of contact if you see something they need to be aware of.
- Have fun and be confident. No one will listen to a squad leader who says: "um so maybe we can do this????? But I don't really know. Ha ha" even if your proposal and orders are absolutely dogshit, say it with confidence and authority and people will listen.
- As above, intent is important. People will follow orders if they know WHY we are doing something. E.g "squad 5 is losing the northwest flank, bravo move wear and support them from the south side of the town." As opposed to "bravo go to the west"
- You want to be on top of your squad, consistently let them know what they're doing. Definitely tell them, as well as other squad leads that you're new, but you're trying to learn. The majority of people respect someone learning to squad lead and will be patient with you. Ask people if they want fireteam lead to help you mark.
- Generalized Commands
  - Move out, Move Up, Advance, Forward
  - Hold Position, Stay put, Establish perimeter
  - Open Fire, Weapons free, Engage, Fire at will
  - Cease Fire, Disengage, Stop firing
  - Retreat, Fall back
  - Go dark (stealth maneuvers, to crouch and stay off radar)
  - Radio Silence
  - Covering, Cover fire, Suppressing Fire

[Back to top](#squad-field-manual)


## Communicating With Other SLs/Commander
- Make sure your team has a commander! And listen to their orders. They are looking at the map and are usually Squad vets who know what needs to happen, when it needs to be done by, and by who. If he/she asks you to build a fob on a point two points away from the active ones, it means he thinks our defense is not sustainable and is preparing to fall back to a defensible position.
- Make sure you communicate with command and other squad leaders. Use your direct comms (num pad) as much as possible, but relay important information to all squads. For example I will relay the location of an enemy tank to all squads, as that can help anti tank infantry to engage and helicopter pilots to stay away. However, I will direct comm our tank squad to tell them what direction the gun is facing, or how many crew members are alive etc. So they can engage effectively. Another example is when organizing an assault. You can direct comms another infantry squad and get them to attack from the north while you sneak into the cap and FOB from the south.
- Tell other SLs what your plan is.
- In regards to the whole team, what you want to do as a basic, good SL, is to actively participate in the first minute plan of action. Take whatever assets you feel like using and using them to the best of your ability. In most cases this means, you'll assign a couple people as drivers/gunners where necessary and let them do their thing, assuming they have some experience with the asset and can be useful.
- The primary things you need to communicate from one SL to another are FOB and objective related. Building / losing a FOB and capturing / losing an objective are the most crucial, game-changing info you HAVE TO share. This allows for others to plan and move accordingly and make sure the whole team remains in the fight.
- Keep command chat clear of unnecessary information. This comes with practice.

[Back to top](#squad-field-manual)


## Squad Tactics
- Know when to disengage from objectives and do it quickly
- Order players to suicide-rush the enemy and respawn to quickly shift your squad to alternative positions around the map
- Know when to cancel a futile attack (e.g. lack of vehicle support in attacking very open objectives)
- Send and/or allow people that know what they're doing to flank, they will almost always kick over enemy Rally Points. Every enemy objective falls as soon as you take out their primary FOB.
- Flank, flank, flank - Never run at the enemy head on that's stupid. You need to learn how to flank and use the environment as your cover. See that hill, use the other side as cover, those bushes and crops, crouch all the way. You may think it takes a long time but I've helped a lot of squads by having my squad flank an enemy position. Flanking is the best tactic to use in most situations, you need to be one step ahead of the enemy and make sure that you have a rough idea where they are at. This is the time when you want to tell your squad to hold fire to not give away your position.
- Keep your cool - As a squad leader you need to keep your head straight. You're going to have bullets, RPGs, grenades all coming at you and sometimes from all directions. You need to constantly be thinking of the best avenues of attack and defense, where to place your squad members, you cannot freeze. Once you freeze and stop moving and stop organizing your squad in a firefight, you're done for. You need to keep the momentum up with your squad as well. Make sure you keep barking out those orders, where you want them to shoot, to move, to cover. As soon as you freeze up the enemy squad has already won.
- Don't let yourself be pinned - It's fine to sit in a position for a little and take some shots off but this is why flanking and moving is important. You don't want a squad to zero in on your position and not give you an avenue to get out. Make sure you keep moving, even if under fire.
- Break contact with the enemy (aka stop fighting them) if your squad is needed on another objective. Do not get stuck in one pointless fight. If you need to spawn shift somewhere else, have your team rush the enemies and tell them where they should spawn next.

[Back to top](#squad-field-manual)


### Offensive Squad Tactics
- Being that this game and others like it (see arma) base the game play mechanics around real world gunfight mechanics its unsurprising that some real world gunfight tactics can be used against your foe with good effect. When using various formations it's important to consider the various needs of each formation. terrain, dispersion and concentration. you want to have as much dispersion as you can use without losing concentration. you don't want to be clumped up so that one grenade or full auto burst kills a bunch of your guys but you have to consolidate your guys so that you can overwhelm your opponents 1 or 2 at a time. to clarify, you want to fight them 5v2 then another 5v2 then kill the last guy. not 5v5 in one big engagement. Check youtube for "Tactical Formations'' or check out https://youtu.be/MuL88_KYcrY
  - LeapFrogging Formation - Split your squad into 2 fireteams. While team A moves towards the objective, team B covers team A. Once A stops (not too far away) they start to cover team B until team B overtakes team A and finds another good location to cover team A.
  - Momentum - I see a lot of squads stop every time they make contact. A lot of the time if you are trying to get to an objective to defend or capture it's best to bypass, or smoke and push through. The best SL I had are always playing the objectives aggressively.
  - Flanking - One of the most effective, intuitive and generally understood tactics in Squad is flanking. You should initiate a flanking move when an enemy squad reveals their location. This usually allows you and at least a few men the freedom of movement to execute a successful flank. However, it is highly beneficial to maintain the element of surprise! Tell your squad you are going in quiet and not to shoot unless you absolutely have to. Use a hill or building to conceal your advance and get as many guns pointing in the right direction and from the right place as possible before anyone shoots. This will maximise the effectiveness of the first volley and should be devastating to the enemy squad, allowing you to then push forward and take out their rally or FOB.
  - Support fire - A slightly more difficult aspect of squad leading is to effectively utilise your MGs, Snipers and RPG's. I've found the best way to do this is by splitting up your squad into 2 separate fireteams. Tell your support team (something like a Sniper, MG and RPG) up on a hill that overlooks your other fireteam and their approach. The important part here is getting the 2 separate fireteams talking to each other and communicating what they need and what they see.
  - Scouting - When advancing, it's handy to send one or 2 guys out in front to check for ambushes and contact. Maybe the one guy dies but you can put a rally down, get him back and now you have a full squad and knowledge of an imminent ambush/enemy position etc. The alternative is a full squad surprised by an ambush which is far worse.
  - Stacking - (not related to clan stacking where one clan or group joins a team to completely dominate the other.) Stacking is the tight formation a squad gets in before breaching a door or wall and extremely effective in SQUAD as a way to break an opponent's defences on an OBJ or FOB which is a very common occurrence in this game. If you go into a well defended compound one at a time you'll find it's basically the opposite of what i mentioned previously about fighting them 5v2 then 5v2 etc and you end up feeding them 1 easy kill at a time. instead, order your unit to stack up on you near to an entry point but in good cover. Put a rally down, then tell your squaddies with grenades to prep a frag and get ready to toss it over the walls. toss all your frags and go in HARD and FAST this is the time to yell GO GO GO ! into your mic and jazz up your squad with a bit of adrenaline. go in right behind the guy in front of you and DON'T BLOCK THE ENTRANCE. Everyone goes in guns blazing and finds a good point of dominance in the compound which they can hold and if all goes well, you take control of the compound and kill a bunch of baddies in the process. if it fails, spawn on the rally and get back in there or wait for another push, depending on how the situation looks.

[Back to top](#squad-field-manual)


### Defensive Squad Tactics
- So you're at a FOB or objective and you need to defend it. The most common thing I see in pub games is that the whole squad or a large portion of it stays physically ON the point or in the building they're defending. This is a mistake. You want to stop them from getting to the compound instead of letting them get to the compound and then trying to stop them from getting in the building. By all being in the same building you are limiting your observation of the surrounding area/enemy maneuvers and you make yourselves vulnerable to a possible frag through the window or door which usually ends badly. Yes, you need to keep a few guys on the point to (A) check on the status of the point (if it's being capped etc) and (B) to obstruct and counter enemy movement through the capture area. For the rest of your guys you want to tell them to pick a spot with good cover and a vision of the surrounding area. The next part is hard and requires reliable squad members but try and get your squadmates to pick a direction/alleyway/area to cover and take responsibility for. When done correctly this allows you to focus your observations better and cover any blind spots more effectively. Another way to do it is to have a few guys on point and have everyone else orbiting the position as a solid group. Search for "Conducting Defensive Operations'' or check this video https://www.youtube.com/watch?v=AiNqUgq1Wfc&feature=youtu.be
  - It is often helpful to designate a couple guys for rear security, I find that medics are best suited for this role as they tend to then stay closer to the squad but generally out of harm's way.
  - Ambushes - If you know the enemy is coming towards you, divide into 2 teams, one team spreads out in front will be the team that engages the enemy when they approach. The 2nd team waits in the flank for contact and moves in to engage the flanks of the enemy when contact on the 1st team is made. This is called an L shaped ambush. A good video that covers this can be seen here https://www.youtube.com/watch?v=BpYbT4orFfs&
- Communicate - As SL you can chat to other SL's with the default binding 'G'. Do this at the start of the game to figure out what squad is capping what so as to avoid wasting precious time getting to the front. It's also important to communicate progress and developments on obj's. i.e. let the other squads know if you're about to get overrun or conversely if you are attacking and need backup to take the OBJ.
  - You need to talk all the time as SL. Your squad relies on you to get the mic ball rolling, you'll find that if you're quiet and don't talk much, your team will usually be the same. So be talkative, have fun, don't be super serious without also having banter in pubs, everyone is there to have fun but call out any shots you hear when things are quiet and act appropriately. You should also react when a squad-mate says he sees or hears something, don't just brush it off.
- It's important to defend positions as well as attack. If the enemy takes your defence point you can no longer capture the point in front of it and this can throw a major spanner in the works for your team. If this happens, get back to the next defence point IMMEDIATELY or else risk chasing the other team all the way back to your base which is no fun!

[Back to top](#squad-field-manual)


## Guerilla/Recon Squad
- Information is an extremely powerful weapon. Knowing where enemy FOBs are, knowing their enemy vehicles are, knowing about an incoming flanking squad can turn a game in your favor. This allows your team to distribute its forces more effectively and respond to threats faster.
- If you're doing recon only you should probably never have more than 2 players max in (R)AAS due to the manpower limits. Whoever is doing recon, make sure they have binos, a rifle with at least 4x optic and can mark targets (either a squad lead or fireteam lead).
- A guerilla/recon squad could be a 4-man squad mounted in a light vehicle (HMMWV, Techie) or on foot (sometimes with transport). SL, Medic, Scoped Rifleman, LAT or Engineer. Operate behind enemy lines, disrupt enemy supply lines, ambush vehicles, and take out FOBs, while relaying additional information on enemy movement to the rest of the squad. This can be extremely effective if you know what you're doing. Besides gathering intelligence, focus on taking out light (logistics) vehicles and FOBs.
- If you focus on gathering intelligence, you can do it as one man squad in a light vehicle as well.
- Make sure to lock your squad if you're running a guerilla/recon team with 1-4 players max.
- Be in close contact with all SLs/Commander but also provide more detailed information to your armor squad to help them hunt enemy tanks you have your eyes on.

[Back to top](#squad-field-manual)


### Strategy To Win Games
- As a SL lead a defensive squad which will lead to many more wins because we have plenty of offensive-minded players, but not enough people who are okay with defending and slowly fighting back an enemy push while the rest of our team pushes up or flanks.
- Be aware of what's going on in the big picture or around you (ie enemy players capping a flag behind them).
- Slow it down and take a defensive position first to repel before pushing outwards at the right times.
- Squad is math: Setting a defence and attack element divides the numbers of the enemy. By that, they cannot focus on one point but two. As you are divided in your own team (attack and defence) it will be about who has the better FOBs (ammo, setup, position-wise) and options for supply.
- Another way to say it is that taking the points does not give you map control. Having map control gets you the points.
- Defence is really fun and you can get easier kills too since you are in cover, still and watching, whereas the enemy has to run to you, making themselves easier to spot in the process. Well, as long as your entire squad doesn't just sit in a single spot and wait to be flanked and killed.

[Back to top](#squad-field-manual)


## How To Use Helicopters
- Communicate with helicopter pilots (direct comms). In the beginning of the match you should be using helis to move an attack or defend fob up the map FAST. Don't just use them for logi runs. A good pilot and good squad leader communication can easily win the game. When asking for a pickup, find a good spot based on the pilots skill and create a perimeter. Pop smoke to help the pilot land and provide cover when you are mounting. Mount up fast and make sure your squad is ready to get on the moment the Helo lands.
- Communicate in command chat that you need a helo and check the ETA with your pilot!
- Gather your Squad before calling Pilot in.
- Control the LZ and make sure there are no enemies close by. Enemy infantry is a HOT-Zone. Enemy BTR is a DEAD Zone!
- Make sure no one gets on the Helicopter before you are gathered and have given the order to board.
- Landing and boarding should be one process and shouldn't take longer than a few seconds!
- Use one colored smoke grenade shortly before the pilot arrives. It's easier to locate you. If you got enemy infantry around and still go for the evac, mark the enemy with red smoke (if you got a grenadier) and let the others throw smoke towards the enemy (between LZ and enemy). This way door gunners can orientate better and can suppress them while your LZ is somewhat covered.
- Make sure you pick a landing zone that's suitable to land. We can't pick you up inside the deepest woods. The easier to reach the LZ the faster the evac. The faster, the safer!

[Back to top](#squad-field-manual)


## Staying Sane
- Kick troublemakers. No one is entitled to be in your squad and you're there to enjoy the game like anyone else.
- Politeness goes a long way. Some jobs are plain boring, but getting a simple: “Thank you" as recognition is huge.
- Ask for opinions or suggestions. Your squad is there stuck with you anyway and someone will be happy to help. Squad leading is hard work. Enjoy yourself with a good beer or 6 or your beverage of choice.
- You determine the environment in your squad and the people that you want to lead. Don't let anyone walk over you, if you don't like the way someone acts, just get rid of them. No one is entitled to be in your squad or anyone else's if they're taking away from your enjoyment of the game as a SL. When you pick SL, you pick a certain amount of responsibility and gain the advantage that you can choose exactly who you play with in your squad. Use it. 7 people communicating and having a good time is a lot better than 9 people, out of which 2 are off doing their own thing, one is talking over SL and you're just getting pissed off at the game. You deserve to enjoy the game just like anyone else and dealing with horse shit behavior is not something I recommend doing too much.
- When things go sour and you get pushed back constantly and can't seem to get your guys to win a single fight... It's not your fault in many cases, if you condense Squad Leading to its core, you're a glorified Rally Point dispenser. Your job is to get your squad to a more or less tactically advantageous spot, point your squad in a direction and then as they're grown up goddamn men they can make micro-level decisions by themselves. And if you're keeping your boys in a relevant area and the killing is just not happening, then it's too bad, but you're only one man and need some help from the squad to make it into an effective force. There's 8 other guys/girls in there and you're all just as responsible. Doesn't matter if you point the tip of the spear to the heart of the beast if the tip is made of marshmallows.
- Make them flank and call out important targets and positions where you need them to be (in very general terms). That's mostly enough. Micromanagement yields no benefits and is mostly annoying to both of you. They should know better where to be in a firefight. Only time you should call out individual members is when you need your vehicle for support somewhere or when you need a logi run or some shovelling needs to be done. Other than that, it's not worth the hassle - you should focus on keeping the morale up for the whole squad instead. Focus on the good things.
- When the blame game starts among the SLs or within the squad, I just have to say: "Settle down guys, we actually did OK this time, the other team is simply better"
- Bear in mind most players are not military. Give acknowledgement to your team and other players when they do what you ask. Something as simple as "cheers mate" or "thanks" goes a long way to building loyalty fast.
- Also when you first get into a match, already have a rough plan in mind and be ready to lay it out the moment your squad is full. Then everyone knows you are competent and will stick close to you rather than lone wolfing.
- It takes confidence and a decent amount of leadership ability but that is a learned skill and squad is great for it. Listen to your teammates and help them out as best you can, you are there to direct and support them, not just bark orders.
- Last but not least, no matter how frustrating it gets, always keep your cool. When you are calm, so is your squad and a calm squad will think a lot clearer than one that is getting angry.
- Have a drink.
- A decent squad leader just makes sure the basics get done well. Get the FOB/HAB down, keep the rally up, give the squad opportunities to get the fighting done.
- Whenever you get a squad of finely chopped jello just piggyback off another squad. Because when individual manpower lacks, raw numbers compensates. "We're following and assisting squad 1" Because, 19 people is way scarier than 4 guys who know what they're doing. And I'm all about that intimidation factor of making some Auto Rifleman realize his 50 round belt isn't enough and screams into the mic "full enemy team to the west" because let's be honest, when's the last time a rifleman ever gave a proper enemy force count. Make it true for once ;)
- You can only do so much. Don't stress too much if a game goes to shit. You're the arm that guides the spear. Sometimes the spear tip (squad members) is not made of steel. Sometimes it's wet noodles. And at that point when every teammate goes 0/10 your leadership is irrelevant. First and foremost Squad is a shooting game. If no one in the squad is shooting enemies, nothing gets done.

[Back to top](#squad-field-manual)


************************************************************************
# Commander

- The Commander's first objective is to lead their team and manage other Squad Leaders.
- Their second objective is to lead a squad of their own as a normal Squad Leader. The role is available to all factions, however it differs slightly for each.
- The Commander role is the only role that can exclusively deploy Strategic or Tactical Support Actions for reconnaissance or firepower purposes.
- The Commander is one of the most important roles in Squad as the position holds power over every other player in the game. Players should follow their Squad Lead's orders and Squad Leads should follow the Commander's orders. Squad Leads who wish to talk directly to their command can do so by hitting Num 0.
- Commanders are chosen by a vote; in order to nominate yourself you must have 2 squad members and there must be at least 3 squads created. After one or more Squad Leaders nominate themselves, every Squad Leader gets a chance to vote for their preferred candidate. Upon being elected Commander, the Commander-elect's squad name will change to: "CMD SQUAD". Commanders can be re-elected after 300 seconds (five minutes). If a new Commander is elected, the cool downs are reset.
- Commander's deaths are worth 2 tickets instead of the usual 1.
- The Commander is not available in the Skirmish game mode, Logar and Sumari due to their small size, which renders the strategic actions available to the Commander obsolete and at the same time overpowered, due to the risk of wiping out the majority of forces on either side.
- Delivering a weaponized tactical support payload against the enemy is a 4 step process.
  - A Squad Leader (possibly the Commander themselves) marks a location on the map using the radial menu to Request Tactical Support from the Commander. The request mark specifies a radius rather than an exact location.
  - The Commander has 1 minute to Accept or Deny the request. If neither is chosen, the request will expire.
  - If accepted, the timer refreshes, and the Commander has 1 minute to Accept or Deny their decision from Step 2. Essentially this acts as a "double-check" or a "2-step verification" to ensure a mistake wasn't made.
  - Finally, if accepted again (the "double-check" or "2-step verification" passed) then the Commander can choose a Tactical Support Action and specify the details of the payload (its direction, how large the radius is, etc.)
- TACTICAL SUPPORT PAYLOADS FOR ANY FACTION ARE NOT 100% ACCURATE, SO BE WARY OF FRIENDLY FIRE!
- Keep in mind that just because others, or perhaps you yourself are outside of the designated target area for a strike does not mean you are at all safe in the slightest. All offensive strategic Commander actions have a large splash damage radius, which can wound or incapacitate friendly infantry a large distance away.
- A Commander can keep their squad size very small to primarily focus on keeping the rest of the team in the loop on enemy intel markings, planning new FOB build locations, coordinating air assault drop points, using the UAV to mark and scout enemy locations, as well as providing devastating fire support through artillery and airstrikes.
- The Commander role could be used by a Squad Leader that still has a full squad fighting in offensive or defensive situations. This “frontlines” Commander would still be able to help augment the team through the use of his Commander actions and keeping each squad on task, but with a more direct engagement in the battle.
- Another way to utilize the Commander role could be used by a Squad Leader focused on Logistics and Building rear defensive locations with a strong emphasis on intel gathering and reconnaissance.
- If you (the commander) have a message to one SL, transmit it directly, and for the love of everything sacred say "Four, this is one" and wait for the  green light to continue. Sometimes I (SL) can talk, sometimes you're talking over my poor scout party that's trying to give good intel for the fourth time and has to repeat it yet again, clogging up the frequency further.

[Back to top](#squad-field-manual)


************************************************************************
# Abbreviations, Lingo

- .50 Cal - In reference to the .50 Cal HMG
- 10-4 - Copy or Yes, I understand your message
- 1HK - One Hit Kill
- 203s - M203 grenade launcher is a single-shot 40mm under-barrel grenade launcher designed to attach to a rifle.
- 2-to-1 advantage - having twice the manpower than the enemy (e.g. on an objective)
- 2/ic - Second in command
- 40 Mike-Mike - An M203 grenade launcher, usually mounted under an M-16 or similar weapon.
- AA - anti aircraft
- AAS - Advance and Secure
- ACC - Accuracy
- ACOG - Advanced Combat Optical Gunsight - the official medium-distance engagement optic of the Marine Corps and U.S. Special Operations Forces
- ADS - Aim down sights (on your rifle)
- Affirm or Affirmative - Yes
- AKA - Also known as
- Ammo - Ammunition
- AFAIK - As Far As I Know
- AFAP - As fast as possible
- AH - Attack Helicopter
- AOR - Area of responsibility
- APC - Armoured Personnel Carrier - Small cannon/HMG, fast, on wheels. Has usually enough space inside for crew + one full squad.
- AR - Automatic Rifleman - one man can carry it, not as heavy as a LMG, think SAW by the US forces
- AR - Assault Rifle
- Area is hot - Can be replaced with a specific area of the map. A section of the map is filled with enemies; friendlies are most likely engaged with the enemy and an intense firefight is ensuing.
- ASAP - As soon as possible
- Asked as a Command - Affirm my last order in which you would repeat the last order you got from your SL to your SL
- As you were - Return to your previous task or posture
- AT - Anti-Tank
- AWOL - Absent Without Official Leave; leaving post without permission
- Azimuth - The degree in which the mortar is facing. If thinking North as 0 degrees, and the enemy is direct South of the mortar emplacement, you would point the mortar 180 degrees from North with an azimuth of 180 degrees.
- Azimuth Check - Ensuring that you are on the correct path or that the task is being done according to procedure

- Bad Splash - Bad Mortar/Rocket Rounds, expect further orders - Means the rounds weren't on target, so expect new bearings to clock into the mortar. Can also mean the rounds hit friendlies. New bearings are usually said right after this phrase. In reference when mortars or other artillery are used on a current position, then squads are supposed to assault said position. Once the mortar rounds splash, then your men are supposed to assault the location.
- Back Cap - Staying behind on an already captured flag (defense flag) while the rest of the team is attacking the next offensive flag. You make sure that the defense flag is not neutralized by the enemy.
- Bad nade - grenade landed too close to friendlies
- Bang-bang - An Army term describing a pistol or rifle. Also, sometimes referred to as pew pew.
- Battery and Assault - Wait for the rounds to splash, then attack.
- BAR - Bolt Action Rifle (a.k.a. Sniper Rifle)
- Barrage and Assault - An assault preceded by an Offensive Barrage can either be done with a Standing (static) or Creeping (moving) Barrage that either targets a defensive position or moves ahead of advancing troops in order to suppress OPFOR in a given area (like clearing through a patch of forest).
- BB - Bye bye
- BCP - Base Control Point (the main base the game starts at)
- Binos - Binoculars
- Bird - Helicopter
- Black - When discussing amounts of something, it means you are almost out
- Black on Ammo - Fully out of ammo/mags
- Blueberries - Random player on your team but not in your squad
- Brad - M2 Bradley Armored Personnel Carrier (APC)
- Bravo Zulu - Good Job
- BRDM - The BRDM-2 is an amphibious armoured patrol car used by Russia and the former Soviet Union. Also known as BTR-40PB, BTR-40P-2 and GAZ 41-08.
- BS - Bullshit
- BTR - The BTR-80 ("Armoured Transporter") is an 8x8 wheeled amphibious armoured personnel carrier (APC) designed in the USSR

- Cap/capped - Capture flags, captured flags
- Capping - Capturing
- Capped - Captured
- CAF - Canadian Armed Forces
- CAS - Close Air Support - defined as air action such as air strikes by fixed or rotary-winged aircraft against hostile targets that are in proximity to friendly forces.
- CE - Combat Engineer
- Charlie Mike - Continue Mission; continue with your task
- Check your Six - Check behind you
- Clear to Engage? - Am I allowed to attack?
- Clear to Engage! - You are allowed to attack!
- Clip(s) - special way to reload a gun involving a literal clip (SKS has this)
- Charlie Foxtrot - Commonly used expression utilizing the military alphabet to stand for clusterfuck.
- Coax - Nearly all main battle tanks and most infantry fighting vehicles have a coaxial machine gun mounted to fire along a parallel axis to the main gun. Coaxial weapons are usually aimed by use of the main gun control. It is usually used to engage infantry or other "soft" targets where use of shots from the main gun would be dangerous, ineffective or wasteful.
- Commander - Commanding SL
- CN - China
- CONOPS - Concept of Operations
- Copy (that) - Information received
- Contact - callout to make once you spot an enemy, e.g. in local com say "Contact 2-30"
- Contact Wait Out - "Contact, wait out" is a term military personnel use over the radio to report enemy sightings/attacks. "Contact" means that the enemy has been identified or that you have already been attacked. "wait" means that you have no time to explain the situation right now. "out" means that you are about to end transmission and will call back later.
- COP - Small base in a combat area, combat outpost
- CP - Control Point or flag
- CPs - Construction points
- CQ - Conquest
- CQC - Close quarters combat
- CQB - Close quarters battle
- CROWS - Common Remotely Operated Weapon Station. In reference to the MG that is mounted on some fire support vehicles, it is remotely operated within the vehicle hull and doesn’t require a man to manually control it directly. In most common reference to the mounted HMG on fire support vehicles that can shred men and light armor, and can take down medium armor.
- C-Wire - Razor Wire

- Danger Close - CAS or artillery support within 600m of friendlies
- Dismount - Leave the vehicle
- DMR - Designated Marksman Rifle
- DoD - Dome of Defense (around main base)
- Double neutral/white - A situation when a defensive flag is neutralised before the offensive one gets fully captured. Only three teammates are required to recapture such a flag, no matter how many enemies are inside the cap zone.
- Drive On - To keep going
- Dropped 2 - Killed 2 enemy soldiers - Said immediately after you kill the said soldiers
- Due North - Direct North - North can be replaced with North, South, East, or West, or the North East, NW, SE, or SW. Can mean to go precisely North, South, or etc. Can mean enemies are moving precisely North, South, or etc.

- EAC - Enhanced Armament Carrier (e.g. HMMWV)
- Egress - Exit
- Empty the (full) Load - Reference to mortar support means, to shoot off all the rockets or mortars in the current mag
- Entrenching tool - shovel - needed to build structures
- ETA - Estimated Time of Arrival
- Exfil - Extraction

- Faction - Team - One of the 2 groups fighting each other
- Fast Mover - Slang for a Jet Fighter. Aptly named due to the rapidity of a Jet Fighter's movement.
- Fire for effect - the final command used in a full fire order after a ranging shot(s) has found the mark.
- Fitty - Slang for an M2 .50 caliber machine gun.
- Flag - Control Point
- FM - Field Manual
- FO - Forward Observer. Someone who can see the mortar impacts and make adjustments to their impact.
- FOB - Forward Operating Base (it's the spot where you drop the radio, a HAB and an ammo box)
- FOV - Field of view
- FOW - Fog of war - not yet visible areas on the map
- FPS - Frames Per Second
- FRAG Round - "Fragmentation Round - refers specifically to the fragmentation round used to take on infantry
- Frags - Fragmentation Grenades
- Free to Engage - Allowed to attack on contact with the enemy
- FTL - Fireteam Lead (a squad can be divided into two fireteams)
- FUBAR - Fuck Up Beyond All Recognition (or Repair)
- Fuck 'Em Up! - Clear to engage but better
- full cap - flag that has been successfully captured (takes 2 minutes)

- G2G - Got to go
- GG - Good Game
- GJ - Good job
- GL - Grenade Launcher
- GL - Good luck
- GLHF - Good Luck, Have Fun
- Good Splash - Good Mortar/Rocket Rounds. Means the mortar rounds were on target and inflicted enemy damage.
- GPMG - General Purpose Machine Gun (like PKP, M240, M60...)
- Grunt - infantryman or foot soldier
- GTL - Gun Target Line: The azimuth in degrees from the mortars to the target.
- Guardian Angel - refers to the squad member who hangs back and eyes the squad's movement from a high position, usually a sniper or scout
- Gun - Term for a mortar or artillery piece. Must never be used within the military to describe a pistol or rifle.
- Gunner - A servicemember who operates a crew-served weapon, such as a piece of artillery or ship's cannon.

- HAB - Hesco Accommodation Bunker - Spawn point
- Hang Fire - Hold fire until told to do so
- HAT - Heavy Anti-Tank
- HBAR - Heavy Barrel
- HC - Hardcore
- HE - High Explosive, refers to ammo types
- HEAT Round - "High Explosive Anti-Tank Round" - refers specifically to the light anti-tank round that can take on most lightly armored vehicles and damage heavier ones
- HEDP - high-explosive, dual-purpose M430 grenade launcher cartridge
- Helo - Helicopter
- HF - Have fun
- HMG - Heavy Machine Gun .50 Cal
- Hold Fire - Stop firing
- Hold spawn - if you're dead don't spawn right away. Instead, wait for a new spawn to show up. Ask you SL where you should spawn.
- Hooah - Phonetic spelling of the military acronym HUA, which stands for "Heard Understood Acknowledged." Originally used by the British in the late 1800's in Afghanistan. More recently adopted by the United States Army to indicate an affirmative or a pleased response.
- HP - Health Point
- HMMWV - High-Mobility Multipurpose Wheeled Vehicle (also: Humvee)

- I have visual - Means you have eyes on the current objective or a specific object.
- I’m Out - Out of ammo in current magazine
- I want 360 security - Make a perimeter
- I want 360 security on the roof - Give me eyes on the roof, I want views on all angles
- IDF - Indirect fire system, e.g. mortar, artillery
- IED - Improvised Explosive Device
- IED Bikes - IEDs placed on dirt bikes
- IFV - Infantry Fighting Vehicle - Medium cannon (25/30 mm), ATGM launcher, tracks, engine in the front. Has enough space inside for crew + one full squad
- IMO - In my opinion
- INS - Insurgent forces, designed after insurgent forces you see in the middle east
- INS - Insurgency game mode

- K/D - Kills per Death
- KIA - Killed in Action
- Kit - The role you're playing. For example: Rifleman, Medic, Squad Leader, Pilot, etc. Many kits have unique weapons.
- Klicks - Kilometers
- KOC - Kill or Capture
- Kornet - 9M133 Kornet is a modern Russian man-portable anti-tank guided missile intended for use against main battle tanks
- KPM - Kills Per Minute

- LAT - Light Anti-Tank
- LAW - M72-LAW, US-specific LAT weapon
- Leapfrogging - One fireteam advances while the other fireteam covers them
- LEL - Laughing extra loud, Sarcastic lol
- Lima Charlie - Loud and Clear (as a response when someone asks on the radio how you read them)
- Lima Lima Mike Foxtrot - Lost Like a Motherfucker
- LMG - Light Machine Gun - one man can carry it; think M240B and PKP, but not a SAW
- Logi - Logistics Truck
- LOL - Lots of laugh/laugh out loud

- M240 Bravo - refers to the FN M240B LMG
- Made Contact - Means you're either engaging the enemy or your on the site of your team's current objective
- Mag(s) - refers to the magazine that holds bullets, mortars, or rockets
- Main - Your team's main spawn point. You spawn with full ammo/supplies. Good place to switch kits if needed.
- MBT - Main Battle Tank - Big gun, loud, on tracks
- Med(s) - Medical Supplies or Medkit
- Men on me - All men of the squad to their SL. Can be shortened to On me.
- Mid cap - that flag in the middle of the map
- MFP - Mortar Firing Point
- Mike Golf - Master Gunner
- Mils - Milliradian (thousandth of a radian), military unit of measurement for US mortars, describes elevation, There are 2Pi Radians in a circle, being 2*3.14, or 6.283 Radians. Multiply that by 1000mils, and you get 6283mils, with roughly 18mils equaling a degree. Most militaries would simplify this number to 6000mils or 6400mils. Simply speaking, a mil is a finer degree than a typical degree, which allows for more precise mortar drops. Using spotters who can give you rough estimates of distance from you to the target, mils can be translated from meters via the Range to Mils table in the mortar GUI.
- Mike(s) - Minute(s) or Millimeter(s) or M in the NATO Phonetic Alphabet
- MG - Machine Gun(er) - an umbrella term for a gun with the following characteristics; can refer to any MG, LMG, or HMG you may encounter such as the SAW, M240B, PKP, .50 Cal, etc. Usually belt fed, but their most notable ability is on-the-move fire support for a squad. Usually sport a bi-pod.
- Moving Like Pond Water - Moving so slowly that a unique term is required to describe it.
- MP - Multi-Player
- MRAP - Mine-Resistant Ambush Protected (vehicle)
- MTLB - a Soviet multi-purpose fully amphibious auxiliary armored tracked vehicle
- MVP - Most Valuable player

- Nades - Fragmentation Grenades or Rifle Grenades
- Need Backup - Need men on my location. Used when enemy soldiers have overrun a squad or specific location.
- Neutral flag - A flag that has not yet been captured by either faction.

- OBJ - Objective - Usually the point you're trying to capture or defend
- OHK - One Hit Kill
- On the money - On target
- OP - Overpowered
- OP - Original post/poster
- OPFOR - Opposing Force, the enemy
- Oscar Mike - On the Move
- Out - Transmission over
- Over - Waiting for response
- OWI - Offworld Industries
- Oxygen Thief - A biting piece of slang for someone who's useless or talks too much.

- Peek - The act of checking a doorway/choke where you're in plain sight of the other team. Often used in a cautionary way, it's how players get sniped/killed before a team fight even starts. (Ex. “Don’t peek”, “Stop peeking” and “No peek”)
- Pick - The act of achieving a quick kill
- PIC - Pilot in Command
- PDW - Personal Defence Weapon
- Pink Mist - A distinct effect created by certain types of gunshot wounds.
- PKP - refers to the PKP Pecheneg LMG
- Platoon - a military unit typically composed of two or more squads, sections, or patrols
- Point - The objective
- Pop Smoke - Throw smoke grenades to SL’s desired target
- Position - Where you're standing or where you're supposed to be standing
- PR - Project Reality mod for Battlefield 2 (Squad's predecessor)
- Projectile - Refers to a weapon type that has a travel time
- Push - Taking aggressive action as a team to move the other team off of a capture point, by eliminating them or driving them off
- PTFO - Play The Fucking Objective
- PTO - Play The Objective
- PTT - Push to talk. The key that activates your mic.
- Pub game - A game that's being played on a public server.
- Push defense - move to a defense flag to prevent enemies from neutralizing it
- Push mid - attack the middle flag
- Push offense - move to the next attack flag and capture it

- QRF - Quick Reaction Force. Squad under the direct command of the Commander. Commander is the only one authorized to direct this unit unless he sheds command of the squad to other officers. Meant to rapidly respond to developing situations. Meant to quickly backup pinned down squads and get them out of a dire situation. The desired vehicle would be a helo, but anything fast like a Humvee or Technical that can get in and out quickly can be used.

- RAAS - Random Advance and Secure
- Recon - Reconnaissance - The observation of a region to locate the enemy or determine possible strategic features.
- Recon Element - Reconnaissance Structure. Technically you can recon from anywhere, most likely from a high vantage point, like a cliff, to locate the enemy, but sometimes you might be scouting out the area via a structure. This structure can be very generalized - a house, tower, small bunker, the fourth floor of an apartment, etc.
- Reloading - Replenishing a new magazine to the chamber
- Rep - Repair
- Repeat - Repeat the last fire order for IDF systems without adjustment.
- Reset - To back out of a fight so you can group up with your team
- Rev - Revive
- REZ - Resurrect/revive me
- Right on top of me - Means the enemy is in the immediate vicinity of your person or dead body
- RG - Rifle Grenade or HE Rifle Grenade
- Rocket or Rocke (rock-e) - Rocket Artillery Technical Truck. For the INS forces, each truck can be referred to by color.
- RPG - Rocket Propelled Grenade
- RPK - 7.62×39mm light machine gun of Soviet design
- RPM - Rounds per minute
- ROF - Rate of Fire
- Roger (that) - Message received and understood
- Roger Dodger - Message received and understood but better
- Rotate - to change positions
- RP - Rally Point - A spawn point for your squad only. One squadmate within 8 meters of you is required to place a rally. If an enemy gets closer than 10 meters to your RP it will be destroyed.
- RU - Russia
- RV - Rendezvous Point

- Salt - Being aggravated, upset, or annoyed
- SAS - Special Air Service - a special forces unit of the British Army
- SAW - Squad automatic weapon
- Say Again - Please repeat the previous order
- Scratch (that) - Disregard previous immediate order
- Self-Propelled Sandbags - A derogatory term for a Marine based on their emphasis on fighting on the front lines.
- Shift spawn - Spawn at a different FOB (the objective might have changed to a different location)
- Shot-Caller - A leader in the team who directs the team during a fight to maximize team coordination and communication. Usually the SL or fireteam lead
- Shot Over - notification given that an IDF system has sent a round(s) down range in accordance with a requested fire order alerting the observer to watch for the splash. (SHOT OUT is the confirmation reply from the observer if they have good drills)
- SL - Squad Leader
- Soft Car - Unarmored vehicle, like the BRDM-2 Scout Car
- Splash - Splash Damage - Mortar and Rocket rounds have splash damage that can hurt multiple tangos at once.
- Smokes - Smoke Grenades
- SNAFU - (a variant of FUBAR) = Situation Normal, All F***ed Up
- Snipes - Sniper
- Soft Flank - Flanking the enemy but with easy access to an escape back to your own team.
- SP - Spawn Point
- SP - Single Player
- Spawn - Refers to the designated area where players spawn (e.g. Main, FOB, Rally Point)
- Spawn Camp/Kill - The act of keeping the enemy team in their spawn area by killing them as soon as they walk out.
- Spawn shift - once you're dead spawn at a different HAB (which is closer to your current/next objective)
- SPM - Score Per Minute
- SR - Sniper Rifle
- Squad - Group of up to 9 soldiers. Every squad needs a squad leader. Can be further segmented into fireteams.
- Squad Lead - Squad Leader
- Squad, mount (up) - Squad, enter the designated vehicle
- Squirt that (location) - Suppress the SL’s desired target
- Stealth cap - part of a squad sneaks to a flag to capture it
- Stealth FOB - build a FOB where the enemy cannot see it.
- Strength Estimate - Estimated number of enemy infantry and/or vehicles. Term used from Commander to Scouting Squad or vice versa. Say the amount of infantry and vehicles in one's view, specifies vehicles and direction.
- Super-FOB - Too many structures in one spot. Needs a lot of resources to build. Can be easily destroyed by an airstrike. Rather build 2-3 FOBs instead of 1 Super-FOB to distribute risk.
- SVD - Dragunov sniper rifle

- TANDEM Round - Refers specifically to the tandem HEAT round used to defeat heavily armored vehicles
- Tango - Target
- Tango Down - Target Down
- Tango Uniform - Slang for "tits up," which is the position dead bodies tend to face. The term can be applied to the deceased as well as broken pieces of equipment
- Tank - refers to any armored vehicle that another teammate may see on the map, not specific at all to what it could be. Could refer to any IFV, APC, etc. with tracks. If it's an actual main battle tank, people will usually say it by the tank's name such as Leopard or Abrams, or simply call out "Main Battle Tank!"
- Tapped - Shot or Hit - Means to be shot and downed or shot and injured. Also, 1-tapping an enemy means killing them using only 1 shot.
- TBH - To be honest
- TC - Territory Control
- Team - Faction - One of the 2 groups fighting each other
- Technical or Techni (teck-e) - reference to the Insurgent/Militia force’s Technical Trucks. Can also refer specifically to the Armed Technical Truck.
- Throw Frags - Throw Fragmentation Grenades to SL’s desired target
- Throwing - The act of losing a game on purpose.
- Tilted - Being frustrated or put on edge to the point where it hinders your ability to play.
- TK - Kill someone on your team
- T/O - Task/Org
- TOW - Tube-Launched, Optically Tracked, Wireless-Guided BGM-71 TOW is an American anti-tank missile
- Toxic - Being rude and/or negative
- Tracking - An aiming style where the player follows a moving target with their crosshairs.
- Transport(s) - Transport Truck. Can be shortened to Trans.
- Trickling - When a team goes in one-by-one and dies rather than grouping up.
- TTK - Time To Kill, time needed to kill someone
- TTPs - Tactics/Techniques/Procedures (e.g. US Army Mortar TTPs)

- UE4 - Unreal Engine 4
- Un-Ass - To move immediately or leave one's current position.
- UP - Under Powered
- US - United States

- VBIED - Vehicle-borne improvised explosive device
- VC - Voice Chat. This refers to the voice chat channel that is available in-game.
- Vic - Vehicle
- VOIP - Voice over IP

- Wait - Hold position or Hold previous relay
- Wait out - useful for putting someone on 'hold' when you have other priorities to deal with first. (like taking cover!)
- Want you to thump that enemy - Want you to launch rifle grenades on that enemy. Order given to the squad member with rifle grenades. Always understood as HE grenades unless said otherwise.
- We’re (I’m) Mounted - refers to you and/or your squad on the transport truck or APC you’re assigned to for the mission
- Wilco - Will Comply or Roger (that)
- WOOT - A chant to show approval

- Zoning - Forcing the enemy away from a certain location

[Back to top](#squad-field-manual)

************************************************************************
# NATO Phonetic Alphabet
- The NATO phonetic alphabet is the most widely used radiotelephone spelling alphabet. It is used by most militaries.
- This can be used when calling out certain locations on the map. Instead if saying "M7" you'd say "Mike 7".
- Also great to know when you have to spell a word.

* A - Alpha
* B - Bravo
* C - Charlie
* D - Delta
* E - Echo
* F - Foxtrot
* G - Golf
* H - Hotel
* I - India
* J - Juliett
* K - Kilo
* L - Lima
* M - Mike
* N - November
* O - Oscar
* P - Papa
* Q - Quebec
* R - Romeo
* S - Sierra
* T - Tango
* U - Uniform
* V - Victor
* W - Whiskey
* X - X-ray
* Y - Yankee
* Z - Zulu

[Back to top](#squad-field-manual)


************************************************************************
# Console Commands

- Commands may change in future updates. To see the latest list of commands use the following command in your console: ListCommands <ShowDetail 0/1> (Prints out the information for all commands in the game)
- To see more information about a command use: ShowCommandInfo <CommandName> (Prints out the details of a particular command)

[Back to top](#squad-field-manual)


## Admin Commands
- AdminAddCameraman <NameOrId> : Add a player to the camera man list
- AdminAllKitsAvailable <Enabled 1/0> : Sets the server to ignore kit restrictions
- AdminAlwaysValidPlacement <Enabled 1/0> : Sets the server to ignore placement rules for deployables
- AdminBan "<NameOrSteamIds>" "<BanLength>" <Ban Reason> : Bans a player from the server for a length of time : 0=Perm, 1d=1Day, 1m=1 month, etc)
- AdminBanById <PlayerID> "<BanLength>" <Ban Reason> : Bans player with Id from the server
- AdminBroadCast <Message> : Send System message to all players on the server
- AdminChangeMap <MapName> : Change the map an travel to it immediately
- AdminDemoPlay <FileName> : Play Back the demo recording, must have file from server)
- AdminDemoRec <FileName> : Records gameplay, you must run this first
- AdminDemoStop : Stops recording and saves the demo to disk
- AdminDisableVehicleClaiming <Enabled 1/0> : Sets the server to disable vehicle claiming
- AdminEndMatch : Tell the server to immediately end the match
- AdminForceNetUpdateOnClientSaturation <Enabled 0/1> : If ture, when a connection becomes saturated, all remaining actors that couldn't complete replication will have ForceNetUpdate called on
- AdminKick "<NameOrSteamId>" <KickReason> : Kicks a player from the server
- AdminKickByID "<PlayerId>" <KickReason> : Kicks a player with Id from the server
- AdminKillServer <Force0/1> : Tells the server to stop execution
- AdminKillServer <Force0/1> : Tells the server to stop execution
- AdminListDisconnectedPlayers : List recently disconnected player ids with associated player name an SteamID
- AdminNetTestStop : AdminNetTestStop (Stops the network test)
- AdminPauseMatch : Tell the server to put the match on hold
- AdminProfileServer <SecondsToProfile> <bUseRaw> : Starts Profiling on the server for a fixed length of time, after which the profiling data is saved to disk
- AdminRestartMatch : Tell the server to restart the match
- AdminSetMaxNumPlayers <NumPlayers> : Set the maximum number of players for this server
- AdminSetNextMap <NameMap> : Set the next map to travel to after this match ends
- AdminSetNumReservedSlots : Set the number of reserved player
- AdminSetServerPassword <Password> : Set the password for a server or use "" to remove it
- AdminSlomo <TimeDilation> : Set the clock speed on the server 0.1 is 10% of normal speed 2.0 is twice the normal speed
- AdminSpawnActor <Index> : Create an Actor for testing (Currently unavailable, Devs only)
- AdminStats : Retrieve stats from the server
- AdminUnpauseMatch : Tell the server to take off the old
- TraceViewToggle : Execute a trace from the screen's center to any object and displays object's information

[Back to top](#squad-field-manual)


## Public Commands
- ApproveVehicleClaim : As a squad leader approve a vehicle claim made by a squad member attempting to enter a vehicle
- ChangeTeams : Change teams to the other side
- ChangeTeamsWithId <NewTeam> : Change teams to the specified team number, zero changes to the other side
- Chat <Message> : <ChatType=All|Teams|Squad> : Broadcast chat message
- ChatToAdmin <Message> : Send System message to all admins on the server
- ChatToAll <Message> : Chat to everyone
- ChatToSquad <Message> : Chat only to same squad
- ChatToTeam <Message> : Chat only to same team
- CreateReallyPoint : Drop a rally point for squad members to spawn from
- CreateSquad <Name> : Request the creation of a squad, specifying the name
- DisabledHudWidgets : Removes all widgets on the HUD
- DisabledUI : Removes the UI components from the screen
- Disconnect : Disconnect from server
- GiveUp : Die and give up being wounded
- HighResShot <Resolution/Multiplier> : take a screenshot,e.G. "HighResShot 3840x2160" or "HighResShot 4"
- JoinSquadWithID <Id> : Join a squad on our team with the following Id
- JoinSquadWithName <Name> : Join a squad on our team with the following name
- LeaveSquad : Leave the squad we are currently
- ListCommands <ShowDetail 0/1> : Prints out the information for all commands in the game
- ListPlayers : List play ids with associate player name and SteamID
- r.SetRes <Resolution> :Change screen resolution, r.setres 1920x1080f
- Reconnect : Reconnects to previous server
- ShowCommandInfo <CommandName> : Prints out the details of a particular command
- ShowNextMap : Ask the server what the next map is
- Stat FPS : Draw frame rate on screen
- Stat Unit : Draws game, draw, and gpu times on screen
- Respawn : Causes the Player to commit respawn

[Back to top](#squad-field-manual)


************************************************************************
# Admin Camera

- Can be used on maps to fly around
- You need to be admin (try it on Jensen's Range during training)
- Great to explore a map
- Shift + P : Turn on/off (if you set a keybind on 'P' it may not work)
- w,a,s,d : Move
- Shift : Move quicker
- Space : Go Up
- CTRL : Go Down
- Scroll Wheel : Forward = Faster Camera Pan / Backwards = Slower Camera Pan
- 0 : Info Display
- 1 : Speed
- 2 : Zoom
- F : Blur
- 6,7,8,9 : Spectator Tools

[Back to top](#squad-field-manual)


************************************************************************
# Sources and Resources

- I tried to list as many sources as possible.
- I'd like to encurage you to read the Squad Wiki for more detailed information on various topics.
- Since Squad's predecessor Project Reality is a Battlefield 2 mod, you can also find information in Battlefield related forums.
- Also, I learned a lot from watching various YouTube videos.
- I will also share guides from other Squad players in this GitHub repo.


## Websites
- Squad Wiki - https://squad.gamepedia.com
- Squad Lingo - https://steamcommunity.com/sharedfiles/filedetails/?id=1194778443
- Mortar Guide - https://steamcommunity.com/sharedfiles/filedetails/?id=1224460390
- https://old.reddit.com/r/joinsquad/
- https://old.reddit.com/r/joinsquad/wiki/starter-guide
- https://web.archive.org/web/20200224212716/http://forums.joinsquad.com
- https://www.protondb.com/app/393380
- Usgu's Squad Manual (Nov 2015, http://cdn.akamai.steamstatic.com/steam/apps/393380/manuals/Squad_Alpha-Manual_1_2_0.pdf?t=1448234414)
- Usgu's Squad Manual (Feb 2016, https://steamcdn-a.akamaihd.net/steam/apps/393380/manuals/Squad_EA-Manual_1_1.pdf?t=1527101610)
- Cheesy Tactical Guide - https://steamcommunity.com/sharedfiles/filedetails/?id=571391558, https://drive.google.com/file/d/0B6sPT1ZeeQA3aGx3YWlHblFQVnM/edit and https://drive.google.com/file/d/0B_iNCOG63HtsSF9oN2NTOXVJNHc/view
- SgtHerhi's "How Not To Suck At" guides - example: https://old.reddit.com/r/joinsquad/comments/7f08ol/how_to_not_suck_at_offense/
- Battlefield Wiki - https://battlefield.fandom.com
- https://squad.projectawesome.com/serverRules
- https://squadmaps.com/


## YouTube Channels
- There are a lot of great videos online to learn more about every aspect of Squad.
- Search for "squad new player guide", "squad sl guide", "squad tank guide", etc.
- Here are a few YouTube channels that you might like (in alphabetical order):
  - Bastion Black Performance (This channel contains real-life small unit tactics. It's not Squad specific, but still interesting.) - https://www.youtube.com/channel/UCHuwc9VESIqSNQzkCwVePdQ/playlists
  - Captain - https://www.youtube.com/c/BHMCaptain/playlists
  - Cwarfighter - https://www.youtube.com/channel/UCVqaQzElqtR_0A5oXk0uzBw/playlists
  - Gorlami14 - https://www.youtube.com/c/Gorlami14/playlists
  - Karmakut - https://www.youtube.com/c/karmakut/playlists
  - MoiDawg - https://www.youtube.com/c/MoiDawg/playlists
  - MrAtomicDuck - https://www.youtube.com/user/MrAtomicDuck/playlists
  - Nano - https://www.youtube.com/c/Nanoytgaming/playlists

[Back to top](#squad-field-manual)


# The End

```
     .--._____,
  .-='=='==-, "
 (O_o_o_o_o_O) Munster, 2021
```
