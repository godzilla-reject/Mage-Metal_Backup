---
cssclasses: [clean-embeds]
---
*For my best friends, Brody, Josh, Caleb, Konnar, Matthew and everyone else. I made this game, and all in the future, for us.*
```table-of-contents
```
# *Foreword*
It is rare that I am without word.

But, the support that I have gotten from the people who have eagerly awaited this mere playtest. *That* leaves me without words. 

Thank you. If you have *ever* let me rant about the Terrarium, been forcefully shown some random game element with “do you think is too complicated?!?” in behind it or suffered through ***yet another*** “Game Design is Still Hard” status in Gen chat, this thank you is for you. Thank you for never angering with me while I forgo a fun night of games to toil away at this passion project of mine. 

From the bottom of my heart, **thank you**. 

It is with a full and happy heart I welcome you to `=[[Dev Helpers]].game-full`. 
# Overview 
*”Greetings Pilot and welcome back to the Terrarium. Time since last Lunar Incursion: 709 Solar Days.”*
- - -
Good morning, Pilot. You’ve graciously agreed to help test the latest in USH automatic biographing technology in the form of the *Advanced Magisterial Pilot Condition and History Bio-Log* (AMP-CHB). The following document contains all of the instruction you should need to complete the test here today.

Welcome to `=[[Dev Helpers]].game-full` *Character Creation Playtest*. The goal of this test is to check the viability, stability and usability of the character creation rules for this game. The following materials are required (and should have been provided) for this playtest:
- A copy of this document. 
- A personal copy of [this](https://docs.google.com/spreadsheets/d/11sFDvnzlPyw0b4NcCGj40xoyfQpYLrE9l6w3kMeaYho/edit?usp=sharing) Google Sheet. This is the playtest character sheet, and it is *not* final. It is handy due to taking the stress of math off of playtesters. 
- At least 3 six-sided polyhedral dice (“d6’s”.)
- A device capable of allowing you to fill out [this](https://forms.gle/osrYS3qtCQ6ktG6m8) feedback form. 

This is the *first* playtest of the *first* game I have ever designed. I am not promising something amazing, but it is *your* feedback that will help it *become* something amazing. This has been a passion project of mine for the better part of the last year of my life, and I sincerely hope that this first playtest can spark an interest within you, dear player, to bear with an aspiring game designer as we all delve into the *Terrarium* over the remnants of Earth Prime over this series of playtests.

The following is an overview for how to create the *Mage* that ends up being *in* the *Metal.* As you follow these instructions, read the content set out before you, and create one of the first characters within a budding universe, keep a few things in mind: 
- *What can be better?*
- *What do you enjoy?*
- *What doesn’t make sense mechanically?*
- *What DOES make sense mechanically?*

Again, I thank you dearly for being apart of this first playtest. Have fun, Pilots, and remember:

***UNITED, WE WILL SLAY THE FOUR HORSEMEN***

# Character Creation Part 1: *The Mage*
## 1. *Playing The Game*
Before you begin determining the mechanics of your character, it is important to have a grasp on the narrative of said character. This idea, referred to by us “professionals” as a *narrative concept*, will help direct and inform the mechanical choices you make during character creation. Maybe your character is some hot-shot piloting prodigy, or a crotchety old veteran that chose to join the Pilot Program after being relieved of duty. 

Make sure your concept is appropriate for the game your GM wants to run, as well as the party you'll be playing with. No one wants to see that their friend has sat down at the table with the intention of playing someone evil in a game all about saving orphans. Probably. I don’t know your friends.

Once you have your concept in order, it might also be beneficial to familiarize yourself with the core rules and mechanics in play under the game, otherwise known as the *system.*

### The Favor System 
The Favor System is the name of the "engine" so-to-speak that `=[[Dev Helpers]].game-short` runs off of. Most games' system would be as simple as "d20," but some are "d20, roll under" or a "dice-pool" system. The Favor System is the modular, under-the-hood, workings of the TTRPG that can be adapted into other games (with enough work). Not all of the mechanics of this game are part *of* the Favor System; the mechanics that are not are wholly unique to this game, and, in theory, would not appear in their same form in other Favor System games. The core components of the Favor System are the dice mechanics, action structure and player mechanic layouts. These various components are briefly summarized below.

#### Dice Structure
The Favor System uses 3d6 for nearly all rolls, with the target number being static and the die result needing to be **lower** than the target number. This set of 3d6 can be changed by the game's variance system (think “advantage” and “disadvantage” in *Fifth Edition*.) Rolling *with favor* (or with “advantage”) lets the player roll 2d6 instead, and rolling *without favor* (or with “disadvantage”) lets the player roll 4d6 instead. This variance mechanic is, in my opinion, the most unique aspect of the system, and this is the reason the system is named for it. The dice mechanics are explored further in Appendix A: Dice Overview.

#### Action Structure 
The Favor System uses a simple set of mechanics for governing *timed action*, which is any scene that constitutes the players having limited time to perform actions, such as combat. During sequences of timed action, a player can move up to their Speed (or equivalent statistic), perform two Actions, and take one Reaction. A typical Action might include something like firing a Weapon, while a Reaction might be casting a spell to protect an ally from damage. More details can be found in Appendix B: Action Overview.

#### Player Mechanic Layout
Part of the Favor System is how it defines the relationship between a mechanic and its associated power progression. This idea is heavily inspired by usage-based progression from video games such as *Morrowind* and *Oblivion*, in which the player unlocks new powers (or "perks") for an ability or skill via usage. The Favor System changes this slightly to be based on *training* instead, in order to prevent the players from having to book-keep how often they use skills or abilities. A practical explanation of this, for example, would be the Training-Perk progression of a player's School of Arcana: when Player A gains a new training level in his School, he gains a numerical bonus of some form; perhaps he gains a +2 bonus to damage with spells from that school, and then he gains the perk associated with that training level. This is to avoid players needing to develop things like a skill and ***then*** get that cool perk they wanted two levels ago but did not meet the requirements for. Some mechanics within a Favor System game might forgo this direct relationship for things that have no real progression to them, such as a background or player species.

Now that you know more about the inner workings of this game, lets get you familiarized with the nitty gritty: Attributes and Statistics; these are the mathematical core of your Mage.
### Mage Mechanics Overview
Taking the typical “number set plus derived number set” approach of most RPGs, `=[[Dev Helpers]].game-short` divides these two sets into Attributes (the primary number set) and Statistics (the derived number set.)
> [!info|right wm-sm txt-left ttl-c] *A Note On Rules Language*
> `=[[Dev Helpers]].game-short` uses a combination of *italics*, **bold** and Proper capitalization in its rules text to help differentiate and call attention to important pieces of rules text. An example of this is ‘Attributes’ and ‘Statistics’ always being capitalized properly due to being mechanics.

#### Attributes
These are the most fundamental parts of a character. Each Attribute begins at 10, and are **rarely** changed after character creation. 
#####  Power
Power is a measure of physicality and force.
*Governs* 
- Carry Weight 
- Melee
#####  Body
Body is a measure of the robustness and physical fortitude of a character.
*Governs* 
- Toughness
- Health
##### Reflex
Reflex is a measure of agility and manual dexterity.
*Governs* 
- Accuracy
- Speed
##### Mind
Mind is a measure mental fortitude, education, and memory. It is _not_ intelligence. A smart character can have poor memory, and thus, poor Mind. Mind can also influence magic.
*Governs:* 
- Skill Aptitude 
- Spell Memory
##### Potential
Potential is a measure of a creature’s ability to exert their influence on the world via metaphysical or meta-mental means, AKA magic. While hand-in-hand with Mind, Potential is seen by some as a form of spirituality as well.
*Governs*
- Spell Memory
- Mana
##### Tenacity
Tenacity is a measure of how powerful a creature's personality and charisma is. Tenacious characters have a much easier time convincing others of things, as well as inspiring allies. Some also consider tenacity to be a meta-physical, or magical, measure of luck and fate. 
*Governs* 
- Luck
#### Statistics
Derived from their respective Attribute, different Statistics have differing formulae for calculating them. If a Statistic would have a decimal, round *down.*
##### Power
- Carry Weight
	- Measures how much a character can carry and remain unaffected. A character is considered encumbered when they're over half of their Carry Weight.
	- Max: Power * 12. 
- Melee Damage Bonus 
	- A bonus to melee weapon damage.
	- Power - 10. 
##### Body
- Toughness
	- A character's ability to resist physical damage.
	- Body/6
- Health
	- This is a measure of how much damage a character's body can sustain before failure.
	- Max HP: Body. 
##### Reflex
- Ranged Accuracy Bonus 
	- A bonus to ranged attack rolls.
	- Reflex - 8.
- Speed
	- How far one can move in 6 seconds. 
	- (Reflex * 3)/10
##### Mind
- Skill Aptitude
	- A measure of how many skills one can use to their fullest extent. A skill that a character has *aptitude* with gains access to the Skill Perks of that skill. Not having aptitude does not affect their capacity to use that skill in any other way.
	- Mind/4
##### Potential 
- Spell Memory
	- How many spells can be prepared a day.
	- Mind+Potential/4.
- Mana
	- Resource used to cast spells.
	- Potential * 2.
##### Tenacity
- Luck
	- Luck is a meta-currency that players can use to fuel actions with the [[Fated]] trait.
	- Tenacity/5 (Minimum of 2.)
#### Proficiencies
> [!info|right ws-med txt-left ttl-c] *Skills and Aptitude*
> In `=[[Dev Helpers]].game-short`, skills are essential to all characters. They can be found in Appendix D: Skill List. More information is found in the *Finalizing Skills* section of character creation.

![[Character Mechanics Overview#^c79b91|*Insert Proficiencies when Done*]]

## 2. *Species*
Once you feel that you are familiar enough with the game’s mechanics, you are ready to move on to creation proper. The first step in this process is answering this question:

*Who are you?*

Pick one of the following three species. While there are only three options in this playtest, launch is planned to include at least nine species across three factions. 

Once you’ve picked your species, make sure you select a Species perk and an Attribute boost, as well as denote other bonuses from your species. 

Take this time to go ahead and fill out non-mechanical details, such as name, age, pronouns, faith, etc.

### ***Species of the United Solar Hegemony*** 
*Formed after the destruction of Earth Prime, the U.S.H. stands as a shining example of comradery and unity.*
#### *Dwaurves of Mars*
![[Dwaurves]]
#### *Elves of Venus*
![[Elves]]
#### *Humans of Nowhere*
![[Human]]
## 3. *History*
After determining your character’s Species, you must answer another question:

*Where did you come from?*

The answer to this question is your character’s *History.* This is what the character did *before* becoming a Pilot, and the skills they learned there are invaluable, even now. Their History also determines their starting assets and currency via a measure of Wealth.

Pick one of the following Histories. They are presented in order of Poor to Extreme.

After your selection, ensure you denote your History’s perk and Attribute boost. Once this is done, select or denote the skills gained from your History. You *do not* gain aptitude in them by default. 

Make sure you also list any other starting bonuses or equipment from your chosen History.

Finally, ensure you denote your character’s *starting wealth*, as stated on the following chart.
![[Starting Wealth Chart]]

### Poor Histories
![[Dusted]]
![[Hegemony Nomad]]
### Moderate Histories
![[Rapscallion]]
![[Wrench Monkey]]
### High Histories
![[Corpo Deskie]]
![[Influencer]]
### Extreme Histories
![[Politologist]]
![[Noble]]

## 4. *School of Arcana*
Now that you have decided what your character did before becoming a Mage Pilot, you are faced with yet another question.

*How do you wield the arcane?*

The answer to this question is the methodology of magic your pilot chose to specialize in when they were training to become a Mage-Pilot. Divided into Schools, these orders of magic represent deep philosophical ideas about reality and magic, as well as their preferred method for blowing up bad guys.

Pick from one of the following School of Arcana, then select one of the two available Paths offered by your chosen School. You become Trained in your School, and gain the first Perk of your chosen Path.

After your selections, ensure you denote your School’s Attribute Boost and any starting gear. Take this time to inscribe your starting spells in your Grimoire as well. 
![[School Note]]
## 5. *Pilot Role*
After making a selection as to the style of magic you wield, you are now posed with a final question:

*What role do you fill within a squad?*

The answer to this question is your *Pilot Role*. This is simply what *you do* on the battlefield, in and out of the Metal. The classical idea of the “tank”, “support” and “DPS” are all determined by this choice.

Select a Pilot Role from the following options, then select one of the two Role Specializations offered by the chosen Role. You then become Trained in your Role.

Denote any proficiencies granted by your Role, and then denote the skills granted by your Role and Specialization. You *do not* gain aptitude in them. Finally, inscribe your Specialization’s starting Spell in your Grimoire. 
![[Role Note]]
## 6. *Finalizing Attributes and Statistics*
Now that your four core selections have been made, its time to finalize your Attributes. Assign 12 free Attribute points across your Attributes. You cannot begin play with an Attribute above 20.

Once you have assigned all 12 points, take this time to calculate your Statistics (if you aren’t using the *free digital character sheet*. Which, you should be. I worked really hard on it.)
## 7. *Finalizing Skills and Proficiencies*
After your Attributes and Statistics are finalized, you are ready to finalize your Skills and Proficiencies. 
### **Skills**
Designate a number of Skill Aptitudes as determined by your Skill Aptitudes Statistic, then select one Skill you are Trained in and have Aptitude with. You begin play as an Expert in that Skill.
### **Weapon and Armor Proficiencies**
Select one Armor proficiency and one Weapon proficiency to increase your training level with by one step (untrained to Trained or Trained to Expert.) You cannot begin play with an Armor or Weapon proficiency at or above Mastered.
### **General Proficiencies**
From among **Perception**, **Piloting** and **Spell-Work**, pick two to begin play at Trained and one to begin play at Expert.
## 8. *Creating a Grimoire*
After all of your mechanical selections, you can move on to creating your *Grimoire*, which is a catalog of all the spells your Mage can cast. These are the guidelines for creating your Grimoire:
1. At Tier 1, your Grimoire can contain Rank 0-3 spells.
2. Your Grimoire can contain a number of spells equal to your Tier * 10 (which is 10.)
3. You have access to any spell on a spell list that either does not have an access requirement or you meet the requirement for. Spells can be found in [[Character Creation Playtest 1 Packet#Appendix C Spell Lists|Appendix C Spell Lists]]
## 9. *Selecting Perks*
Each character in `=[[Dev Helpers]].game-short` has (a) quirk(s) that helps set them apart from other characters. These quirks are known as *General Perks*. Select one for your Mage Pilot.
![[Perk Note]]
## 10. *Selecting Equipment*
After selecting a General Perk, the final step of Mage creation is to determine what equipment your Pilot uses. 

Using the starting wealth granted by your **History**, purchase as little or as much equipment from [[Character Creation Playtest 1 Packet#Appendix E Equipment|Appendix E: Equipment]]. USH-M basic gear recommendation is at least one weapon (preferably that you have a proficiency in), one suit of armor (also, preferably that you have proficiency in), and some basic gear such as Nutri-gel, a Hardlight Torch, a backpack and a set of clothes. 

After gear acquisition, denote any remaining credits.  
## 11. *Finishing Up*
Congratulations, you’ve completed the first (and more complicated) half of character creation for this play test. Take this time to go ahead and fill out the *Mage* section of the linked feedback questionnaire. 

Now, it is time to create the *Metal* for the *Mage*. Proceed to Part 2: *The Metal*.

# Character Creation Part 2: *The Metal*
Just like your Mage, a concept of your Metal is needed before you begin creating it. A couple things to keep in mind when making up the concept for your Mage’s first Metal:

1. Make sure your Metal fits any criteria your playgroup agrees on keeping consistent across everyone’s Metals. This might be as simple as a shared naming method, or as important as everyone using the same Frame.
2. Ensure your Metal is a reflection and extension of your Pilot. This is exactly what Metals are; extensions of the inner parts of a Mage and their magic, given raw and powerful form. 

Once you’ve nailed down the concept of your Metal, review how Metal Mechanics differ from Mage.
### Metal Mechanics 
![[Metal Attributes and Statistics]]
## 1.  *Frame*
The *Frame* is the most basic component of the Metal, forming the foundation of which all other parts are mounted upon. It determines fundamental aspects of a Metal, such as Size, body-plan, and weapon mounts.

Select a **Frame** from the options below, then denote the Attribute bonuses, Weapon Mounts, and any Perks or Integrated Systems granted by the Frame.

![[BF-001]]
![[BF-002]]
![[HF-001]]
![[HF-002]]
![[LF-001]]
![[LF-002]]
![[SHF-001]]
![[SHF-002]]
![[ULF-001]]
![[ULF-002]]
## 2. *Shell*
The *Shell* of the Metal is what determines the armor plating of your Metal, as well as an *Intrinsic* ability that provides powerful combat abilities. 

Pick a **Shell** from the options below. Selection is restricted by your chosen **Pilot Role** during Mage creation. 

After you’ve chosen your **Shell**, denote the following: Attribute boost, armor type, Weapon Mounts, and Intrinsic.
![[Bunker Buster]]
![[Fortress Breaker]]
![[Subtle Dialog]]
![[Surgeon General]]
![[Wire Runner]]

## 3. *Soul Core*
The *Soul Core* of the Metal is exactly that: a core, with a soul therewithin. It acts as the heart of the Metal’s *Soul-Resonance Reactor*, or S-R<sup>2</sup> Engine. The soul of spirit within the core reacts with the latent Potential of the Pilot, providing a nearly infinite amount of energy to run the massive machine. 

The **Soul Core** of a Metal is a special choice for a Pilot, as it dictates a special confrontation that the Pilot must eventually face at their darkest hour; the *Deity within the Machine*, the **Deus Ex Machina**. Pay special attention to the **Deus** of your chosen **Soul Core**. 

Pick a **Soul Core** for your Metal, and then denote granted the granted Attribute bonuses, Core Passive, and Core Intrinsic. You can also denote your **Deus Ex Machina**, but it will not be relevant in this playtest (or the next one, honestly.) In future playtests, **Soul Cores** will be limited by your chosen **School of Arcana** during Mage creation.

![[ATSC-001 ''Warring Dragons'']]
![[DTSC-001 ''Steelclad Mamba'']]
![[STSC-001 ''Infinite Hydrangea'']]

## 4. *Finalizing Metal Attributes and Statistics*
After selecting your Metal’s basic components, it is time to finalize its Attributes and Statistics, just as you did for your Pilot. 

Assign 6 free Attribute points. You cannot begin play with a Metal Attribute above 30.

Once you’ve assigned these points, take this time to calculate your Metal’s Statistics if you aren’t using the digital character sheet (which, again, you should be. I worked *really* hard on it.)
## 5. *Installing Metal Systems*
Other abilities, such as *jet boosters* and other typical mecha-fantasy fair, in `=[[Dev Helpers]].game-short` are relegated to *Systems*, which each Metal can only have a select amount of. This limit is dictated by the **System Points** Statistic. 

Spend these SP on as many, or as few, systems as you want. You *do not* have to spend all of them. 

In future playtests, Systems will be limited in access by the components of the Metal. 

Metal Systems can be found in [[Character Creation Playtest 1 Packet#Appendix F Metal Equipment|Appendix F: Metal Equipment]]
## 6. *Mounting Weaponry*
As you’ve created your Metal, you’ve seen mention of “weapon mounts.” These are, in effect, ‘weapon slots’ for your Metal. Each mount has a “size”: *auxiliary*, *secondary*, *primary*, *heavy* and *superprimary*. 

Each mount can house a weapon of its size or *one smaller*. Additionally, *super-primary* weaponry can be mounted across *two* mounts, at least one of which must be a *primary/aux* or *heavy* mount.

Some mounts also have other modifiers, such as “Twin” or “(Restriction)”. Two of the same weapon can be installed in a Twin mount, and can be fired independently *or* simultaneously. Mounts with (Restrictions) are limited to only what is permitted by the Restriction. 

Finally, a mount can have a “/Aux” modifier, which allows for an extra auxiliary weapon to be installed alongside the main weapon that fires when the main weapon is fired. 

Each mount on your Metal must have a weapon installed in it. 

Metal Weapons can be found in [[Character Creation Playtest 1 Packet#Appendix F Metal Equipment|Appendix F: Metal Equipment]]
## 7. *Finishing Up*
Your Metal is mechanically complete! Congratulations! 
# Wrapping Up
There is one last step here: style and flair. Take this time to go a bit more in-depth on what both your Pilot and their Metal look like. Write up a small description of both your Mage-Pilot and your Metal, incorporating things chosen during creation of each of them.

From here, go ahead and fill out the second part of the Playtest Feedback Questionnaire. Once you’ve done that, ensure you keep a copy of your character sheet, as you’ll be revisiting this same character in Playtest 2 (and beyond!)

Again, I want to personally thank you for being a participant in the first ever playtest for my first ever game. I had no clue the amount of work that would go into just getting here, but the continued interest from all of the people closest to me is what got me to this point. I look forward to the next playtest, and I hope you do too.

Remember Pilots,

**UNITED, WE WILL SLAY THE FOUR HORSEMEN**

# Appendices 
## Appendix A: Dice Overview 
![[Dice Overview]]
## Appendix B: Action Overview
![[Actions Overview]]
## Appendix C: Spell Lists
![[Spell List]]
## Appendix D: Skill List
![[Skill List]]
## Appendix E: Mage Equipment 
### E.1: General Equipment
![[Equipment Appendix]]
### E.2: Weaponry Pr
### E.3: Armor
## Appendix F: Metal Equipment
### F.1: Metal Systems 
### F.2: Metal Weaponry 