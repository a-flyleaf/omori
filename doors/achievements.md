---
layout: ws
title: Achievements (WIP)
permalink: achievements
css: "
table{border-collapse:collapse;} th,td{border:1px solid #bfbfbf; padding:.25em; vertical-align:top;}
th{vertical-align:middle;}
td p{margin:0;} td br{margin-bottom:.25em;} td ul,td ol{margin:.15em 0 .15em 1em;} td li ul{margin:0 0 0 1em;}
.chk th{width:2em;} td.chk{text-align:center;}

.canon{font-family:sans-serif;} .canon p{display:inline-block;} .canon>p{font-size:.8em;}

.copy{max-height:15em; overflow-y:scroll; background:#efefef; font-family:consolas,monospace; font-size:.75em; padding:0 1em;} #md{padding:1em;}
.copy a{text-decoration:none; pointer-events:none;}
.copy strong,.copy b{font-weight:normal;} .copy em,.copy i{font-style:normal;}
.copy .omo{text-transform:none;}

.pad1 td{padding-top:.5em;} .pad2 td{padding-bottom:.75em;}

@media print{
	.wrap{padding:0;}
	.pad1 td,.pad2 td{padding:.25em;}
	
	th,td{border:2pt solid lightgray;}
	td:nth-child(3){max-width:2in;}
	/*https://stackoverflow.com/questions/4730216/keep-an-html-element-from-spanning-multiple-pages-when-printed/4730244#4730244*/ tr.pad1{page-break-after:avoid;} tr.pad2{page-break-before:avoid;} /*this... doesn't seem to work, at least not on my computer, but oh well*/
	
	a{text-decoration:none;} /*https://www.sitepoint.com/css-printer-friendly-pages/#addsupplementarycontent*/ a::after{content: ' (' attr(href) ')'; font-size:.8em;}
	
	.note::after{content:'achievement list from the OMORI wiki; reordered with notes by a-flyleaf last updated 2023 Dec.14'; text-align:right; margin:5pt; display:block; font-size:.8em; font-family:sans-serif; max-width:33em; float:right; line-height:1.5;}
	
	#check,footer{display:none;}
}"

# sorting note to self:
# 000-099 Prologue (Vast Forest, Otherworld)
# 100-199 Three Days Left (Faraway 1, Orange Oasis minus Breaven, Pyrefly Forest, Sweetheart's Castle)
# 200-299 Two Days Left (Faraway 2, Breaven, Last Resort, Underwater Highway, Humphrey)
# 300-399 One Day Left (Faraway 3, endgame)
achievements:
  - nm: Good Morning!
    dc: Wake up in the morning.
    rt: 3
    typ: story
    order: 100
    how: <b>Plot checkpoint</b>; achieved on Three Days Left of both routes.
  - nm: Oyasumi.
    dc: Go to sleep after a long day.
    rt: 3
    typ: story
    order: 150
    how: <b>Plot checkpoint</b>; achieved on Three Days Left of both routes.
  - nm: Alt+F4
    dc: Defeat <span class="omo">Download Window</span>.
    rt: 3
    typ: story
    order: 50
    how: <b>Plot checkpoint</b>; achieved during the Prologue of both routes.
  - nm: See you, Space Boyfriend...
    dc: Defeat <span class="omo">Space Ex-Boyfriend</span>.
    rt: 3
    typ: story
    order: 90
    how: <b>Plot checkpoint</b>; achieved during the Prologue of both routes.
  - nm: <span class="omo">Ohohohoho!!</span>
    dc: Defeat <span class="omo">Sweetheart</span>.
    rt: 3
    typ: story
    order: 190
    how: <b>Plot checkpoint</b>; achieved during Three Days Left of both routes.
  - nm: Buy high, sell low.
    dc: Defeat <span class="omo">Mr. Jawsum</span>.
    rt: 3
    typ: story
    order: 250
    how: <b>Plot checkpoint</b>; achieved during Two Days Left of both routes.
  - nm: When I flex, I feel my best!
    dc: Defeat <span class="omo">Pluto (expanded)</span>.
    rt: 3
    typ: story
    order: 251
    how: <b>Plot checkpoint</b>; achieved during Two Days Left of both routes.
  - nm: Slime Time is Over!
    dc: Defeat <span class="omo">Slime Girls</span>.
    rt: 3
    typ: story
    order: 275
    how: <b>Plot checkpoint</b>; achieved during Two Days Left of both routes.
  - nm: Whale done.
    dc: Defeat <span class="omo">Humphrey</span>.
    rt: 3
    typ: story
    order: 276
    how: <b>Plot checkpoint</b>; achieved during Two Days Left of both routes.
  - nm: There's something behind you...
    dc: Reach the other ending.
    rt: 3
    order: 900
    how: |-
      <b>Plot checkpoint</b>; ending-based.
      - In the <b style="display:inline-block;">True Route</b>, do not save Basil.
      - In the <b style="display:inline-block;">Hikikomori Route</b>, [play to the end. Unsure if moving out is necessary?]
  - nm: Green Thumb
    dc: Water a plant back to life in <span class="omo">Basil</span>'s garden.
    rt: 3
    order: 165
    how: <b>Plot checkpoint (optional)</b>; the party draws attention to it on Three Days Left of both routes.
  - nm: So majestic... so beautiful...
    dc: Fly the <span class="omo">Butt Certificate</span> in <span class="omo">Cattail Field</span>.
    rt: 3
    order: 25
    how: <b>Plot checkpoint (missable)</b>. Before climbing up to Otherworld, complete the quest <span class='omo'>Berly's Lost Ball</span> to earn your certifications.
  - nm: Recycling is a concept.
    dc: Get all rewards from the <span class="omo">Recycling Machine</span>.
    rt: 3
    order: 35
    how: |-
      Recycle 50 items. [Unsure if actually obtaining the <span class='omo'>Universal Remote</span> is necessary?] You'll likely find a few through regular gameplay, but this amount will take some dedicated grinding.  
      There are <a href='https://omori.fandom.com/wiki/RECYCLING_MACHINE#STRATEGY'>two major methods</a>, both of which have a chance of returning a <span class="omo">Can</span>:
      - In Vast&nbsp;Forest, pet the shadow&nbsp;dog. You'll always get something; 1/6th chance of a <span class="omo">Can</span>.
      - In the Junkyard, Kel has a 5/8ths chance of scavenging an item at the start of every battle; <span class="omo">Can</span> is one of the options. *You do not need to complete the battle to gain the item*; the Fandom Wiki recommends level 10--12 for a guaranteed runaway.  
        
      You could theoretically scrounge up 50+ recyclables via Vast&nbsp;Forest and get this achievement shortly after reaching Otherworld for the first time, but my condolences to your patience.
  - nm: <span class="omo">What's the big idea?!?!</span>
    dc: Make your way and talk to the <span class="omo">Lone Mole</span>.
    rt: 3
    order: 37
    how: Found in the Otherworld Outskirts, surrounded by traffic cones.
  - nm: xD
    dc: Get the <span class="omo">LOL Sword</span>.
    rt: 3
    order: 260
    how: |-
      1. In Pyrefly&nbsp;Forest (west of entry), obtain the <span class="omo">Joke Book</span> and talk to Weeping&nbsp;Willow to accept her quest.
      1. In Underwater&nbsp;Highway > Last Resort, examine the joke sign in through the construction area. You will be unable to explore this space until Pluto is defeated.
      1. Return to Weeping&nbsp;Willow and, with Hero tagged, tell her the Construction Joke.
  - nm: Christmas Crusher
    dc: Ruin Christmas.
    rt: 3
    order: 175
    how: In Sprout&nbsp;Mole Village, use Omori to cut down the Christmas tree.
  - nm: "[Season] Sympathizer"
    dc: Choose the <span class="omo">[Season] Mole</span>.
    rt: 3
    order: 175
    how: In Sprout&nbsp;Mole Village, tell one of the seasonal moles (Spring, Summer, Fall, and Winter) that that's your favorite season. *You can only make this decision once per playthrough*; to get them all in one go, save before answering, pick, reload, repeat.
  - nm: AWEKJRLKJFLKASNFAWIJGAWEFJAWEKFJAKFAASJFKA
    dc: Kill the first <span class="omo">Sous Chef</span>.
    rt: 3
    order: 180
    how: In Sweetheart's Castle, Royal Kitchen, make at least one mistake during your first attempt at cake-baking.
  - nm: Everyone's a critic.
    dc: Watch all movies in <span class="omo">Sweetheart</span>'s "throne room".
    rt: 3
    order: 180
    how: There are 11 in total. Have fun!
  - nm: As expected from professionals!
    dc: Perfectly train the <span class="omo">Sprout Mole</span> choir.
    rt: 3
    order: 180
    how: "[may require save-scumming?]"
  - nm: Hope and Vigor!
    dc: Complete <span class="omo">Orange Joe</span>'s quest.
    rt: 3
    order: 170
    how: Both brothers are in Orange&nbsp;Oasis. The one you're looking for is on the second level of Dino's&nbsp;Dig.
  - nm: The Chosen One
    dc: Turn the valve to the right in <span class="omo">Rain Town</span>.
    rt: 3
    order: 170
    how: Self-explanatory. *You can only make this decision once per playthrough*; save before turning if you want to see both results.
  - nm: Ain't nobody here but us chickens.
    dc: Defeat the <span class="omo">Chicken?</span> at the top of <span class="omo">Dino's Dig</span>.
    rt: 3
    order: 170
    how: "*Be warned*: The chicken will run on its first move, and will not respawn. Its <span class='omo'>Speed</span> is 110. Good luck!"
  - nm: The currency of the future...
    dc: Trade <span class="omo">Clams</span> for <span class="omo">Clems</span>.
    rt: 3
    order: 193
    how: |-
      <b>Missable</b>. Involves the following steps:
      - After defeating Sweetheart, talk to Pessi in Sprout&nbsp;Mole Village to accept the quest <span class="omo">Pessi's Thing</span>.
      - Also in Sprout&nbsp;Mole Village, find the Shady&nbsp;Mole and accept his quest <span class="omo">B.E.D.</span>; you can complete it without leaving the Village.
      - This causes the Shady Mole to appear outside the Last&nbsp;Resort after Pluto is defeated. Agree to trade your Clams. Experience regret.
      
      (Spoiler alert: You can find the Mole again, and earn your hard-earned Clams back, after defeating him elsewhere in the Underwater&nbsp;Highway.)
  - nm: Ghost Party!
    dc: Have a Ghost Party.
    rt: 3
    order: 240
    how: |-
      Personal recommendation: Save this quest for last, or at least towards the very end when you're running around tying up loose ends. However, you can achieve it early as reaching Last&nbsp;Resort.
      1. Outside the Resort, take a dive through the haunted pool to find the Ghost&nbsp;Party. The Tophat Ghost will give you the quest of the same name.
      2. You'll find the remaining ghosts at the following locations:
        - Last&nbsp;Resort, in one of the rooms
        - Sweetheart's&nbsp;Castle > Royal&nbsp;Gallery
        - Orange&nbsp;Oasis, far southeast
        - Otherworld > Frozen&nbsp;Lake
        - Otherworld > Junkyard, in one of the conveyor-puzzle areas
        - Vast&nbsp;Forest > Pinwheel&nbsp;Forest
      3. Return to the Tophat Ghost. Celebrate!
  - nm: Good Dog?
    dc: Pet all the creatures in <span class="omo">Marina</span>'s sector in <span class="omo">Humphrey</span>.
    rt: 3
    order: 270
    how: <b>Plot checkpoint (optional)</b>; you'll be passing through to progress the story. If you poke a critter, just leave & re-enter the map to make it re-appear.
  - nm: Mmm... <span class="omo">Sweetheart</span>, I mean, <span class="omo">Tofu</span>.
    dc: Hold 99 <span class="omo">Tofu</span>.
    rt: 3
    order: 38
    how: |-
      Can be found through various means, including but not limited to:
      - Kel's Junkyard-scavenging (1/8th chance)
      - fishing in Frozen Lake
      - purchased from Tofu&nbsp;Jash in Sprout&nbsp;Mole Village (for 1 clam each), or from Smuggler&nbsp;Jash in Sweetheart's&nbsp;Castle (for 2 clams each)
      - use Aubrey to smash vases in Sweetheart's Dungeon
      - digging on the first floor of Dino's&nbsp;Dig
      - dropped by most Sprout&nbsp;Mole enemies, namely those around Sweetheart's&nbsp;Castle
      
      You *must* have 99 in your inventory at one time to get the achievement; it's not cumulative.
  - nm: Bunny Exterminator
    dc: Defeat 100 <span class="omo">Bunnies</span>.
    rt: 3
    order: 15
    how: Just bash some rabbits; they're found in most major areas, so no need to grind out the gate. At the Train&nbsp;Station through Vast&nbsp;Forest, Leafie will tell you how many you've felled.
  - nm: Squizzard Exterminator
    dc: Defeat 100 <span class="omo">Squizzards</span>.
    rt: 3
    order: 240
    how: "[Unsure if you need to defeat Pluto first?] Navigate to Seacow&nbsp;Farms through the Underwater&nbsp;Highway. Between rounds, head in the barn to get rewards from Farmer&nbsp;Jim and/or heal from the milk pail. Every last squizzard respawns every time you leave and return to the farm outside. Alas, there is no counter. This will take *some time*. Have fun!"
  - nm: <span class="omo">Thank you! Thank you! Thank you!</span>
    dc: Commission <span class="omo">Rococo</span>.
    rt: 3
    order: 191
    how: After defeating Sweetheart, Rococo can be found in the Castle basement.
  - nm: Patron of the Arts
    dc: Commission all of <span class="omo">Rococo</span>'s art.
    rt: 3
    order: 192
    how: "Leave and re-enter Sprout Mole Village to trigger artwork completion. Costs 106,000 clams total, including the first.<br>Personal tip: combine this with squizzard-farming (a later achievement) both to farm clams and break up the monotony."
  - nm: Power of Friendship!
    dc: <span class="omo">Release Energy</span> on your foes.
    rt: 3
    order: 10
    how: Tutorial-compelled one does not count.
  - nm: One for the Road
    dc: Gain <span class="omo">Bread</span> using <span class="omo">Bread Slice</span>.
    rt: 3
    order: 15
    how: Omori learns this at Level&nbsp;5.
  - nm: Perfect Weather Conditions
    dc: Defeat <span class="omo">Kite Kid</span>.
    rt: 3
    order: 30
    how: "Found in Pinwheel Forest. Although you can go back for this immediately after reaching Otherworld, be warned: he's strong!"
  - nm: <span class="omo">Gwahahaha!!</span>
    dc: Defeat ???.
    rt: 3
    order: 31
    how: "<b>Missable</b>. Spoiler alert, it's Pluto; find and defeat him in the Otherworld&nbsp;Campsite *before* obtaining the Special&nbsp;Mixtape."
  - nm: Goodbye, World!
    dc: Defeat <span class="omo">The Earth</span>
    rt: 3
    order: 39
    how: "<b>Missable</b>. Found in Captain Spaceboy's shortcut to the Junkyard. (It's not obvious our planet can be interacted with!) Will disappear on Two Days Left."
  - nm: Ohoooooooooo...
    dc: Defeat the <span class="omo">Unbread Twins</span>.
    rt: 3
    order: 240
    how: "[Unsure if you need to defeat Pluto first?] Although you unlock Orange&nbsp;Oasis earlier than this, Breaven will be inaccessible until Two Days Left. Poke around the “graveyard”; once you fall in, there's no way out until you reach and defeat these two."
  - nm: The First Law
    dc: Defeat <span class="omo">Roboheart</span>.
    rt: 3
    order: 270
    how: "After Molly's cutscene, Roboheart can be found in her section of the Slime&nbsp;Girls' Lair."
  - nm: Minty Fresh
    dc: Brush your teeth every day.
    rt: 3
    order: 101
    how: <b>Missable</b>. Achievable during waking segments. [Probably locked after daytime?]
  - nm: Good Dog
    dc: Pet a dog.
    rt: 3
    order: 34
    how: Pet the shadow&nbsp;dog in a Vast&nbsp;Forest grotto, or Hector or Lucas in Faraway.
  - nm: Littering is bad, recycling is better.
    dc: Throw away something.
    rt: 3
    order: 5
    how: "[Can probably be done as soon as you have inventory access?]"
  - nm: R.I.P.
    dc: Read all the tombstones in the... dev room...
    rt: 3
    order: 350
    how: In the neighborhood segment of Black&nbsp;Space, find the dev room through one of the tombstones. Gotta read ’em all.
  - nm: You think you're clever, huh...
    dc: "Enter code: haveadollariguess at www.omocat-shop.com for $1.00 off."
    rt: 3
    order: 99
    how: "<b>Missable; Steam-exclusive</b>. Name the protagonist “OMOCAT”. (Does nothing on consoles.)"
  - nm: They call me <span class="omo">Scarethrow</span>.
    dc: Listen to <span class="omo">Mr. Scarethrow</span>'s rant.
    rt: 3
    order: 60
    how: "[Unsure if defeating Jawsum is necessary?] Found in the Junkyard. Dialogue will loop when complete."
  - nm: It's all a dream...
    dc: Unlock all achievements/badges. Thank you for playing <i class="omo">Omori</i>.
    rt: 3
    order: 1000
    how: Achieve everything else on this list. Congratulations!
  - nm: One more day...
    dc: Reach the good ending.
    rt: 1
    order: 925
    how: Save Basil, then continue against Omori.
  - nm: Close your eyes...
    dc: Reach the bad ending.
    rt: 1
    order: 925
    how: Save Basil, but do *not* continue against Omori.
  - nm: Up high...
    dc: High-five <span class="omo">Kel</span>.
    rt: 1
    order: 120
    how: <b>Plot checkpoint</b>; route caveat above applies.
  - nm: Down low...
    dc: High-five <span class="omo">Kel</span> three times.
    rt: 1
    order: 300
    how: <b>Missable</b>, if of course you haven't high-fived Kel on all three days. The high-fives themselves, however, are plot checkpoints.
  - nm: Too Slow!
    dc: Don't high-five <span class="omo">Kel</span>.
    rt: 1
    order: 121
    how: <b>Plot checkpoint</b>; route caveat above applies. Note that there's an achievement for high-fiving on all three days, but none for rejecting thrice.
  - nm: I'll just take that...
    dc: Take $20.00 from <span class="omo">Kel</span>'s wardrobe.
    rt: 1
    order: 200
    how: Go on. Be a thief.
  - nm: It's honest work.
    dc: Complete all part-time jobs once.
    order: 114
    how: Route caveat above applies. Jobs can be found at Gino's&nbsp;Pizza, Othermart, and Fix-It; doing a *good* job is not required.
    rt: 1
  - nm: Against all odds...
    dc: Get a perfect score delivering <span class="omo">pizza</span>.
    rt: 1
    order: 114
    how: Route caveat above applies. You *can* read the notes, if you squint. I believe in you! (Maybe ask a friend.)
  - nm: That can't be good for business.
    dc: Quit in the middle of a part-time job.
    rt: 1
    order: 114
    how: Route caveat above applies. Othermart and Fix-It jobs can be aborted via poster; on Gino's bike, Quit.
  - nm: Good Company
    dc: Go to <span class="omo">Sean</span> and <span class="omo">Karen</span>'s housewarming party.
    rt: 1
    order: 114
    how: |-
      <b>Missable</b>.
      1. On Three Days Left, interact with the couple at Fix-It.
      2. In the <b>morning/daytime</b> of One Day Left, pay them a visit.
      3. Party's in the <b>evening</b> of the same day.
  - nm: Math Whiz
    dc: Complete the math worksheet correctly.
    rt: 1
    order: 114
    how: "(Technically achievable on both routes, as long as you answer the door on Three Days Left.)"
  - nm: Grammar Whiz
    dc: Complete the grammar worksheet correctly.
    rt: 1
    order: 114
    how: Route caveat above applies.
  - nm: Tummy Full of Fish
    dc: Feed the <span class="omo">Stray Cat</span> every day and sunset.
    rt: 1
    order: 113
    how: |-
      <b>Missable</b>. Locations courtesy <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=2342372862">phantom2450's guide on Steam</a>:
      1. Three Days Left, morning/day: Faraway Park > monkey bars
      1. Three Days Left, evening: Basil's house > roof
      1. Two Days Left, morning/day: Sunny's house > roof
      1. Two Days Left, evening: outside Othermart > tree
      1. One Day Left, morning/day: Faraway Park > hideout
      1. One Day Left, evening: church graveyard > Mari's grave
      
      Calls for six Fish ($10/ea) total.
  - nm: <span class="omo">NEEERRRDDDDD!!!</span>
    dc: Lose to <span class="omo">Kim</span> and <span class="omo">Vance</span>.
    rt: 1
    order: 115
    how: <b>Plot checkpoint (optional)</b>. The story will continue regardless.
  - nm: The Art of Self-defense
    dc: Defeat <span class="omo">The Hooligans</span> with <span class="omo">Pepper Spray</span>.
    rt: 1
    order: 225
    how: <b>Missable</b>. The fight is a plot checkpoint, but you'll need to snag the pepper spray from Kel's house *before* heading to the hideout. (And of course, you can choose *not* to pepper spray a bunch of losers; the story will proceed regardless.)
  - nm: Bees?
    dc: Battle the "bees".
    rt: 1
    order: 215
    how:
      <b>Missable</b>. During Two Days Left, after picking up the "pizza" order, find the hive in Faraway Park; winning not required. Will disappear after the lake cutscene.
  - nm: Music Connoisseur of Sorts
    dc: Insert every song into <span class="omo">Gino's Jukebox</span>.
    rt: 1
    order: 315
    how: "This is also <a href='https://omori.fandom.com/wiki/Category:CDS'>a Process</a>; Pet&nbsp;Rock championship required. [details TBA]"
  - nm: The Very Best
    dc: Defeat the <span class="omo">Pet Rock</span> champion.
    rt: 1
    order: 314
    how: "This is <a href='https://omori.fandom.com/wiki/PET_ROCKS#PLAYERS'>a Process</a>. [details TBA]"
  - nm: Reduce, reuse, and recycle!
    dc: Defeat the <span class="omo">Recyclepath</span>.
    rt: 1
    order: 230
    how: |-
      <b>Missable</b>.
      1. On Two Days Left, evening, find the Fashionable&nbsp;Mom outside her house. Complete her sidequest by talking to the Strange&nbsp;Man at Fix-It, then the cashier, then finally returning to Mom.
      2. On One Day Left, morning/day, swing by the hideout. *You can only fight the Recyclepath once*; save before just in case.
  - nm: Universally Loved
    dc: Receive all <span class="omo">flowers</span> in the hospital.
    rt: 1
    order: 110
    how: This is a massive, *massive* process, requiring 100% diligence through all three days of the True Route. [details TBA]
  - nm: When she was here...
    dc: Give <span class="omo">Flowers</span> to <span class="omo">Mari</span>.
    rt: 1
    order: 310
    how: Flowers can be bought for $2 at Fix-It. You can get this achievement on One Day Left only.
# HIKIKOMORI-EXCULSIVE HERE ONWARD, ORDER UNSURE
  - nm: Good Boy
    dc: Complete your <span class="omo">To-Do List</span>.
    rt: 2
    order: 325
    how: <b>Plot checkpoint [obligatory?]</b>. On One Day Left, sort your stuff.
  - nm: A Bit Less Lonely
    dc: Commission all of <span class="omo">Gator Guy's</span> statues.
    rt: 2
    order: 335
    how:
      Leave and re-enter Last Resort through the ground floor exit to trigger statue completion.
  - nm: Take Me to the River!
    dc: Let the plastic fish finish its song.
    rt: 2
    order: 335
    how: "[need batteries via Pinkbeard, then Frozen Lake]"
  - nm: Welcome Home
    dc: Take the <span class="omo">Keeper of the Castle's</span> power.
    rt: 2
    order: 335
    how: "[after resetting Headspace, below Sweetheart's Castle.] Will permanently override the Castle."
  - nm: I'll cherish you all forever.
    dc: Get the <span class="omo">Flower Crown</span> from <span class="omo">Basil</span>.
    rt: 2
    order: 335
    how: "[after resetting Headspace, not sure if story-obligated or at a specific place?]"
  - nm: Anytime is a good time for a picnic!
    dc: Recover at all of <span class="omo">Mari</span>'s picnics.
    rt: 2
    order: 335
    how: |-
      Picnic locations:
      - Forest Playground
      - Vast Forest
      - Pinwheel Forest
      - Otherworld
      - Junkyard (there are 2; you'll pass them both as part of the story)
      - Frozen Lake
      - Orange Oasis
      - Rain Town
      - Breaven
      - Pyrefly Forest (2; again, both will be passed)
      - Sprout Mole Village
      - Sweetheart's Castle (3; Dungeon, Servants' Quarters, and Royal Theater)
      - Last Resort (3; one outside, one inside, another at the construction site)
      - Deep Well
      - Humphrey (3, two in Slime&nbsp;Girl areas and a third [towards the end])
      - Snowglobe Mountain (2, [details TBA])
  - nm: We'll always be there for you, <span class="omo">Omori</span>.
    dc: Visit all mirrors.
    rt: 2
    order: 335
    how: |-
      Mirror locations:
      - Forest Playground
      - Pinwheel Forest
      - Otherworld Campsite
      - Pyrefly Forest
      - Sprout Mole Village
      - Sweetheart's Castle
      - Underwater Highway
      - Last Resort
      - Humphrey
      - Orange Oasis
      - Snowglobe Mountain
  - nm: The view is pretty nice...
    dc: Look through all telescopes.
    rt: 2
    order: 335
    how: |-
      Telescope locations:
      - Otherworld
      - Orange Oasis
      - Underwater Highway
      - Snowglobe Mountain
  - nm: See you, Space Husband...
    dc: Defeat <span class="omo">Space Ex-Husband</span>.
    rt: 2
    order: 335
    how: "[Plot checkpoint?] Found at the peak of Snowglobe Mountain."
  - nm: The Brightest Stars
    dc: Defeat <span class="omo">Pluto</span> and <span class="omo">The Earth</span>.
    rt: 2
    order: 335
    how: Found at the Junkyard shortcut, One Day Left.
  - nm: Inhuman
    dc: Defeat <span class="omo">Mutantheart</span>.
    rt: 2
    order: 335
    how: Found in the Slime Girls' Lair, One Day Left.
  - nm: Minor Imperfection
    dc: Defeat <span class="omo">Perfectheart</span>.
    rt: 2
    order: 335
    how: Found in the Slime Girls' Lair, One Day Left.
  - nm: Seriously, you're the coolest!
    dc: Beat the <span class="omo">Boss Rush</span>.
    rt: 2
    order: 335
    how: Found in Humphrey, One Day Left.
  - nm: Repressed
    dc: Defeat every <span class="omo">Something</span> at the bottom of the <span class="omo">Lost Library</span>.
    rt: 2
    order: 335
    how: "[Plot checkpoint?]"
  - nm: Foes Filed!
    dc: Complete the <span class="omo">Foe Facts!</span> journal.
    rt: 2
    order: 335
    how: "[is a Process]"
---
# achievements (WIP)
there sure are a lot of them.

basically lifted off [the fandom wiki](https://omori.fandom.com/wiki/ACHIEVEMENTS), but with separate [how-to info](#how-to) for ease of reading/copying. <span style="background:yellow;">**should be [printer-friendly](https://www.sitepoint.com/css-printer-friendly-pages/)!** [this is a self-reminder; there's *some* printer-specific CSS here but I should keep checking it as the page develops]</span>

----

\*Story-based; you’ll get these just by beating the game.  
T: True Route, touch grass \| H: "Hikikomori," don't do that

<table>
	<thead>
		<tr><th colspan="2">routes</th><th rowspan="2" id="info">info</th></tr>
		<tr class="chk"><th>T</th><th>H</th></tr>
	</thead>
	<tbody>{%assign ach=page.achievements|sort:"order"%}{%for a in ach%}
		<tr class="pad1">
			{%if a.rt==1%}<td rowspan="2" class="chk">✔</td><td rowspan="2" class="chk">✗</td>{%endif%}
			{%if a.rt==2%}<td rowspan="2" class="chk">✗</td><td rowspan="2" class="chk">✔</td>{%endif%}
			{%if a.rt==3%}<td rowspan="2" class="chk">✔</td><td rowspan="2" class="chk">✔</td>{%endif%}
			<td class="canon">
				<b>{{a.nm|markdownify}}</b>
				{{a.dc|markdownify}}
			</td>
		</tr>
		<tr class="pad2"><td{%unless a.how%} style="background:yellow;"{%endunless%}><!--TEMP <span style="font-family:courier; display:inline-block; border:1px solid #bfbfbf; padding:0 .25em; width:7em">ORDER: <span style="float:right;">{{a.order}}</span></span> <!--/TEMP-->{{a.how|markdownify}}</td></tr>
	{%endfor%}</tbody>
</table><div class="note"></div>

<section id="check" markdown="1">
## checklists
note that links and other formatting (bold, italics) in the info column isn't mirrored here due to coding limitations

### markdown
<div class="copy" id="md">TR = True Route \| HR = Hikikomori Route \| br = both routes&nbsp;&nbsp;<br>\* = story checkpoint<br>{%for a in ach%}<br>- [ ] ({%if a.rt==1%}TR{%else%}{%if a.rt==2%}HR{%else%}{%if a.rt==3%}br{%if a.typ=="story"%}\*{%endif%}{%endif%}{%endif%}{%endif%}) **{{a.nm}}**: {{a.dc}}&nbsp;&nbsp;<br>{{a.how|replace:'- ','<br>&nbsp;&nbsp;- '}}<br>{%endfor%}</div>

### plaintext
<div class="copy" id="pt"><br>[TR] = True Route | [HR] = Hikikomori Route | [br] = both routes<br>* = story checkpoint<br>{%for a in ach%}<br>{%if a.rt==1%}[TR]{%else%}{%if a.rt==2%}[HR]{%else%}{%if a.rt==3%}[br]{%if a.typ=="story"%}*{%endif%}{%endif%}{%endif%}{%endif%} { {{a.nm}} } {{a.dc}}<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{a.how|replace:'- ','<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- '}}<br>{%endfor%}</div>
</section>
<!--copy javascript? https://www.w3schools.com/howto/howto_js_copy_clipboard.asp-->

<!--## Processes
for the drawn-out ones where, if you miss one step or progress the story, you've locked out the whole achievement-->