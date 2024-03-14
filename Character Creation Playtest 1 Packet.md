---
cssclasses: [clean-embeds]
---
*For my best friends*

*I made this game, and all in the future, for us.*

# *Foreword*
It is rare that I am without word.

But, the support that I have gotten from the people who have eagerly awaited this mere playtest. *That* leaves me without words. 

Thank you. If you have *ever* let me rant about the Terrarium, been forcefully shown some random game element with “do you think is too complicated?!?” in behind it or suffered through ***yet another*** “Game Design is Still Hard” status in Gen chat, this thank you is for you. Thank you for never angering with me while I forgo a fun night of games to toil away at this passion project of mine. 

From the bottom of my heart, **thank you**. 

It is with a full and happy heart I welcome you to *`=[[Dev Helpers]].game-full`*. 

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


## 2. *Species*
Once you feel that you are familiar enough with the game’s mechanics, you are ready to move on to creation proper. The first step in this process is answering this question:

*Who are you?*

Pick one of the following three species. While there are only three options in this playtest, launch is planned to include at least nine species across three factions. 

Once you’ve picked your species, make sure you select a Species perk and an Attribute boost, as well as denote other bonuses from your species. 

Take this time to go ahead and fill out non-mechanical details, such as name, age, pronouns, faith, etc.

### ***Species of the United Solar Hegemony*** 
*Formed after the destruction of Earth Prime, the U.S.H. stands as a shining example of comradery and unity.*
#### *Dwaurves of Mars*
*One of the three Founding People of the Unified Solar Hegemony, the Dwaurves are a hearty people, stern and powerful. Strangers consider them to be too work-centric, putting their working lives ahead of all else aside from family and drink. Those who have spent time within the cold, dry air of the Martian stone-cities, however, can attest that they are a zealous people, dedicated to family and craft with an unparalleled passion only found miles below the Martian desert.*

Dwaurves were the last of the Founding Peoples to ratify the United Constitution of Sol, and many attribute this to the fact that they are slow to trust outsiders. In their own history, they have a long past of constant warfare; the horrors of Mars refuse to let even a single drop of blood go unearned. When something is won of a dwaurf, lest it be blood or honor, that pact is kept eternal. 

If you seek to play a Mage-Pilot who can survive any horror of the cosmos, dedicate a heart of iron to their allies, and brandish wanton loyalty, the Dwaurves of Mars is right for you. 
##### Characteristics
###### You Might...
- Remain loyal to those you consider forge-sibling, no matter their petty slights against you.
- Have an eye for all things stone and metal, knowing pinnacle craftsmanship when you see it.
- Refuse to break or back down when given the chance to do so.
###### Others Probably...
- See you as, frankly, a *stubborn ass.* Some say this is an asset, though most claim it to be a liability.
- Assume you are a heavy drinker.
- Respect, or fail to, the deep connection you hold with your family, clan, and clade.
##### Physical Description
Dwaurves are shorter than the standard Human by about one foot, standing around five foot on average. They boast wide, compact bodies, built on burly frames. Dwaurves of all genders are fully capable of growing thick, curly beards, which they often braid into intricate arrays of complex patterns that are specific to their job, family, clan, and clade. Long beards and short head hair are a sign of masculinity and leadership amongst them, while thin, face-hugging beards and long, flowing hair is a powerful sign of femininity. Clean-shaven, bald dwaurves are dishonorable, untrustworthy, and unclean.

The Dwaurves of Mars typically mature into adulthood around age 50, though each clan has more specific coming-of-age ceremonies that draw the line of adulthood in other ways. A dwaurf's lifespan is around 400 years, though death is typically regarded as something a dwaurf must agree to.
##### Society and Culture
Long before the Venusian Elves claimed the moons of Saturn, or mankind grasped the dust of their moon, the Dwaurves fought against the other *natives* of Mars: the Starbeasts. Natively named for the sounds Dwaurven hunters made when running from them, these animals represent the bulk of the history of the Dwaurves; that is, an arms race against a species of ever-evolving megafauna. As such, craftsmanship of new and better weapons was the name of the game, and the only place they could do so was deep in the caverns of Mars.

Today's dwaurves, having nearly hunted the Starbeasts to extinction, still maintain a production-based, group-minded culture. This is merely a broad-stroke for them, however. Culture varies vastly between the different stone-cities, and even between clades within the cities. Most dwaurves, even still, share a passion for the finer aspects of metallurgy, stonework, masonry, and gem-cutting. Most enjoy bare-hand brawling, architectures, and mining as well. 

Each dwaurf is given an *icon* at birth; this represents their clan and clade. This icon is typically a weapon, though it varies. To have an icon taken is an ultimate crime, and to freely part with it is an ultimate dishonor. 
##### Morality and Religion
While quite a bit more secular than both humans and elves, dwaurves do have a primary religion: The Steel Pact, which is named such for the original Dwaurf, Adaman, forging a pact with the Serpent of the Heavenly Steels at the dawn of creation. This pact afforded a boon to Adaman: he was granted the ability to wield the Six Heavenly Steels, which are mythical metal alloys that hold magical properties. In modern times, the Pact is highly metaphorical; each alloy represents a balancing act between two opposing forces in the world, such as the Sixth Steel, Tyrannium, representing the balance between the need for leadership and the desire of tyranny. 

Most dwaurves are lawful in nature, and while they are quite selfless, they are also very protective of their own and warry of outsiders, leading some to declare them quite neutral parties. A strong sense of justice helps define them further as a people who work hard, but play even harder. 
##### Naming Tendencies 
Dwaurves have, admittedly, quite complex naming conventions. A dwaurf's full name is their chosen name (selected when they come of-age), their given name (the name given by their birthing-parents), their family name, their clan name, and their clade name. Given names are normally a virtue, while chosen names are normally relevant to the individual's coming-of-age. 
###### Sample Names
Below are some examples of names.
####### Chosen Names 
Agna, Bodril, Doegin, Vinyar, Kotri, Rogar.
####### Given Names 
Torra (Tenacious), Yangari (Powerful), Viim (Silent), Ruski (Loud), Kazva (Calm).
####### Family Names 
White-Beard, Star-Runner, Moon-Catcher, Boulder-Breaker, Beast-Waker.
####### Clan Names 
Mogrung, Fargraven, Gigantua, Nekarik, Bodungrin.
####### Clade Names 
Shipwrighter, Stonecutter, Timberyarder, Anvilbreaker.
- - -
###### Dwaurf Mechanics

>[!info|left] Species Information 
>**Attribute Boost**: Body
>
>**Size:** 1
>
>**Species Bonuses:** Dwaurves gain a +1 to Toughness at character creation. Dwaurves also begin play with one weapon or equipment that acts as the icon of their clan and clade. 
>
>**Languages:** Common, Dwaurven , Additional *common* Languages equal to 1 minus your Skill Aptitude.
>
>**Special Senses:** 
>- *Night Vision:* You can see in total darkness as if it were moderate light.
>

>[!column|left] ***Species Perks:*** Choose 1 From Options Below
>> [!metadata] *Option 1* Arcane Resilience
>> You take 2 less damage from all spells. This applies *before* Toughness.
>
>> [!metadata] *Option 2* Hardy
>> You gain a +5 bonus to Health at character creation.
>
>> [!metadata] *Option 3* Rock and Stone!
>> You gain Stonesight, a sense that allows you to see through mundane stonework, with a range of 60 feet.
#### *Elves of Venus*
*One of the three Founding People alongside Dwaurvenkind and Humankind, the Elves are a mystical, superstitious and martial people dedicated to their endless pursuit of understanding perfection. Those foreign to the City-States of Venus consider the Elves to be esoteric, cold and brutal. Those who are willing to shelter from the burning heat of the Venus landscape in the grand pyramids, however, know that the Elves are, in fact, brutal, and maybe even esoteric, but they are ruthlessly dedicated to an idea of fulfilment others can barely fathom.*

First of the species of Sol to leave their planet, Elves lived in the shadows of Old Earth until humankind was ready to take their baby steps into the stars. The elves were quick to ratify the United Constitution of Sol, which sits in stark contrast to the Dwaurves. 

Much like the Martians, Elves also have a history soaked in blood, though not their own. Descendants of an intergalactic race of uber-warriors, elves warred amongst themselves across the cosmos until they quite literally blew themselves back to the stone age. This happened long before the advent of humankind on Old Earth, and much of this history has been lost to the endless eons. To lose history, or any other knowledge, is to fall off of *El Camino a la Perfección*. 

Elves seek perfection through both mystical and mechanical, but through martial as well. Elves are astute fighters, who are quick to act but slow to win, loving to toy with their prey on the battlefield.

If you wish to play a Mage-Pilot who seeks to understand the universe through magic and metal, shed brilliant blood, and preserve history, the Elves of Sol are right for you. 
##### Characteristics
##### You Might 
- Be slow to trust and form bonds due to your extreme lifespan.
- Never break bonds once they are formed.
- Seek to understand a very narrow corner of reality in pursuit of *El Camino a la Perfección*.
##### Others Might 
- See you as “odd” or “unusual” due to the stories told of Elven tradition.
- Assume you are a perfectionist, to your detriment.
- Adore, or slight, you for your people’s dedication to knowledge and religion. 
##### Physical Description
Elves stand taller than the average Human by about one foot, standing roughly seven feet tall on average. They have lithe, wiry frames, with slightly-too-long limbs. Most elves are thin, though there is just as much possible variation between body types as humans.

Most who have never seen an elf typically have an issue telling apart "male" elves from "female" elves. This is primarily due to elves’ lack of sexual dimorphism and facial androgyny. Elves possess no secondary sex characteristics, and possess the capacity to change their reproductive organs at will.

Facially, elves typically possess sharp features and pointed ears, though some House bloodlines have rounded or even squared ears. Elves also cannot grow facial hair. 

Elves have an exceptionally long lifespan, living normally around 1,000 years. This leads to the timescale of their perception working fundamentally differently to other mortalkind. Elves normally come of age at 200 years old, as this is when they first typically hear the Summoning for the first time. The Summoning, a curse upon the very blood of the Elves, summons the deepest instinct of their warrior-race past, driving them into an animalistic frenzy roughly once every fifty years.
##### Society and Culture
While the Dwaurves warred against nearly unconquerable beasts on Mars, Elves were in an arms race of their own; they were desperate to find a way to fight the slow collapse of Venus’ atmosphere. 

After being set back to a stone-age level of technology at the very end of the Forerunner War, elves used remnants of their ancestor’s technology to accelerate technologically at an alarming rate, eventually shedding concepts such as war in favor of peace to unite against the common problem. As such, elven society, even now, is still leagues ahead of the other Sol species. The elven idea of philosophy is that war is unneeded, but violence is an acceptable answer and that technology is the only way forward. This stands in stark contrast with the Summoning, the magical curse put upon Elven blood. 

In time, these opposing forces have come to conflict, and now harmony. Each elf is taught the ways of war, the ways of magic, and the ways of technology. This three-fold path is essential to an elf’s development in spirit, body, and mind, and their society seeks to perfect them all. 

##### Morality and Religion
Classically, the Elves follow the Tradition, a religion formed from the fundamentalist ideas of the Forerunners in which they are descendants of. The Tradition is a wild combination of martial blood-sport, flesh sacrifice, ritual sexual acts and convoluted rituals. This "religion" is not followed openly in the modern day of the Hegemony, but it is *felt* throughout Elven society. There are some sects who still follow the Tradition, and believe that the Summoning is tied to straying from the Path set forth by the Tradition.

In modernity, elves follow the Three-Fold Path, or *El Camino a la Perfección*. This can be summed up as the idea that, in order to lead a perfect life, one must perfect their body, soul, and mind. Past this, the elves idea of “morality” is the pursuit of making life fair for all things, if not equitable. 
##### Naming Tendencies 
Elves choose their own names in accordance to their pursuit of the Three Paths, as well as have a name that is given to them at birth and their House name.
##### Sample Names
###### Given Names
Mahoti, Ikla, Ncouti, Chunguti
###### Perfect Mind Names 
Conoci, Medacón, Papel
###### Perfect Body Names 
Lanza, Espada, Blindaje
###### Perfect Soul Names
Oración, Magi, Deletreer
###### Family Names 
1. Tialoc
2. Xolotli 
3. Ehecatli
4. Centeōtl
5. Xipe Totec
6. Tōnatiuh
- - -
##### Elf Mechanics

>[!info|left] Species Information 
>**Attribute Boost**: Reflex
>
>**Size:** 1
>
>**Species Bonuses:** Elves gain a +3 bonus to Skill Aptitude at character creation.
>
>**Languages:** Common, Elvish, Additional *common* Languages equal to 1 minus your Skill Aptitude.
>
>**Special Senses:** None.

>[!column|left] ***Species Perks:*** Choose 1 From Options Below
>> [!metadata] *Option 1* Elven Nimble-ness
>> You gain a +2 bonus to Speed.
>
>> [!metadata] *Option 2* War-God Accuracy
>> You gain a +1 bonus to Accuracy.
>
>> [!metadata] *Option 3* Bloodline Magic
>> You gain an extra starting Rank-0 Spell. You do not have to meet its School requirements. You always have this spell prepared, regardless of Spell Memory. 
#### *Humans of Nowhere*
*First of the Founders of the Hegemony, Humankind is a barbaric, bloody, and war-driven race with the unique ability to form a pack-bond with nearly any creature or inanimate object in the known universe. Many, including their Hegemony contemporaries, think them to be too short-sighted, but it is this short-sightedness that has taken humankind to the stars, past the Fringe, and into deep space. With their home planet annihilated by the Apostels, Humankind now calls the Terrarium home.*

The youngest of the three major species in the Sol system, humankind once called Old Earth home, but after it was torn asunder by the first coming of the Apostels, humankind constructed the Terrarium to act as a new home and center of the budding United Solar Hegemony. This new empire, the first of its kind in the Milky Way, allowed the species of Sol to consolidate enough power, resources and intellect to finish Project New Steel, which gave the Hegemony the first truly mass-produced Metals, as well as the ability to train Mage-Pilots en masse. 

As for the attitudes of humankind, we are all *too* familiar with how driven humankind is, lest it be by passion, lust or war. 

If you seek to play a Mage-Pilot who desires the throes of combat and harbors limitless potential, the Humans of Nowhere might be for you. Humans are complicated. They know. 
##### Characteristics
###### You Might…
- Seek to manifest your ideals at all costs.
- Desire a new Earth for humankind.
- Form relationships and friendships with all peoples easily.
###### Others Probably…
- Respect your capability to fit into any niche and find a role in any situation.
- Fear you seek only blood and death.
- Find it difficult to form expectations of you. 
##### Physical Description
Humans are highly adaptable, and due to their tragically short life-spans, evolve to fit new environments quickly. As such, their appearance is highly dependent on climate, with sunny, bright or hot environments causing humans to have darker skin while colder climates give rise to humans with much lighter skin tones. 

Humans can have hair and eyes of nearly any color. In previous times, this was limited to only select colors, but awakening humankind’s latent magic seems to have caused new mutations that allow for the full color spectrum to be expressed. Humans will typically have hair and/or eye color that relates to the type of magic they have the most talent in. 

Humans reach physical maturity around the age of 15, though they are unique in that they do not reach *mental* maturity at the same time (that typically happens around age 25.) A typical human can live for roughly 90 years, though some can live longer. Humans also have a highly mutable two-helix DNA structure, which allows them to intermarry with nearly any other species and produce offspring that bear traits of both parent species. The most notable of these half-humans are the eladryn, or half-elves, and the gnomes, or half-dwaurves.

It’s complicated, they know. 
##### Society and Culture
Humans have a long, varied and rich history of doing two things: fighting and reproducing. Humans, despite all originating from the same small group on Old Earth, grew to hate one another across their long history, only learning to put differences such as skin color and sexual preference aside when faced with an extinction-level climate crisis during the final centuries of Old Earth. 

Now, in modernity, Humankind shares the common burdens of being the leading species of the Hegemony and having no place to call their own. They bear constant reminder of the destruction brought to Earth, looking down on its remnants from the massive space-city known as the Terrarium. 

Culturally, humankind still widely varies across each group and niche; this constant state of change makes humankind seem to lack a concise culture and empire. It’s complicated, they know. 
##### Morality and Religion
Humans are widely superstitious, even if they claim not to be. The idea of “luck” and “fate” are both distinctly human in that *something random could just happen.* Nearly all other species believe that there is a reason for all things, but humans instead think that *randomness* is the core aspect of the universe that drives all things.

Despite this die-roll driving force, humans are strict about both morality and religion, having waged many a war over both. The issue is that no two groups of humans can actually agree on one religion or moral code. It’s complicated, they know. 
##### Naming Tendencies 
Humans, at least cosmically, have pretty simple names. A birth name, given by parents, and a surname, or family name. Humans are also widely known to choose a completely different name and go by that, ignoring their given name. Still other groups of humans use naming schema from dwaurves or elves, and even still others might not even have names at all! It’s complicated, they know.
- - -
##### Human Mechanics

>[!info|left] Species Information 
>**Attribute Boost**: Any.
>
>**Size:** 1
>
>**Species Bonuses:** At character creation, humans can select an additional Weapon, Armor, or General proficiency to become Trained in. 
>
>**Languages:** Common, Additional *common* Languages equal to 1 minus your Skill Aptitude.
>
>**Special Senses:** None.

>[!column|left] ***Species Perks:*** Choose 1 From Options Below
>> [!metadata] *Option 1* Intuitive Skill 
>> Choose a Skill you are proficient in and have aptitude with. Whenever you gain a new level of training in another Skill, you also gain that training in the chosen Skill.
>
>> [!metadata] *Option 2* Naturalborn Pilot
>> You begin play as an Expert in Piloting.
>
>> [!metadata] *Option 3* Supernatural Talent
>> Once per day, you can spend a Luck point to choose the outcome of a single roll you make. 

## 3. *History*
After determining your character’s Species, you must answer another question:

*Where did you come from?*

The answer to this question is your character’s *History.* This is what the character did *before* becoming a Pilot, and the skills they learned there are invaluable, even now. Their History also determines their starting assets and currency via a measure of Wealth.

Pick one of the following Histories. They are presented in order of Poor to Extreme.

After your selection, ensure you denote your History’s perk and Attribute boost. Once this is done, select or denote the skills gained from your History. You *do not* gain aptitude in them by default. 

Make sure you also list any other starting bonuses or equipment from your chosen History.

Finally, ensure you denote your character’s *starting wealth*, as stated on the following chart.

| Wealth Level | Starting Funds |
|:------------:|:--------------:|
|     Poor     |      800       |
|   Moderate   |      1200      |
|     High     |      1800      |
|   Extreme    |      2700      |

### Poor Histories
> [!info|no-i]- #### Dusted
> Referred to as such due to the amount of exhaust dust that coats the slums, you are one of the Dusted. The Dusted sit at the lowest of Terrarium society, being relegated to working the hydroponics yards or super-factories, both of which pay little. The Dusted are also not allowed to leave the slums without special permission, typically gained via a lucky job opportunity or pilot academy scholarships.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *Poor*
>> **Attribute**: **Body**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> Two of your choice.
>
>> [!info|text-Center clear] Perk: Untouchable
>> As one of the Dusted, you are effectively invisible to people of higher classes. Most non-violent crime you commit goes unpunished due to the fact enforcers rarely want to interact with you. You can also get access to the Slums’ black markets and other hubs of non-regulated activity with ease.

> [!info|no-i]- #### Hegemony Nomad
The Nomads are a small fleet of highly powerful hedge mages that exist outside of the Circles of Magi, but still within the Hegemony jurisdiction.  You are one of these Nomads. Despite powerful magic, your lifestyle is minimalistic and poor, and your people's perceptions by the general populous does not help either.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *Poor*
>>**Attribute**: **Potential**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> - [[Meta-Magic]]
>
>> [!info|text-Center clear] Perk: Wanderer Arcana
>> You begin as an Expert in Meta-Magic, and you gain aptitude in it if you do not otherwise have it. Additionally, you can change your Meta-Magic spell-forms when you prepare your spells each day.  
### Moderate Histories
> [!info|no-i]- #### Wrench Monkey
You sit at the heart of the economy: the working class. You repair, destroy, or otherwise work on vehicles, of which the kind has little bearing. This knowledge is practical, and while hard work, wrench monkeys never run out of work.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *Moderate*
>>**Attribute**: **Power**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> [[Mundocraft]] *or* [[Artifice]]
>>> *…and*
>>> One Power Skill
>
>> [!info|text-Center clear] Perk: Well-Stocked Workshop
>> You have access to a suite of tools that you can use at any time. You can use these tools to craft, maintain and work on nearly any mechanical weapon, armor, or vehicle (other than Metals.)

> [!info|no-i]- #### Rapscallion
Lowest of the low, you are comfortable in the Terrarium’s worst streets and deepest alleys. You partake in illicit, unscrupulous activities consistently, and prefer to work alone. Despite your poor company and worse smell, you can maintain a decent living.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *Moderate*
>>**Attribute**: **Reflex**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> One **Reflex** Skill
>>> *…and*
>>> One **Tenacity** Skill
>
>> [!info|text-Center clear] Perk: Night of Debauchery
>> You can find a place to partake in hedonism anywhere you go. When exploring, you can spend 4 hours finding a local red light district or otherwise place of illicit activity.
### High Histories
> [!info|no-i]- #### Corpo Deskie
You work for one of the six mega-corporations that own and control 95 % of the Terrarium.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *High*
>>**Attribute**: **Mind**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> Two Mind Skills.
>>> *…or*
>>> One Power Skill *and* One Tenacity Skill.
>
>> [!info|text-Center clear] Perk: Ready-Access Loans
>> You can take out a company loan at nearly any time. These loans can be used to procure most standard equipment that doesn't have a rarity trait. Typically, these loans are repaid in favors to your higher-ups, not money. Your starting credits is one of these such loans.

> [!info|no-i]- #### Influencer
Whether it be from musical talent, video essays, or an All_Your_Fans, you sit at the height of a media community cultivated by your own hand. You maintain a wealthy, comfortable lifestyle in the Terrarium, but also live at the mercy of trends and your fanbase. After all, without them you are *nothing*.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *High*
>>**Attribute**: **Tenacity**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> One Tenacity Skill.
>>> *…and*
>>> One Mind Skill *or* One Body Skill.
>
>> [!info|text-Center clear] Perk: Adoring Fans
>> You can use your fans for small tasks that require little physical action. When exploring or during downtime, you can implore your fanbase to attempt to locate a person, location, or other information accessible via the Hypranet. This information cannot be classified, though it can be otherwise kept secret. There is a chance of failure, however, and using this perk, regardless of success, requires you to take a week of downtime to produce content to keep your fanbase happy.
### Extreme Histories
> [!info|no-i]- #### Politologist
You are a Politologist, a scholar-philosopher who sits at the nexus of the Hegemony's long history of both Politics and Science. You have studied these things deeply, and now you are a leader within your community who must justify their politics with science.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *Extreme*
>>**Attribute**: **Mind**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> [[Diplomacy]] *or* [[Deception]].
>>> *…and*
>>> One Mind Skill.
>
>> [!info|text-Center clear] Perk: Impromptu Speech
>> In times of stress or peril, you can rally the people and inspire your allies with a powerful, Impromptu speech. When you use this ability, you can make a request of a large crowd using a Tenacity skill of the GM's choice. Any ally that hears this speech gains 1dE temporary Health, which is doubled on a critical success.

> [!info|no-i]- #### Noble
You come from the height of luxury in the Terrarium, living in the Upper Epitaph or Outer Shells. You might be from a family of career pilots, training from birth to be the best the Terrarium has to offer, or you might be from one of the Black Houses, brought up with an education comparable to no other.
>>[!info| clear no-i] Mechanics
>>**Wealth**: *Extreme*
>>**Attribute**: **Tenacity**
>>> [!metadata|text-Center c-p-sm] Skill Proficiencies
>>> Two Mind Skills.
>
>> [!info|text-Center clear] Perk: Namedrop
>> You can drop your last name in conversations with people of high class, such as merchants who specialize in high-value products, in order to get special access to “in-the-back” inventory, invites to social events, and even audiences with people of utmost importance.

## 4. *School of Arcana*
Now that you have decided what your character did before becoming a Mage Pilot, you are faced with yet another question.

*How do you wield the arcane?*

The answer to this question is the methodology of magic your pilot chose to specialize in when they were training to become a Mage-Pilot. Divided into Schools, these orders of magic represent deep philosophical ideas about reality and magic, as well as their preferred method for blowing up bad guys.

Pick from one of the following School of Arcana, then select one of the two available Paths offered by your chosen School. You become Trained in your School, and gain the first Perk of your chosen Path.

After your selections, ensure you denote your School’s Attribute Boost and any starting gear. Take this time to inscribe your starting spells in your Grimoire as well. 
### Aerophasia
Aeromancers are the masters of mobility and ranged combat, slinging arrows and dashing around on the screaming squails of the torrential winds.
#### Starting Equipment
You begin play with the following equipment:
- Catalyst: A bright green leaf that seems to billow on its own. It flies away if held by anyone else.
- Grimoire: A thin journal with a feather quill that never needs ink. Only you can open the journal.
- Resonator: A arrowhead with feathers attached, bound to a necklace.
- - -
>[!info] ### Mechanics
>**Sphere:** Elemancy
> **Attribute Boost:** **Reflex**
> **Starting Spell:** [[Aerostrike]]

##### When you select  this School,  select  a  Path. 

>[!column]- ***Path of the Valliant Zephyr*** 
>> [!metadata] *Trained Perk: Zephyr's Winds*
>> *When you become Trained in this School, you gain the following benefits.*
>> Any time a spell with the [[Air]] trait allows you to move as apart of casting it, you can move an additional 2 spaces and you do not trigger reactions during that movement.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>> ***Coming Soon…***
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>>***Coming Soon…***
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this School, you gain the following benefits.*
>>***Coming Soon…***

*…or*

>[!column]- ***Path of the Wind Dancer*** 
>> [!metadata] *Trained Perk: Windborn Cutter*
>>*When you become Trained in this School, you gain the following benefits.*
>>You gain a +2 bonus to damage with [[Air]] spells each time you move as a part of an Air spell. This bonus caps at +4, and you lose it if you move by other means.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>> ***Coming Soon…***
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>>***Coming Soon…***
>
>> [!metadata] *Legendary Perk:*
>> *When you become a Legend in this School, you gain the following benefits.*
>> ***Coming Soon…***
### Hydrophasia
The most spiritual of the Elemancy schools, hydromancers flow from state to state, using frozen ice as well as scalding steam to bring calamity.
#### Starting Equipment
You begin play with the following equipment:
- Catalyst: A wristband with bright blue water in it, which changes states with your spells. It melts in anyone else’s hands, reforming around your wrist.
- Grimoire: A water-proof scroll that wraps around your forearm. Its text washes off when held by anyone else, soaking them in the process.
- Resonator: A chunk of permafrost bound to a necklace.
- - -
>[!info] #### Mechanics
>**Sphere:** Elemancy
> **Attribute Boost:** **Potential**
> **Starting Spell:** [[Steam-Spike]]

#### When you select  this School,  select  a  Path. 

>[!column]- ***Path of the All-Consuming Tsunami*** 
>> [!metadata] *Trained Perk: Tsunami's Deluge*
>> *When you become Trained in this School, you gain the following benefits.*
>> Your Hydrophasia is powerful, but draining. Treat all damage rolls of a 1 as a 2 for Hydrophasia spells, but increase their mana cost as if it was a spell level higher.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this School, you gain the following benefits.*

*…or*

>[!column]- ***Path of the Ever-Shifting Tide*** 
>> [!metadata] *Trained Perk: Even Flow, Constant Change.*
>>*When you become Trained in this School, you gain the following benefits.*
>>You are a master at changing the flow and state of water. Each time you alternate Ice and Steam modes of your Hydrophasia spells, you gain a +1 *cumulative* magical bonus to attacks and Spell-Work, which caps out at +4. If you take damage or use the same mode twice, you lose this bonus immediately.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>> *When you become a Legend in this School, you gain the following benefits.*
### Pyrophasia
Harnessing the power of wicked flame, practitioners of this school, typically known as *pyromancers,* bring immolation through desolate flame. Despite this wanton destruction, their flames can give new life the chance to rise.
#### Starting Equipment
You begin play with the following equipment:
- Catalyst: A palm lighter, with an important name engraved on it. It is too hot for anyone else to hold.
- Grimoire: A matchbook that always seems to have matches. Each stick is rune-scribed with with spells. It always seems to find its way into your pocket.
- Resonator: A small piece of black-charred wood that always seems to smolder. This flame does not cause harm or spread. It is affixed to a small necklace.
- - -
>[!info] #### Mechanics
>**Sphere:** Elemancy 
> **Attribute Boost:** **Power**
> **Starting Spell:** [[Ignition]]

#### When you select  this School,  select  a  Path. 

>[!column]- ***Path of the White Phoenix Down*** 
>> [!metadata] *Trained Perk: Healing Downflame*
>> *When you become Trained in this School, you gain the following benefits.*
>> You can cast any spell with the [[Fire]] trait on an ally to heal them for the damage normally dealt. If they are Immune to fire damage, your healing has no effect. Spells cast this way gain the [[Healing]] trait.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this School, you gain the following benefits.*

*…or*

>[!column]- ***Path of the Flaming Lion Emperor*** 
>> [!metadata] *Trained Perk: Emperor's Pyretics*
>>*When you become Trained in this School, you gain the following benefits.*
>>You are Immune to Fire damage, and can use [[Ignition]] to set yourself aflame, giving you the [[Ignited]] condition. While on fire, your Pyrophasia spells always gain their ***Immolation*** effect (even if you don’t meet the trigger) and cost additional mana as if they were two Ranks higher.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>> *When you become a Legend in this School, you gain the following benefits.*
### Terraphasia
With stubbornness and unyielding loyalty, Terramancers are stalwart warriors who forge weapons and armor from the earth below them.
#### Starting Equipment
You begin play with the following equipment:
- Catalyst: A set of six stone arm rings, which fit only your arms.
- Grimoire: A stone tablet, which has been enchanted to never leave your side.
- Resonator: A worked, polished, and cut gem or mineral, attached to a necklace.
- - -
>[!info] #### Mechanics
>**Sphere:** Elemancy
> **Attribute Boost:** **Body**
> **Starting Spell:** [[Earthen Armor]]

#### When you select  this School,  select  a  Path. 

>[!column]- ***Path of the Tectonic Bastion*** 
>> [!metadata] *Trained Perk: Shifting Plates*
>> *When you become Trained in this School, you gain the following benefits.*
>> Whenever you Cast or Dispel a Spell with the [[Defensive]] trait, you can use a reaction to Move up to your Speed, ignoring penalties from the spell.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this School, you gain the following benefits.*

*…or*

>[!column]- ***Path of Crystal Watchtower*** 
>> [!metadata] *Trained Perk: Crystallomancy*
>>*When you become Trained in this School, you gain the following benefits.*
>>Your Terraphasia spells manifest crystals instead of earthen stone. Any  spell you cast with the [[Earth]] trait can deal cutting damage instead of crushing, and you reduce any Speed penalty from those spells by 5. You also gain access to [[Uncommon]] spells with the [[Crystal]] trait.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>> *When you become a Legend in this School, you gain the following benefits.*
### Technosophy 
Technomancers have a special relationship with the Metals; instead of seeing them as resonators for magical power, they view them as extensions of the self. Most technomancers augment their bodies with cybernetics and magitech in order to feel closer to their Metals.
#### Starting Equipment.
You begin play with the following equipment:
- Catalyst: A [[PiC-Mi]] (Personally-Integrated Computer Machine Interface)
- Grimoire: A copy of [[Cybermagistic Solution's Grim-Ware]] software.
- Resonator: One cybernetic enhancement.
- - -
>[!info] ####  Mechanics
>**Sphere:** Technomynism
> **Attribute Boost:** **Mind**
> **Starting Spell:** [[Techno-Babble]]

#### When you select  this School,  select  a  Path. 

>[!column]- ***Path of the Technosorcerer*** 
>> [!metadata] *Trained Perk: Sp3ll_C0d1ng*
>> *When you become Trained in this School, you gain the following benefits.*
>> Once per hour, you can attempt to code a new spell on-the-fly as a free action. Pick one spell you have access to but do not have in your grimoire. Roll a **Spell-Works** check, with a penalty equal to the spell’s Rank. On a success, you can cast the spell. On a failure, you suffer feedback, and cannot cast a spell for a round.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this School, you gain the following benefits.*

*…or*

>[!column]- ***Path of the Biotechnician*** 
>> [!metadata] *Trained Perk: Bionic Integration*
>>*When you become Trained in this School, you gain the following benefits.*
>>You can directly integrate computer technology into your body. Your PiC-Mi is directly integrated into your brain (and as such, loses the [[Upgrade]] trait), and you can use any cybernetic or bio-tech enhancement as a catalyst.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>> *When you become a Legend in this School, you gain the following benefits.*
### Runeurgy
Sometimes called scribes, runeurgists are masterful practitioners of the most basic component of spell-work: language. Magic is a language a Mage speaks with the universe, and runeurgists are exceptionally fluent. 
#### Starting Equipment.
You begin play with the following equipment:
- Catalyst: A large writing utensil with your name etched across it. It never seems to run out of ink.  
- Grimoire: A tome who's pages are blank to anyone other than you. Only your catalyst can inscribe within it.
- Resonator: A vial of pitch-black ink, strung on a necklace. 
- - -
>[!info] #### Mechanics
>**Sphere:** Artifacteomancy
> **Attribute Boost:** **Tenacity**
> **Starting Spell:** [[Power-Word 'Harm']]

#### When you select  this School,  select  a  Path. 

>[!column]- ***Path of the Rune-Scribed*** 
>> [!metadata] *Trained Perk: Bound in Ink*
>> *When you become Trained in this School, you gain the following benefits.*
>> You can cast spells by drawing their spoken components in ink instead. Any spell you cast with the [[Vocal]] trait is cast as if affected by the *Silent Spell* spell-shape, but this is *not* a spell-shaping effect. Additionally, your grimoire is the canvas of your skin; any spell you learn becomes tattooed onto your skin, and your prepared spells' tattoos glow with a faint ebb and glow. 
>
>> [!metadata] *Expertise Perk: Ink Duelist*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk: Ink-Wrought Soul*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk: Power Word-'Creation'*
>>*When you become a Legend in this School, you gain the following benefits.*

*…or*

>[!column]- ***Path of the Word-Caller*** 
>> [!metadata] *Trained Perk: Word-Shaper*
>>*When you become Trained in this School, you gain the following benefits.*
>> You can freely shape the spellform of your Power Words. Any spell you cast with the [[Vocal]] trait can have an additional spell-shape applied to it (for a total of two, or three if you are Legendary in [[Meta-Magic]].) This increases by another additional spell-shape each time you gain a training level in this School.
>
>> [!metadata] *Expertise Perk: Word-Speaker*
>> *When you become an Expert in this School, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk: Word-Weaver*
>>*When you become a Master in this School, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk: Power Word-'Obliteration'*
>> *When you become a Legend in this School, you gain the following benefits.*

## 5. *Pilot Role*
After making a selection as to the style of magic you wield, you are now posed with a final question:

*What role do you fill within a squad?*

The answer to this question is your *Pilot Role*. This is simply what *you do* on the battlefield, in and out of the Metal. The classical idea of the “tank”, “support” and “DPS” are all determined by this choice.

Select a Pilot Role from the following options, then select one of the two Role Specializations offered by the chosen Role. You then become Trained in your Role.

Denote any proficiencies granted by your Role, and then denote the skills granted by your Role and Specialization. You *do not* gain aptitude in them. Finally, inscribe your Specialization’s starting Spell in your Grimoire. 
### Battlefield Support
Supports use buffs and healing to help allies survive the battle, as well as deal more damage. 
- - -
>[!info] #### Role Mechanics
> **Attribute Boost:** Any
> **Armor Proficiency :** Infiltrator (Trained)
> **Weapon Proficiency:** Simple Ranged (Expert)
> **Role Skill:** [[Arcanology]]

#### When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization: Medic*** 
>>[!info] #### Mechanics
>Medical Supports specialize in healing and repair on the battlefield. 
> **Specialty Skill:** [[Medicine]]
> **Starting Spell:** [[Patch-Up]]
> 
>> [!metadata] *Trained Perk: Resplendent Life*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain a +3 magical bonus to healing you do to allies who are [[Bloodied]]. Additionally, you can pay for up to half of an ally's spell's mana cost. Doing so costs your reaction. 
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

*…or*

>[!column]+ ***Role Specialization: Barricader*** 
>>[!info|left] #### Mechanics
>>Barricadier Supports generate cover and utilize perfect positioning to create advantageous situations for their allies.  
> **Specialty Skill:** [[Mundocraft]]
> **Starting Spell:** [[Eunard's Portable Cover]]
> 
>> [!metadata] *Trained Perk: Reinforced Constructs*
>> *When you become Trained in this Role, you gain the following benefits.*
>> Constructs you create (such as via spells with the [[Construct]] trait) gain a +2 bonus to Toughness and cannot be pierced. Additionally, you can pay for up to half of an ally's spell's mana cost. Doing so costs your reaction. 
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*


### Frontline Vanguard
The Vanguards take to the frontlines, using their extreme defenses to tank damage, make distance, and create chances for their allies.
- - -
>[!info] #### Role Mechanics
> **Attribute Boost:** **Body**
> **Armor Proficiency :** Powered (Expert)
> **Weapon Proficiency:** Simple Melee (Trained)
> **Role Skill:** [[Athletics]]

#### When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : Bastion*** 
>>[!info] #### Mechanics
>Bastions are the living shield of their groups, using massive armor and powerful shields to stop damage before it ever has the chance to wound them and their allies. 
> **Specialty Skill:** [[Intimidation]]
> **Starting Spell:** [[Shield Crush]]
> 
>> [!metadata] *Trained Perk: Living Shield*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain resistance to physical damage. Additionally, you roll with favor against any check that would move you by force with favor.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

*…or*

>[!column]+ ***Role Specialization: Juggernaut***
>>[!info|left] #### Mechanics
>Juggernauts are beacons of light in the dark of the battlefield; using powerful war-cries, these front-liners burn their own life to stoke the fires of their allies. 
> **Specialty Skill:** [[Athletics]]
> **Starting Spell:** [[Blood Cry]]
> 
>> [!metadata] *Trained Perk: Unyielding*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain an additional 5 Health at character creation, and any time you would increase your max Health, you gain an additional +3 Health. Additionally, you roll with favor against any check that would move you by force.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

### Guerilla Tactics 
Guerilla Specialists gather information, scout out battles, and recon for potential hostiles. Boasting good mobility, as well as evasion, Guerillas stay out of the fray to take others out with speed.
- - -
>[!info] #### Role Mechanics
> **Attribute Boost:** **Power**
> **Armor Proficiency :** Mobile (Trained)
> **Weapon Proficiency:**  Martial Ranged (Trained) *and* Simple Melee (Trained)
> **Role Skill:** [[Survivalism]]

#### When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : Scout*** 
>>[!info] #### Mechanics
>Scouts get ahead of their allies, using information gathered from the shadows to help them line up the perfect ambush.
> **Specialty Skill:** [[Survivalism]]
>>
> **Starting Spell:** [[Retrace]]
>  
>> [!metadata] *Trained Perk: Scouting Communications*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You can double the range of any spell you cast with the [[Communication]] trait. Additionally, whenever you reduce a foes to 0 Health, you heal for a number of Health equal to your level.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

*…or*

>[!column]+ ***Role Specialization : Hunter*** 
>>[!info|left] #### Mechanics
>Hunters slink through the edge of the tree-line, taking out key targets with speed before the main engagement begins.
> **Specialty Skill:** [[Sneakery]]
>> 
> **Starting Spell:** [[Predator's Sight]]
> 
>> [!metadata] *Trained Perk: Predation*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You gain a +2 Space bonus to reach with any melee attack, as long you would lose the [[Hidden]] condition as apart of that attack. Additionally, whenever you reduce a foes to 0 Health, you heal for a number of Health equal to your level.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

### Logistical Controller 
Logistical Controllers do just that: control the pace of the battle, lest it be by locking down key points or locking foes out of their most powerful abilities.
- - -
>[!info] #### Role Mechanics
> **Attribute Boost:** **Mind**
> **Armor Proficiency :** Mobile (Trained)
> **Weapon Proficiency:** Martial Melee (Expert)
> **Role Skill:** [[Meta-Magic]]

#### When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : Engineer*** 
>>[!info] #### Mechanics 
>Engineer Controllers create minions and other constructs to control the pace of encounters.
> **Specialty Skill:** [[Artifice]]
> **Starting Spell:** [[Auto-Shot Turret]]
> 
>> [!metadata] *Trained Perk: Construct Spell-Origination Disjunction*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You can treat Constructs you summon as the origin point of spells you cast for the purposes of range and line of sight. Additionally, allies within 12 spaces of you gain a +1 magical bonus to Move, while enemies suffer a -1 magical penalty to Move.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

*…or*

>[!column]+ ***Role Specialization : Disruptor*** 
>>[!info|left]  #### Mechanics
>Disruptor Controllers attack the enemies directly in order to lock them out of their most powerful abilities. 
> **Specialty Skill:** [[Meta-Magic]]
> **Starting Spell:** [[Arc Surge]]
> 
>> [!metadata] *Trained Perk: Electro-Neural Dissipation*
>> *When you become Trained in this Role, you gain the following benefits.*
>> Shocked enemies have a -2 to rolls against any of your spells or effects that require a **Mind** check. Additionally, allies within 12 spaces of you gain a +1 magical bonus to Move, while enemies suffer a -1 magical penalty to Move.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

### Long-Range Ordinance
Those in the Long-Range Ordinance role act as the heavy firepower of their team, either shutting down key chokes or unleashing devastating damage with high-powered weaponry. While powerful, they are nearly defenseless due to the amount of accommodation needed for such extreme firepower.
- - -
>[!info] #### Mechanics
> **Attribute Boost:** **Reflex**
> **Armor Proficiency :** Infiltrator (Trained)
> **Weapon Proficiency:** Advanced Ranged (Trained)
> **Role Skill:** [[Sneakery]]

#### When you select  this Role,  select  a  Specialization. 
>[!column]+ ***Role Specialization : Sniper*** 
>>[!info] ##### Mechanics
> Snipers are single-target annihilators; they hide and wait, allowing their teammates to set up the perfect kill-shot.
> **Specialty Skill:** [[Sneakery]]
> **Starting Spell:** [[Sniper's Mark]]
> 
>> [!metadata] *Trained Perk: Critical Reload*
>> *When you become Trained in this Role, you gain the following benefits.*
>> Whenever you score a critical hit with a weapon you are trained in, you can reload that weapon as a free action. If it has any heat accumulated, you vent it off as part of this reload. Additionally, you ignore up to -4 in range penalties.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*

*…or*

>[!column]+ ***Role Specialization : Heavy Artillery*** 
>>[!info|left] ##### Mechanics
> Artillerists deliver high-yield payloads of powerful explosive magic and area-denying weaponry. If you need a chokepoint held, these are the pilots for you.
> **Specialty Skill:** [[Acrobatics]]
> **Starting Spell:** [[Cedrik's Mini-Many-Minefield]]
> 
>> [!metadata] *Trained Perk: Delayed Payload Delivery*
>> *When you become Trained in this Role, you gain the following benefits.*
>> You can choose to delay the detonation of any spell or weapon you use with the [[Area]] trait by one round. When delayed this way, it deals an additional die of damage when it does detonate. Additionally, you ignore up to -4 in range penalties.
>
>> [!metadata] *Expertise Perk:*
>> *When you become an Expert in this Role, you gain the following benefits.*
>
>> [!metadata] *Masterful Perk:*
>>*When you become a Master in this Rolel, you gain the following benefits.*
>
>> [!metadata] *Legendary Perk:*
>>*When you become a Legend in this Role, you gain the following benefits.*]

## 6. *Finalizing Attributes and Statistics*
Now that your four core selections have been made, its time to finalize your Attributes. Assign 12 free Attribute points across your Attributes. You cannot begin play with an Attribute above 20.

Once you have assigned all 12 points, take this time to calculate your Statistics (if you aren’t using the *free digital character sheet*. Which, you should be. I worked really hard on it.)

## 7. *Finalizing Skills and Proficiencies*
After your Attributes and Statistics are finalized, you are ready to finalize your Skills and Proficiencies. 
### **Skills**
Designate a number of Skill Aptitudes as determined by your Skill Aptitudes Statistic, then select one Skill you are Trained in and have Aptitude with. You begin play as an Expert in that Skill.
> [!info|right ws-med txt-left ttl-c] *Skills and Aptitude*
> In `=[[Dev Helpers]].game-short`, skills are essential to all characters. They can be found in Appendix D: Skill List. More information is found in the *Finalizing Skills* section of character creation.
### **Proficiencies**
Proficiencies are similar to statistics, in that they are tied directly to an attribute (typically to meet requirements), but they are tracked with training levels instead of numeric values. Each new training level in a proficiency also gains the player character a new Perk associated with that proficiency. 
#### **Weapon and Armor Proficiencies**
Select one Armor proficiency and one Weapon proficiency to increase your training level with by one step (untrained to Trained or Trained to Expert.) You cannot begin play with an Armor or Weapon proficiency at or above Mastered.
##### *Weaponry*
>[!column]- ### **Simple  Ranged Weapons**
>> [!note] #### *Description*
>> **Key Attribute: Reflex**
>
>> [!metadata|right] *Trained Perk: Simple Ranged Weapon Specialty* 
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> Pick one Ranged Weapon Group. Simple Weapons you wield that belong to that group gain its listed Specialty trait. 
>
>> [!metadata|right] *Expertise Perk: Power In Simplicity*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> Increase the damage die size of Simple Ranged weapons you wield by one step. 
>
>> [!metadata|right] *Masterful Perk: Fast Loader*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>> You take one less action to reload Simple Ranged weapons you wield, and two less actions to reload weapons that belong to your Simple Ranged Weapon Specialty. 
>
>> [!metadata|right] *Legendary Perk: Better Critical*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> Extend the critical range of weapons you wield that belong to your Simple Ranged Weapon Specialty by 1 (typically to 6 and lower.)

>[!column]- ### **Martial  Ranged Weapons**
>> [!note] #### *Description*
>> **Key Attribute: Reflex**
>
>> [!metadata|right] *Trained Perk: Martial Ranged Weapon Specialty*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> Pick one Ranged Weapon Group. Martial Weapons you wield that belong to that group gain its listed Specialty trait
>
>> [!metadata|right] *Expertise Perk: Spell and Bullet*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> Whenever you attack with a weapon that belongs to your Martial Ranged Weapon Specialty, if you casted a spell this turn, that attack deals an extra die of **channeled** damage.
>
>> [!metadata|right] *Masterful Perk: Close-Quarters Gunplay*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>> You ignore penalties to using Martial Ranged weapons within Engagement range.
>
>> [!metadata|right] *Legendary Perk: Martial Prowess*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> Increase the damage die size of Martial Ranged weapons you wield by one step.

>[!column]- ### **Advanced  Ranged Weapons**
>> [!note] #### *Description*
>> **Key Attribute: Reflex**
>
>> [!metadata|right] *Trained Perk: Advanced Ranged Weapon Specialty*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> Pick one Ranged Weapon Group. Advanced Weapons you wield that belong to that group gain its listed Specialty trait.
>
>> [!metadata|right] *Expertise Perk: Fast Loader*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> You take one less action to reload Advanced Ranged weapons you wield, and two less actions to reload weapons that belong to your Advanced Ranged Weapon Specialty.
>
>> [!metadata|right] *Masterful Perk: Sharpshot*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>> You ignore up to -2 in Range penalties when making ranged attacks with weapons you wield that belong to your Advanced Ranged Weapon Specialty. This is cumulative with other such effects, such as the **Perception** perk ‘Viewfinder’.
>
>> [!metadata|right] *Legendary Perk: Brutal Critical*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> Extend the critical range of weapons you wield that belong to your Advanced Ranged Weapon Specialty by 1 (typically to 6 and lower.) Additionally, when you roll a critical hit on an attack with such a weapon, multiply the damage by 3, instead of 2. 

>[!column]- ### **Simple Melee Weapons**
>> [!note] #### *Description*
>> **Key Attribute: Power**
>
>> [!metadata|right] *Trained Perk: Simple Melee Weapon Specialty*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> Pick one Melee Weapon Group. Simple Weapons you wield that belong to that group gain its listed Specialty trait.
>
>> [!metadata|right] *Expertise Perk: Power in Simplicity*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> Increase the damage die size of Simple Melee weapons you wield by one step.
>
>> [!metadata|right] *Masterful Perk: Brutality*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>> Increase the critical damage multiplier for weapons you wield that belong to your Simple Melee Weapon Specialty to 3.
>
>> [!metadata|right] *Legendary Perk: Onslaught*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> Weapons you wield that belong to your Simple Melee Weapon Specialty gain [[Flurry\|Flurry 1]]. This is additive with any Flurry it already has. 

>[!column]- ### **Martial Melee Weapons**
>> [!note] #### *Description*
>> **Key Attribute: Power**
>
>> [!metadata|right] *Trained Perk: Martial Melee Weapon Specialty*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> Pick one Melee Weapon Group. Martial Weapons you wield that belong to that group gain its listed Specialty trait.
>
>> [!metadata|right] *Expertise Perk: Gun and Blade*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> Whenever you attack with a weapon that belongs to your Martial Melee Weapon Specialty, if you attacked with a Ranged weapon this turn, that attack gains a +3 circumstance bonus. 
>
>> [!metadata|right] *Masterful Perk: Sword and Sorcery*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>> Whenever you attack with a weapon that belongs to your Martial Melee Weapon Specialty, if you casted a spell this turn, that attack deals an extra die of **channeled** damage.
>
>> [!metadata|right] *Legendary Perk: Martial Prowess.*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> Increase the damage die size of Martial Melee weapons you wield by one step. 

>[!column]- ### **Advanced Melee Weapons**
>> [!note] #### *Description*
>> **Key Attribute: Power**
>
>> [!metadata|right] *Trained Perk: Advanced Melee Weapon Specialty*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> Pick one Melee Weapon Group. Advanced Weapons you wield that belong to that group gain its listed Specialty trait.
>
>> [!metadata|right] *Expertise Perk: Brutal Critical*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> Extend the critical range of weapons you wield that belong to your Advanced Melee Weapon Specialty by 1 (typically to 6 and lower.) Additionally, when you roll a critical hit on an attack with such a weapon, multiply the damage by 3, instead of 2. 
>
>> [!metadata|right] *Masterful Perk: Devastating Blow*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>>  Weapons you wield that belong to your Advanced Melee Weapon Specialty gain the [[Devastating]] and [[Critical\|Critical dX]] traits. X is one step higher than the weapon’s damage die.
>
>> [!metadata|right] *Legendary Perk: Relentless Stance* `=[[Dev Helpers]].one-action`
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> [[Stance]]
>> - - -
>>  While you are in this stance, you make all attacks with Advanced Melee Specialty weapons with favor. All attacks are made against you with favor. While you are Relentless, you cannot Dodge or Block.
>

##### *Armor*
![[Character Mechanics Overview#^059684]]
![[Character Mechanics Overview#^85f3b3]]
![[Character Mechanics Overview#^83a377]]

#### **General Proficiencies**
From among **Perception**, **Piloting** and **Spell-Work**, pick two to begin play at Trained and one to begin play at Expert.
>[!column]- ### **Perception**
>> [!note] #### *Description*
>> Perception is how well a character is trained at spotting subtle details, as well as a measure of reaction speed.
>> **Key Attribute: Mind**
>
>> [!metadata|right] *Trained Perk: Thorough Searcher*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> You take your time to ensure you find everything. When you Search or Scan a location, you can elect to take twice the amount of time to do so. If you do, you gain a +3 circumstance bonus to **Perception** checks made as a part of those actions.
>
>> [!metadata|right] *Expertise Perk: Viewfinder*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> You ignore -2 in range penalties when making Ranged weapon attacks. This increases to -4 when you become a Master in **Perception**.
>
>> [!metadata|right] *Masterful Perk: Scouting*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>> Whenever you **Scout**, you grant allies a +3 circumstance bonus to initiative instead of a +1.  
>
>> [!metadata|right] *Legendary Perk: All-Seeing Eyes*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> You make checks to see through illusions and other falsehoods with favor. 

>[!column]- ### **Piloting**
>> [!note] #### *Description*
>> Piloting is arguably the most important proficiency in *Metal*. All PCs, and nearly all NPCs will have it to at least some degree of it. It is a measure of a pilot's skill, but it also a measure of how well-connected to their Metal they are.
>> **Key Attribute: Reflex+Potential**
>
>> [!metadata|right] *Trained Perk: Stunt Pilot*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> 
>> You can now use Novice piloting maneuvers you have access to.
>
>> [!metadata|right] *Expertise Perk: Hot-Shot Pilot*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> 
>> You can now use Expert piloting maneuvers you have access to.
>> 
>> Whenever you critically fail a **Piloting** check, you can spend a Luck point to instead succeed. If you do, you make your next **Piloting** check without favor. 
>
>> [!metadata|right] *Masterful Perk: Ace Pilot*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>>
>> You can now use Master piloting maneuvers you have access to.
>> 
>
>> [!metadata|right] *Legendary Perk: Perfect Pilot*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> 
>> You can now use Legendary piloting maneuvers you have access to.
>> 
>> You cannot fail (but you can still *critically fail*) **Piloting** checks.
>

>[!column]- ### **Spell-Work**
>> [!note] #### *Description*
>> Spell-Work is just a fancy way to say "casting," specifically spells that are *not* cantrips. When outside of a Metal, a Mage must make a Spell-Work roll to cast a spell, and when in their Metal, they typically roll Spell Working to cast a spell when severely damaged or out of mana. 
>> **Key Attribute: Mind+Poential**
>
>> [!metadata|right] *Trained Perk: Magician*
>> *When you become Trained in this Proficiency, you gain the following benefits.*
>> Spells you cast of Rank 1 or lower cost half as much mana. When you increase your Spell-Work training level, the Rank of spells effected increases by 1. 
>
>> [!metadata|right] *Expertise Perk: Magus*
>> *When you become an Expert in this Proficiency, you gain the following benefits.*
>> Your spells are harder to resist. Creatures rolling to resist the effects of a spell you cast suffer a difficulty penalty equal to your Tier.
>
>> [!metadata|right] *Masterful Perk: Wizard*
>>*When you become a Master in this Proficiency, you gain the following benefits.*
>> Increase the damage die size of spells you cast that are Rank 3 or lower. 
>
>> [!metadata|right] *Legendary Perk: Archmage*
>> *When you become a Legend in this Proficiency, you gain the following benefits.*
>> You treat all spells as if they were two Ranks lower. If this would reduce a spell to below Rank 0, it becomes Rank 0 instead.
>
## 8. *Creating a Grimoire*
After all of your mechanical selections, you can move on to creating your *Grimoire*, which is a catalog of all the spells your Mage can cast. These are the guidelines for creating your Grimoire:
1. At Tier 1, your Grimoire can contain Rank 0-3 spells.
2. Your Grimoire can contain a number of spells equal to your Tier * 10 (which is 10.)
3. You have access to any spell on a spell list that either does not have an access requirement or you meet the requirement for. Spells can be found in [[Character Creation Playtest 1 Packet#Appendix C Spell Lists|Appendix C Spell Lists]]

## 9. *Selecting Perks*
Each character in `=[[Dev Helpers]].game-short` has (a) quirk(s) that helps set them apart from other characters. These quirks are known as *General Perks*. Select one for your Mage Pilot.
### Perks 
> [!info|n-th no-i]- #### Battlemage
> ##### Mechanics
> | | |
> |:---:|:---:|
> |**Tier:** | 1  |
> | **Type:** | General  |
> | **Requirements:** |*Expert in a Melee weaponry proficiency* |
> #### Details:
> You can use any melee weapons as a spellcasting catalyst, including conjured ones. Additionally, any spell you cast that would conjure a weapon no longer requires a catalyst or material, and gains the [[Flash]] trait.

> [!info|n-th no-i]- #### Jack of All Trades
> ##### Information
> | | |
> |:---:|:---:|
> |**Tier:** | 1  |
> | **Type:** | General  |
> | **Requirements:** | *Mind 14+* |
> #### Details:
> You gain a +4 fortune bonus to skills you are not trained in, but roll those skills without favor.

> [!info|n-th no-i]- ####  Lifebringer
> ##### Information
> | | |
> |:---:|:---:|
> |**Tier:** | 1  |
> | **Type:** | General  |
> | **Requirements:** | *Your Grimoire contains three or less spells that deal damage.* |
> #### Details:
> Increase the die size of all healing from spells you cast by one step. Decrease the die size of all damage you deal from spells you cast by two steps (If this would bring the die size to a d2 or lower, it deals no damage instead.)

> [!info|n-th no-i]- #### Novice Blood Mage 
> ##### Information
> | | |
> |:---:|:---:|
> |**Tier:** | 1  |
> | **Type:** | General  |
> | **Requirements:** | *Either the Hemaphoresis School, or;  Your Grimoire contains at least five spells with the [[Life-Bound]] trait.*|
> #### Details:
> You can no longer cast [[Life-Bound]] spells using Mana, but you gain Resistance to the damage you take from casting spells. Like normal, your Toughness does not apply to this damage and you cannot reduce it by other means (unless otherwise stated.)

> [!info|n-th no-i]- #### Robust Fortitude
> ##### Information
> | | |
> |:---:|:---:|
> |**Tier:** | 1  |
> | **Type:** | General  |
> | **Requirements:** |*Body 12+* |
> #### Details:
> You gain Resistance to two of the physical damage types or one of the energy damage types.

> [!info|n-th no-i]- #### Tome Mage
> ##### Information
> | | |
> |:---:|:---:|
> |**Tier:** | 1  |
> | **Type:** | General  |
> | **Requirements:** | *None* |
> #### Details:
> You calculate the cost of spells that belong to your School as if they were one Rank *lower* and you calculate the cost of non-School spells as if they were one Rank *higher*.

> [!info|n-th no-i]- #### Wildheart
> ##### Information
> | | |
> |:---:|:---:|
> |**Tier:** | 1  |
> | **Type:** | General  |
> | **Requirements:** | *An Elemancy or Natureomancy School* |
> #### Details:
> Increase the die size of all of your spell's damage by one step, and you treat all 1’s rolled for spell damage as 2’s. Your grimoire can only contain spells from the Elemancy and Natureomancy spheres that deal damage. Finally, you cast all spells as if they are two Ranks higher.

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
#### Attributes 
A Metal's Attributes are slightly different from a Mage's; they lack the "mental" Attributes of a Mage-Pilot (which are Mind, Potential, and Tenacity), as well as a measure of reaction speed (Reflex) due to these things being pilot-dependent. It is still the pilot in control, after all, and Metals aren't quite capable of truly acting on their own. 
##### Structure = ((Power + Body)/2)
This is the measure of the physical construction and ability of the Metal. 
Governs: Health, Toughness, and Melee Damage Bonus 
##### Engineering = ((Reflex + Tenacity)/2)
This is a measure of the quality of the design of a Metal, and this dictates how far one can push the limits of their Metal.
Governs: Heat Limit, Shields, Speed
##### Computation = ((Mind + Potential)/2)
This is the measure of the computational ability of the on-board abilities 
Governs: Systems Points (SP), Sensor Range, Ranged Accuracy Bonus
#### Statistics
Derived from their respective Attribute, different Statistics have differing formulae for calculating them. If a Stat would have a decimal, round *down.*
##### Structure 
- Health 
	- How much punishment a Metal's hull can sustain before facing Integrity failure.
	- Max Health=Structure
- Toughness 
	- A Metal's resistance to damage.
	- Structure/3
- Melee Damage Bonus 
	- A bonus to Melee damage. 
	- Structure - 15
##### Engineering
- Heat Limit 
	- How much heat the S-R<sup>2</sup> Engine can accrue before entering [[Meltdown]], and then [[Criticality]]. 
	- Max Heat: Engineering/2
- Barrier 
	- An meta-ablative barrier that further protects from damage.
	- Max Shield = Engineering * Tier
- Speed 
	- How far a Metal can move in 12 seconds. 
	- Engineering/2
##### Computation  
- Ranged Accuracy Bonus
	- A bonus to ranged *attack rolls.*
	- Computation - 15
- System Points 
	- How many systems the on-board computer can run in parallel.
	- Computation/8
- Sensor Range 
	- How many spaces the Metal's perception sensors can detect other Metals and creatures.
	- Computation
##### Unkeyed 
These are stats that do not have a keyed Attribute; they are free-standing.
- Integrity 
	- Metals do not enter a death spiral when reduced to 0 Health; instead, they mark off one Integrity and go back to full Health. When a Metal reaches 0 Integrity, it is destroyed.
## 1.  *Frame*
The *Frame* is the most basic component of the Metal, forming the foundation of which all other parts are mounted upon. It determines fundamental aspects of a Metal, such as Size, body-plan, and weapon mounts.

Select a **Frame** from the options below, then denote the Attribute bonuses, Weapon Mounts, and any Perks or Integrated Systems granted by the Frame.

### Ultralight Frames 
#### ULF-001 "Dogfighter"
The first-ever mass-production frame in the *Ultralight* weight-class, the *Dogfighter* is prized for its reliable construction and diverse mounts. 
>[!info|n-th no-i] ###### Mechanics  
|                   |                     |
|:-----------------:|:-------------------:|
|     **Size**      |    1     |
| ***Attributes***                       |
|   **Structure**   |  2  |
|  **Engineering**  | 3 |
|  **Computation**  | 2 |
| **Weapon Mounts** |   Secondary, Aux/Aux   |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Mass Production*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> Parts for this frame are available *everywhere*; When you attempt Field Repairs, you gain a +4 equipment bonus to any related checks. 
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*

#### ULF-002 "Spring-Leaf"
One of the many prototypes for the *Dogfighter*, this early iteration focused on extreme speed, though the quality of production is still notable. Its odd mounts are considered by many to be the killing factor of its design.
>[!info|n-th no-i] ###### Mechanics  
|                   |                                           |
|:-----------------:|:-----------------------------------------:|
|     **Size**      |                     1                     |
| ***Attributes***  |                                           |
|   **Structure**   |                     1                     |
|  **Engineering**  |                     4                     |
|  **Computation**  |                     2                     |
| **Weapon Mounts** | Secondary (Melee-Only), Twin Aux, Aux/Aux |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Whispers on the Winds*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> Whenever you fire an Auxiliary weapon while Engaged, you can move up to half your Speed as part of that action. 
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
### Light Frames 
#### LF-001 "Side-Winder"
Super-Massive Robotic’s premier Light Frame is the Side Winder. The Side Winder was the first SMR frame designed to utilize the highly experimental Laminar-Momtion Drive to aid in near perpetual motion. This frame sacrifices Structure in order to support its higher speed and systems capacity.
>[!info|n-th no-i] ###### Mechanics  
|                   |                     |
|:-----------------:|:-------------------:|
|     **Size**      |    1     |
| ***Attributes***  |                     |
|   **Structure**   |  1  |
|  **Engineering**  | 3 |
|  **Computation**  | 3 |
| **Weapon Mounts** | Twin Secondary/Aux      |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Repetitive-Motion Stress-Dissipation*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> As long as you are not Engaged, you can ignore the penalty incurred by repeated [[Dodge#^8b0f15\|Evade]] attempts.
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
#### LF-002 "Shadow-Stalker"
The *Shadow-Stalker* line exists as SMR's response to the USH Grand Military commissioning a battlefield stealth solution. It came about by retrofitting a *Side-Winder* with a host of stealth-augmenting upgrades, such as refitting the Laminar-Motion Drive channel to accommodate a Radial Vision Obscurement Device (R-VOD.)
>[!info|n-th no-i] ##### Mechanics  
|                   |                     |
|:-----------------:|:-------------------:|
|     **Size**      |    1     |
| ***Attributes***  |                     |
|   **Structure**   |  2  |
|  **Engineering**  | 2 |
|  **Computation**  | 3 |
| **Weapon Mounts** |   Primary/Aux, Aux/Aux    |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Obfuscation-Preservation Warding  *
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> The first time each round you would become *noticed*, you do not (but you *do* gain any effects you would've as if you *did* become noticed.)
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
### Balanced Frames 
#### BF-001 "Average Joe"
The most commonly created, reliable, and basic frame. The *Average Joe* is what all Mage-Pilots learn to pilot on.
>[!info|n-th no-i] ##### Mechanics  
|                   |                                           |
|:-----------------:|:-----------------------------------------:|
|     **Size**      |                     1                     |
| ***Attributes***  |                                           |
|   **Structure**   |                     2                     |
|  **Engineering**  |                     2                     |
|  **Computation**  |                     2                     |
| **Weapon Mounts** | Primary, Secondary (One-Handed Only), Aux |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Intrinsic-Variation Override*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> At character creation, select two different Attributes. Your Metal gains a +1 bonus to those Attributes. 
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
#### BF-002 "Giant Robot"
The second-ever mass-produced SMR Frame. The *Giant Robot* was intended to be a Frame capable of carrying a singular Heavy weapon.
>[!info|n-th no-i] ##### Mechanics  
|                   |                     |
|:-----------------:|:-------------------:|
|     **Size**      |   1     |
| ***Attributes***  |                     |
|   **Structure**   | 3 |
|  **Engineering**  | 2 |
|  **Computation**  | 2 |
| **Weapon Mounts** |  Heavy     |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Failsafe Contingency  Protocol "Super Robo"*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> Whenever your Metal would be compromised and fail due to having marked max Integrity, you may roll a single d6. On a roll of 4+, set your Integrity to 1 instead, and mark max Heat, and in turn, your Metal immediately enters Meltdown.
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
### Heavy Frames 
#### HF-001 "Paul Bunyan"
Named for an Old Earth giant monster myth, this Frame was one of the first SMR frames to be made in Standard Metal Size (SMS) 2. This was done in order to accommodate the extra integrated armor and warding that enables the high-powered use of massive weapon systems.
>[!info|n-th no-i] ##### Mechanics  
|                   |                     |
|:-----------------:|:-------------------:|
|     **Size**      |    2     |
| ***Attributes***  |                     |
|   **Structure**   |  4 |
|  **Engineering**  | 2 |
|  **Computation**  | 2 |
| **Weapon Mounts** |  Primary/Aux, Secondary/Aux, Aux     |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Freedom Faller*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> A serious of strategically placed runes allow your Metal to swing Melee weapons with great speed. Primary and Super-Primary Melee weapons your Metal wields gain the [[Flurry\|Flurry 1]] trait.
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
#### HF-002 "Thunder Drum"
A unique take on the standardized *Lightweight* heavy frame, the *Thunder Drum* model replaces the integrated system of its predecessor with the “Taiko” Ally Reinforcement Array. While still outfitted with robust integrated armor and warding, this frame was designed to exploit high system capacity in order to provide powerful battlefield support.
>[!info|n-th no-i] ##### Mechanics  
|                   |                    |
|:-----------------:|:------------------:|
|     **Size**      |         2          |
| ***Attributes***  |                    |
|   **Structure**   |         2          |
|  **Engineering**  |         1          |
|  **Computation**  |         4          |
| **Weapon Mounts** | Heavy/Aux, Aux/Aux |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Integrated System-"Taiko" Ally Reinforcement Array*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> (Once per Encounter) The thundering rhythm of the Array roars to life, providing a fierce tempo to fight to. All allies within a 6-space aura around you gain a +2 bonus to attack rolls. Additionally, whenever an ally successfully lands an attack while within the aura, lightning leaps from the drums, dealing an additional 2 **electric** damage.
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
### Superheavy Frames
#### SHF-001 "Kaiju"
The SMR *Kaiju* superheavy frame is the top-of-the-line, state-of-the-art, heavy engagement platform. It was created as a homage to the Star Beasts of Mars, and as a way to kill them as well. Standard Metal Size 3 frames are *exceptionally* difficult to pilot, and the *Kaiju* is even more temperamental than other frames.
>[!info|n-th no-i] ##### Mechanics  
|                   |                     |
|:-----------------:|:-------------------:|
|     **Size**      |    3     |
| ***Attributes***  |                     |
|   **Structure**   |  4 |
|  **Engineering**  | 1 |
|  **Computation**  | 2|
| **Weapon Mounts** |  Heavy, Twin Secondary     |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk: Integrated Weapon- Kingslayer Atomic Cannon*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> (Recharge 4+) You fire a massive beam of atomic hellfire from the mouth-mounted cannon. This beam deals 2d6 *plus marked Heat* **fire** damage in a 15-space line. This beam deals *triple* damage to structures and can pierce cover. If your Metal is in Meltdown, this beam instead deals 2d12 damage.
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*
#### SHF-002 "Colossus"
The largest Frame ever manufactured by Super Massive Robotics, the Colossus was named for the Old Earth "*Colossus of Rhodes*", which was thought to be the first Metal created by mankind. The Colossus represents the pinnacle of human engineering and piloting ability, as no other species have ever had a pilot that could use one. Due to sheer size, a pilot must use the Cerebral-Interfacing Colossus Control (CICC) System, which uses complex wards and enchantments to allow the pilot to see as the Colossus does. Some pilots believe this Frame should be outlawed due to the system required for a single pilot to use it, as the Colossus has allegedly been known to “test the spirit” of its pilots.
>[!info|n-th no-i] ##### Mechanics  
|                   |                     |
|:-----------------:|:-------------------:|
|     **Size**      |    4     |
| ***Attributes***  |                     |
|   **Structure**   |  5 |
|  **Engineering**  | 1 |
|  **Computation**  | 1 |
| **Weapon Mounts** | Primary/Aux, Secondary/Aux, Secondary/Aux, Aux      |

>[!column]+ ***Upgrade Perks*** 
> 
>> [!metadata] *Basic Perk:  Cerebral-Interfacing Colossus Control System*
>> *When this part is upgraded to Basic, your Metal gains this perk.*
>> Whenever your Metal sustains damage, you take 1 **mental** damage that cannot be avoided or reduced in *any* way. You ignore Size penalties to Piloting checks.
>
>> [!metadata] *Advanced Perk:*
>> *When this part is upgraded to Advanced, your Metal gains this perk.*
>
>> [!metadata] *Ethereal Perk:*
>>*When this part is upgraded to Ethereal, your Metal gains this perk.*
>
>> [!metadata] *Divine Perk:*
>>*When this part is upgraded to Divine, your Metal gains this perk.*


## 2. *Shell*
The *Shell* of the Metal is what determines the armor plating of your Metal, as well as an *Intrinsic* ability that provides powerful combat abilities. 

Pick a **Shell** from the options below. Selection is restricted by your chosen **Pilot Role** during Mage creation. 

After you’ve chosen your **Shell**, denote the following: Attribute boost, armor type, Weapon Mounts, and Intrinsic.

### Infiltrator
#### Surgeon General
Named for a well-respected Old World medical practitioner, this Shell provides powerful support in the form of healing and armor reinforcement. 
>[!info|no-i n-th] ## Mechanics 
|                   |                     |
|:-----------------:|:-------------------:|
|  **Armor Type**   |    Infiltrator     |
| **Weapon Mounts** |   Secondary, Aux   |
|   *Attributes*    |                     |
|   **Structure**   |  1 |
|  **Engineering**  | 4 |
|  **Computation**  | 2 |

>[!column]+ ***Intrinsic and Intrinsic Upgrades*** 
> 
>> [!metadata] *Basic Intrinsic:* Reinforce Armor `=[[Dev Helpers]].two-action`
>> *This is the Shell's Intrinsic Ability*
>> 
>> [[Defensive\| Defensive (Ability)]]
>> 
>> *Frequency: Once Per Encounter*
>> - - -
>> All allies within Sensors range gain a +2 circumstance bonus to Toughness until the end of the encounter. This bonus is lost if they enter Meltdown or their Integrity fails (and cannot be regained).
>
>> [!metadata] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Intrinsic Ability gains this enhancement.*
#### Bunker Buster
Two words: payload delivery. This Shell allows Metals to get "dug in," increasing Sensor range while crippling movement in order to avoid flanks on stationary artillery delivery. 

>[!info|no-i n-th] ## Mechanics 
|                   |                     |
|:-----------------:|:-------------------:|
|  **Armor Type**   |    Infiltrator    |
| **Weapon Mounts** |   Secondary, Aux   |
|   *Attributes*    |                     |
|   **Structure**   |  1  |
|  **Engineering**  | 5 |
|  **Computation**  | 1 |

>[!column]+ ***Intrinsic and Intrinsic Upgrades*** 
> 
>> [!metadata] *Basic Intrinsic:* Entrenchment `=[[Dev Helpers]].free-action`
>> *This is the Shell's Intrinsic Ability*
>> 
>> *Frequency: Once Per Round*
>> - - -
>> You convert your method of movement (legs, typically) into a stationery intrenchment, allowing you to stabilize your shots and increase perception. Your Speed becomes 0, and your Sensor range is doubled. This transformation lasts until you spend one action to reconfigure.
>
>> [!metadata] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Intrinsic Ability gains this enhancement.*
### Mobile 
#### Subtle Dialog 
Useful for Metals who use stealth to gather information, this Shell ensures that Metal can guarantee a fast get-away when cover is blown and the fight goes loud.

>[!info|no-i n-th] ## Mechanics 
|                   |                     |
|:-----------------:|:-------------------:|
|  **Armor Type**   |    Mobile    |
| **Weapon Mounts** |   Primary, Aux    |
|   *Attributes*    |                     |
|   **Structure**   |  2  |
|  **Engineering**  | 2 |
|  **Computation**  | 3 |

>[!column]+ ***Intrinsic and Intrinsic Upgrades*** 
> 
>> [!metadata] *Basic Intrinsic:* Auto-Retreat "Skedaddle" Mechanism `=[[Dev Helpers]].two-action`
>> *This is the Shell's Intrinsic Ability*
>> 
>> *Frequency: Once Per Encounter*
>> - - -
>> Triple your Speed for the next 3 rounds. You cannot move directly towards an enemy, and lose this bonus if you make an attack of any form while affected by it.
>
>> [!metadata] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Intrinsic Ability gains this enhancement.*
#### Wire Runner 
In order to control the pace of battle, the Wire Runner shell employs a powerful lock-out subroutine.

>[!info|no-i n-th] ## Mechanics 
|                   |                     |
|:-----------------:|:-------------------:|
|  **Armor Type**   |    Mobile    |
| **Weapon Mounts** |   Primary, Aux   |
|   *Attributes*    |                     |
|   **Structure**   |  1 |
|  **Engineering**  | 2 |
|  **Computation**  | 4 |

>[!column]+ ***Intrinsic and Intrinsic Upgrades*** 
> 
>> [!metadata] *Basic Intrinsic:* Weapon Mount Lock-Out Sub-Routine `=[[Dev Helpers]].one-action`
>> *This is the Shell's Intrinsic Ability*
>> 
>> 
>> *Frequency: Once Per Round*
>> - - -
>>Select a Metal within Sensors range, then make a [[Hacking]] contest against their **Computation**. On a success, the next time they take the Attack action, you select which mount they fire from. On a failure, you instead select one of their mounts. They cannot use the selected mount until the end of your next turn. 
>
>> [!metadata] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Intrinsic Ability gains this enhancement.*
### Powered
#### Fortress Breaker Shell 
Named for the Shell's main strength, which is shattering the walls of fortresses, this Shell is preferred by Bastions and Juggernauts alike. 
>[!info|no-i n-th] ## Mechanics 
|                   |                     |
|:-----------------:|:-------------------:|
|  **Armor Type**   |    Powered    |
| **Weapon Mounts** |  Heavy, Aux    |
|   *Attributes*    |                     |
|   **Structure**   |  4  |
|  **Engineering**  | 1 |
|  **Computation**  | 2 |

>[!column]+ ***Intrinsic and Intrinsic Upgrades*** 
> 
>> [!metadata] *Basic Intrinsic:* Thundering Crash `=[[Dev Helpers]].two-action`
>> *This is the Shell's Intrinsic Ability*
>> [[Move]], [[Electric]]
>> 
>> *Frequency: Recharge 5+*
>> - - -
>> You target an enemy within Sensors range, and then barrel towards them. You Move up to that target, crashing into them with a sonic boom that deals **sonic**/**electric** damage equal to your Toughness to that target and half that to any Metal or creature who's space you moved through.
>
>> [!metadata] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Intrinsic Ability gains this enhancement.*
>
>> [!metadata] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Intrinsic Ability gains this enhancement.*


## 3. *Soul Core*
The *Soul Core* of the Metal is exactly that: a core, with a soul therewithin. It acts as the heart of the Metal’s *Soul-Resonance Reactor*, or S-R<sup>2</sup> Engine. The soul of spirit within the core reacts with the latent Potential of the Pilot, providing a nearly infinite amount of energy to run the massive machine. 

The **Soul Core** of a Metal is a special choice for a Pilot, as it dictates a special confrontation that the Pilot must eventually face at their darkest hour; the *Deity within the Machine*, the **Deus Ex Machina**. Pay special attention to the **Deus** of your chosen **Soul Core**. 

Pick a **Soul Core** for your Metal, and then denote granted the granted Attribute bonuses, Core Passive, and Core Intrinsic. You can also denote your **Deus Ex Machina**, but it will not be relevant in this playtest (or the next one, honestly.) In future playtests, **Soul Cores** will be limited by your chosen **School of Arcana** during Mage creation.
### Attack-Type Cores
#### ATSC-001 ''Warring Dragons'' 
***Requirements: None.***

The first of the Attack Type S-R<sup>2</sup> Engine cores to be produced by Super-Massive Robotics, the *Warring Dragons* utilizes two, shall we say, ***highly adversarial*** dragon spirits to facilitate the requisite Soul-Resonance reaction. These spirits, like all other spirits used in the  S-R<sup>2</sup> Engines, are perfectly safe for the pilot*, but this model of Core has been known to cause the occasional outburst in pilots who interface with it for prolonged periods.

<sub>\*Assuming proper usage</sub>

*This Core is recommended for players who want to play a heavily conflicted, passionate character, who has strong, polarizing stances on situations and ordeals.*

>[!info|no-i n-th] ##### Mechanics 
|  *Attributes*   |                                         |
|:---------------:|:---------------------------------------:|
|  **Structure**  |                    3                    |
| **Engineering** |                    2                    |
| **Computation** |                    2                    |
|   **Traits:**   | [[Air]], [[Earth]], [[Fire]], [[Water]] |

> [!embed-feat]- ### Core Passive: *A War of Two Dragons*
> [[Usage\|Usage: Metal]], [[Modal]]
> - - -
> *As you summon your Metal, and at the start of each combat, pick one of the following options*
> 
> ***Gozuryū's Pentafocus*** When you cast a spell or fire a weapon that has the [[Air]], [[Earth]], [[Fire]], or [[Water]] traits, you become [[Energized\|Energized 1]], or increase your Energized condition by one, up to a maximum of Energized 4. If you cast a spell or fire a weapon with the same trait more than once in a row, your Energized condition does not increase. 
> 
> ***Tiamat's Singular Point*** When you cast a spell or fire a weapon that has the [[Air]], [[Earth]], [[Fire]], or [[Water]] traits, you gain a  +1 *stacking*, *cumulative*, magical bonus to damage that has one of the aforementioned traits. This bonus stacks up to +4, and does not increase if you cast a spell or fire a weapon with the same trait more than once in a row.

>[!column]- ### ***Core Intrinsic and Intrinsic Upgrades*** 
> 
>> [!embed-feat]- Basic Intrinsic: *Draconic Outburst `=[[Dev Helpers]].two-action`*
>> *This is the Core's Intrinsic Ability*
>> 
>> ***Frequency: Once Per Combat***
>> 
>> [[Modal]]
>> - - -
>> *When you use this ability, its effect depends on which Passive mode you are currently using.*
>> 
>>>[!embed-feat]- ***Devastation of Gozuryū***
>>>
>>> [[Area\|Area (12-space Cone)]], [[Earth]], [[Fire]] 
>>> 
>>> A slurry of molten stones and roaring fire bellows forth from the Spirit Core. All creatures within the area take 1d6 **crushing** damage and 1d8 **fire** damage, and must make a *basic* **Reflex** save. Any creature who critically fails becomes [[Ignited]] and [[Coated]] for 1 minute.. 
>> 
>>>[!embed-feat]- ***Lamentation of Tiamat***
>>> 
>>> [[Area\|Area (8-space Emanation)]], [[Auditory]], [[Air]], [[Water]]
>>> 
>>> A horrid cry of mournful lament rings out from the Spirit Core, threatening to freeze all of creation solid. All creatures within the area must make a **Body** check. On a failure, affected creatures become [[Frozen]] for 1 round, and on a critical failure, they become Frozen for 1 minute instead. Regardless of outcome, all creatures in the area are [[Flustered]]. 
>
>> [!embed-feat] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Core Intrinsic Ability gains this enhancement.*
>
>> [!embed-feat] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Core Intrinsic Ability gains this enhancement.*
>
>> [!embed-feat] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Core Intrinsic Ability gains this enhancement.*

> [!embed-feat]- ### Deus Ex Machina: *A War Within, Finally Won*
> You finally confront the war between the spirits that reside in the core of your Metal, and in turn, the war within yourself. If you would be faced with a choice that you truly find no way to resolve, you can invoke this Deus Ex Machina. The Escalation die immediately is set to maximum, and you must face a Test of Soul, which will be determined by your GM. On a success, your Soul ignites. Replace your Potential attribute with Soul, and increase your Tier to 5. 
### Defense-Type Cores
#### DTSC-001 ''Steelclad Mamba''
***Requirements: None*** 
First of the Defense-Type  S-R<sup>2</sup> Engine cores produced as apart of SMR’s contract with the USH military, the *Steelclad Mamba* utilizes a Spirit that is internally referred to as the *Iron Adder*\*. This spirit is a massive serpent, clad in trillions of steel plates in place of scales that it can use to create weapons and shields at will. This core, after prolonged exposure, tends to illicit protective behaviors in pilots.  

<sub>\*SMR and the USH-M are acutely aware that Adders and Mambas are two different species of snake.</sub>

>[!info|no-i n-th] ##### Mechanics 
|  *Attributes*   |                     |
|:---------------:|:-------------------:|
|  **Structure**  |  2  |
| **Engineering** | 3 |
| **Computation** |2 |
|   **Traits:**   |  [[Metal]]                   |

> [!embed-feat]+ ### Core Passive: *Coiled Blade*
> [[Usage\|Usage: Metal]]
> - - -
> You gain a +1 magical bonus to attacks made as a part of a reaction. This bonus increases by 1 each time you upgrade the quality of this soul core.

>[!column]+ ### ***Core Intrinsic and Intrinsic Upgrades*** 
> 
>> [!embed-feat] Basic Intrinsic: *Shed Scales* `=[[Dev Helpers]].three-action`
>> *This is the Core's Intrinsic Ability*
>> 
>> ***Frequency: Once Per Combat***
>> [[Usage\|Usage: Metal]]
>> - - -
>> You shed your scales, clearing all negative statuses and shedding all penalties to Toughness. 
>
>> [!embed-feat] *Advanced Enhancement*
>> *When this part is upgraded to Advanced, your Metal's Core Intrinsic Ability gains this enhancement.*
>
>> [!embed-feat] *Ethereal Enhancement*
>>*When this part is upgraded to Ethereal, your Metal's Core Intrinsic Ability gains this enhancement.*
>
>> [!embed-feat] *Divine Enhancement*
>>*When this part is upgraded to Divine, your Metal's Core Intrinsic Ability gains this enhancement.*

> [!embed-feat]+ ### Deus Ex Machina: *A Cure For Poison*
> You find the cure for the *Iron Adder’s* most virulent poison. 
> 
> If you would be forced to attempt to survive an impossible circumstance, you can invoke this Deus Ex Machina. The Escalation die is immediately set to maximum, and you must face a Test of Soul, which has been carefully determined by your GM. On a success, your Soul ignites. Replace your Potential attribute with Soul, and increase your Tier to 5. 
### Support-Type Cores

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
### E.2: Weaponry
![[Mage Weapon Appendix]]
### E.3: Armor
![[Armor Appendix]]
## Appendix F: Metal Equipment
### F.1: Metal Systems 
![[System Appendix]]
### F.2: Metal Weaponry 
![[Metal Weapon Appendix]]