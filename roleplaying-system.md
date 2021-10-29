# Conan D20 System
We'll be running this campaign using the **3rd edition Conan D20 system**. I chose this system primarily because it's very close to systems we all know (D&D 3.5 and Pathfinder), but it better suits the theme the story will touch on. I could have used the Warhammer Fantasy rules, but these are pretty foreign to us and I don't want to add that burden.

The 3rd edition Conan D20 system is extremely similar to D&D 3.5 with a few notable exceptions:
1. Armor and defense have been overhauled to provide a more robust combat experience
    - AC has been broken down into two active defensive options; *Dodge* and *Parry*
    - Armor instead provides *damage reduction* which can be mitigated by a high *strength* score and weapons with high *armor piercing* scores.
1. Finesse fighting is available to any character
1. This is a very low magic system with a strong theme of corruption from its use.
1. Magic items and magical healing are rare.

## Rulebook
For simplicity, only the core rule book is allowed.
- [Conan D20 3.5](https://drive.google.com/file/d/0B36P1ltRqaAMMXNhMVQtM2NuSEU/view?usp=sharing&resourcekey=0-ftS9tc5byv7bF_sSPQL2ww)

# Notable Rules
Since most of us are familiar with D&D 3.5 and Pathfinder, I've provided a list of the notable rule changes between Conan D20 and those systems (along with a few optional rules and house rules).

## Misc
- **Initiative (p.151):** `Initiative Check = 1d20 + Reflex saving throw modifier + Dexterity modifier + any relevant feats or other bonuses (Improved Initiative, etc.)`

## Defense
Every character must decide in combat whether to defend by Dodging or Parrying. Most characters will have a preferred method of defence and it is often easiest to assume that said preferred method is in use each round unless the Player specifi es otherwise.

- **Dodge (p.149):** `Dodge Bonus = base dodge bonus (class) + dodge bonuses`
    - Requires at least one free or friendly square to have enough space to move, otherwise take a -2 penalty.
- **Parry (p.149):** `Parry Bonus = base parry bonus (class) + parry bonuses`
    - Must wield a weapon, shield, or object.
    - Ranged attacks cannot be parried.
    - -4 penalty for being unarmed, -1 penalty when not proficient with the weapon or using an improvised weapon.
    - **Weapon Breakage Rule (p.150):** Every time the attack roll exactly **equals the defender's Parry Defence**, proceed as if the attacker had made a successful **sunder** attempt against the defender's weapon instead of hitting the defender.

## Armor, Damage Reduction, and Armor Piercing

- **Armor Damage Reduction (p.150):** Instead of making a character hard to hit, armor reduces the damage taken via **Damage Reduction.**
    - Any type of armor may have it's DR score increase by adding a helmet.
- **Shields (p.136):** Apply their shield bonus to Parry Defense, Dodge Defense vs ranged attacks, and may be used to make shield bash attacks (losing parry defense in the process). Shields have no effect on Armor DR.
- **Armor Piercing Weapons (p.153):** Armor DR is **halfed** when `AP Score (Str + Weapon AP) >= Armor DR Score`.
    - Weapons with AP 0 cannot pierce armor regardless of the character's strength.
    - Attackers using Finesse Fighting bypass Armor DR in a different manner (see below).
    - See p.153 for an example if you get confused.
- **Armor Damage & Repair (p.153):** When armour is hit for **20+ damage (after the DR), its DR is reduced by 1d4.**
    - Armor can be repaired by anyone with the Craft (armoursmith) skill at a cost of 20% of the original cost of the armour per 1 DR damage. 
    - Repair cost is halfed if the character does it himself with a Craft (armourer) check (DC 10) or Craft (blacksmith) check (DC 15) and ten minutes of time for each 1 DR repaired. 
    - If armour is reduced to 0 DR, it is completely destroyed.

## Attacks 
- **Finesse Fighting (p.154):** When using a finesse weapon, you may use Dex instead of Str for attack.
    - _Finesse Weapons:_ All light weapons and several one-handed or two-handed piercing weapons
    - **Bypassing Armor:** **Ignore Armor DR** when `attack roll > Defense + DR`
        - Overrides the Armor Piercing rules.
    - Switching between finesse fighting and standard attacks is a free action and can be performed every round.
    - Ranged weapons cannot be used with Fineese fighting.
- **Combat Maneuvers (p.179):** A list of combat maneuvers are available to any character at no cost, provided that character meets the prerequisites. These maneuvers are in addition to any class abilities or feats your character by obtain.

## Damage Rules
- **Minimum Damage Rule (p.153):** If damage reduction from armour reduces the damage of a successful attack to less than 1, a successful hit still deals 1 point of nonlethal damage.
- **Massive Damage Rule (p.163):** If a character takes `20+ damage` from a single attack and is not reduced below 0 hp, the character must make a Fortitude saving throw.
    - `Massive Damage Fortitude Saving Throw DC = 10 + (1/2 damage dealt)`
    - If the save fails, the character drops to -10 HP and is dead. A `Fate Point` may still be used to be "left for dead."

## Healing
- **[House Rule] Max natural healing:** When calculating natural healing, always take the maximum value. 

## House Rule: Damage Fatigue and Exhaustion
The goal of this rule is to make low health actually impact how characters can perform. Rather than giving a blanket penalty across the board like other systems (L5R for example), we will instead apply fatigue and exhaustion effects when a player drops at or below a certain percent of their maximum hitpoint value.
- **Damage Fatigue:** When a player drops **below 20%** of their maximum hitpoints, they become **fatigued** from damage.
- **Damage Exhaustion:** When a player drops **below 10%** of their maximum hitpoints, they become **exhausted** from damage.

### _Fatigued_
A fatigued character can neither run nor charge and takes a -2 penalty to Strength and Dexterity. Doing anything that would normally cause fatigue causes the fatigued character to become exhausted. After 8 hours of complete rest, fatigued characters are no longer fatigued.

### _Exhausted_
An exhausted character moves at half speed and takes a -6 penalty to Strength and Dexterity. After 1 hour of complete rest, an exhausted character becomes fatigued. A fatigued character becomes exhausted by doing something else that would normally cause fatigue.