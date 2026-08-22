<p align="center"> <img src="https://github.com/zerodawnbr/zerodawntoolbox/blob/main/imgs/banner.jpg" alt="Banner Zero Dawn"> </p>

![Banner do Mod](https://github.com/zerodawnbr/TerjeSkill/blob/main/cannibal.png)


# 💀 Skill Tree: CANNIBAL

> *Survive by consuming your own kind.*
>
> The dark path of human flesh brings madness, but rewards predators with unmatched power and brutal instincts.

---

## 🩸 PERKS

### 1. ➕ Iron Stomach

> Reduces the chance of contracting **Brain Disease (Kuru)** when eating human flesh. At max level, the cannibal develops **total immunity**.

**📈 Progression — Levels 1 to 5**

`20%` ➜ `40%` ➜ `60%` ➜ `80%` ➜ `100%`

**🛡️ Infection Resistance**

---

### 2. 🧛 Taste of Blood

> Grants a **health regeneration** rate immediately after consuming human flesh. Fresh blood heals your wounds.

**📈 Progression — Levels 1 to 5**

`0.5` ➜ `0.6` ➜ `0.7` ➜ `0.8` ➜ `0.9`

**❤️ Healing Modifier**

---

### 3. 💀 Bloodlust

> Desperation brings fury. Drastically increases **melee combat damage** when your health is critically low.

**📈 Progression — Levels 1 to 5**

`+25%` ➜ `+27%` ➜ `+29%` ➜ `+31%` ➜ `+33%`

**⚔️ Additional Raw Damage**

---

### 4. 🧟 Predatory Instinct

> Hunters do not tire easily. Reduces **stamina** consumption for all movement actions.

**📈 Progression — Levels 1 to 5**

`10%` ➜ `11%` ➜ `12%` ➜ `13%` ➜ `14%`

**🏃 Stamina Cost Reduction**

---

### 5. 👃 Scent of Prey

> A true predator smells death. Visually highlights nearby **fresh corpses** through smoke and flies.

**📈 Progression — Levels 1 to 5**

`25m` ➜ `35m` ➜ `45m` ➜ `55m` ➜ `65m`

**👁️ Detection Distance**

---

### 6. 🔪 The Butcher

> Mastery of the blade. Ensures you harvest **more meat** when skinning survivor corpses and severely reduces knife degradation during the process.

**📈 Progression — Levels 1 to 5**

`+25%` ➜ `+30%` ➜ `+35%` ➜ `+40%` ➜ `+45%`

**🥩 Meat Yield**

---

### 7. 🥩 Devourer

> The body adapts to the new diet. Drastically multiplies the **Nutrition and Hydration** values extracted from each piece of human meat.

**📈 Progression — Levels 1 to 5**

`1.50x` ➜ `1.55x` ➜ `1.60x` ➜ `1.65x` ➜ `1.70x`

**🍖 Nutritional Status**

---

### 8. ⚡ Adrenaline Rush

> The frenzy of the hunt. Grants an immediate burst of **movement speed and stamina recovery** right after taking down a survivor.

**📈 Progression — Levels 1 to 5**

`10%` ➜ `12%` ➜ `14%` ➜ `16%` ➜ `18%`

**⚡ Speed Bonus**

---

### 9. 🤕 Pain Resistance

> Madness numbs the body. Considerably reduces **shock damage**, preventing unconsciousness during combat and enemy attacks.

**📈 Progression — Levels 1 to 5**

`25%` ➜ `27%` ➜ `29%` ➜ `31%` ➜ `33%`

**🛡️ Shock Reduction**

---

### 10. 👑 Apex Predator

> The ultimate frenzy state. Become a **relentless monster**, receiving massive combat bonuses right after a confirmed kill.

**📈 Progression — Levels 1 to 5**

`25%` ➜ `27%` ➜ `29%` ➜ `31%` ➜ `33%`

**💀 Additional Skill Power**

---

## ☠️ BECOME THE PREDATOR

> **You do not hunt to survive.**
>> **You survive because you hunt.** 🩸

---

# 💀 How to Earn XP — CANNIBAL

There are **4 exact ways to earn XP** with the current settings of the **CANNIBAL** skill tree.

---

## 1. 🩸 Kill Survivors

> **The highest source of XP.**

Getting your hands dirty yields **50 XP per kill**. However, the engine has some strict locks to prevent XP *farming* among friends.

### 🎯 Headshot Bonus

If the kill is achieved with a **headshot**, the experience receives a **1.5x** multiplier.

- **Normal XP:** `50 XP`
- **Headshot:** `50 × 1.5 = 75 XP`

### 📏 Minimum Distance

Per the variable:

`CannibalMinimumSurvivorDistance = 100`

the target must be **at least 100 meters away** from you for the XP to count.

### ⏱️ Victim Cooldown

You cannot kill the same person repeatedly to accumulate XP.

The variable:

`CannibalSameVictimExperienceCooldown = 3600`

requires you to wait **3600 seconds**, equivalent to:

**1 hour**

before earning XP again by killing the same player.

### ⏱️ General Cooldown

There is also an interval of:

`60 seconds`

between any kill for the XP to be validated.

---

## 2. 🔪 Butcher Corpses

> **Cleaning up the crime scene also pays off.**

Butchering a human player's corpse using a **knife** grants XP instantly.

The XP amount is defined by the variable:

`CannibalButcherCorpseExpGain`

- **XP per butchered corpse:** `25 XP`

---

## 3. 🥩 Consume Human Flesh

> **Our daily bread.**

Every time the character consumes a **piece of processed human meat**, they receive XP.

The XP amount is defined by the variable:

`CannibalConsumeHumanFleshExpGain`

- **XP per consumed piece:** `10 XP`

---

## 4. 💀 Eat Directly from the Corpse

> **Extreme barbarism.**

Using the action to eat **raw meat directly from the corpse on the ground** grants additional XP per bite.

The XP amount is defined by the variable:

`CannibalEatCorpseExpGain`

- **XP per bite:** `5 XP`

---

# ☠️ Summary

| Action | XP |
|---|---:|
| 🩸 Kill survivor | **50 XP** |
| 🎯 Headshot | **75 XP** |
| 🔪 Butcher corpse | **25 XP** |
| 🥩 Consume processed human meat | **10 XP** |
| 💀 Eat directly from corpse | **5 XP per bite** |

---

# 🏆 Fastest Strategy

The fastest way to level up this tree is to combine all XP sources:

1. 🎯 **Hunt players from a distance**
2. 🔫 **Secure the Headshot** → `75 XP`
3. 🔪 **Go to the body and butcher it** → `25 XP`
4. 🥩 **Consume the generated meat** → `10 XP per piece`
5. 💀 **Eat directly from the corpse** → `5 XP per bite`

---

## 🛡️ Abuse Protection

The system has specific mechanisms to prevent artificial XP *farming* among friends:

- 📏 **Minimum distance:** `100 meters`
- ⏱️ **Same victim cooldown:** `3600 seconds`
- ⏱️ **General cooldown between kills:** `60 seconds`
- 🎯 **Headshot:** `1.5x` multiplier

These restrictions significantly hinder the use of arranged kills between players to artificially accelerate progression.

---

> 🩸 **The system was developed to reward true terror.**
>
> **Kill. Butcher. Devour. Evolve.**

---

# skills.cfg File

## 🩸 Cannibal Experience

| Parameter | Value | Description |
|---|---:|---|
| `Skills.CannibalConsumeHumanFleshExpGain` | `10` | Sets experience gained when consuming human flesh. |
| `Skills.CannibalKillSurvivorExpGain` | `50` | Sets experience gained when killing a survivor. |
| `Skills.CannibalButcherCorpseExpGain` | `25` | Sets experience gained when butchering a human corpse. |
| `Skills.CannibalEatCorpseExpGain` | `5` | Sets additional experience gained when consuming flesh from a corpse. |
| `Skills.CannibalHeadshotKillExpModifier` | `1.5` | Sets experience multiplier when killing a survivor with a headshot. |
| `Skills.CannibalKillStreakExpModifier` | `1` | Sets experience multiplier applied to consecutive kills. |

---

## ⚖️ Cannibal Balance

| Parameter | Value | Description |
|---|---:|---|
| `Skills.CannibalTasteOfBloodDuration` | `30` | Sets duration of the **Taste of Blood** effect. |
| `Skills.CannibalTasteOfBloodCooldown` | `60` | Sets cooldown for the **Taste of Blood** effect. |
| `Skills.CannibalBloodlustHealthThreshold` | `0.5` | Sets health percentage below which **Bloodlust** becomes active. |
| `Skills.CannibalBloodlustMinimumHealth` | `0.1` | Sets minimum health percentage used to calculate **Bloodlust**. |
| `Skills.CannibalScentOfPreyCorpseLifetime` | `1800` | Sets how long a corpse remains detectable in seconds. |
| `Skills.CannibalButcherSkinningTime` | `30` | Sets time required to butcher a human corpse. |
| `Skills.CannibalButcherKnifeDamage` | `50` | Sets absolute damage applied to a knife when butchering. |
| `Skills.CannibalAdrenalineRushDuration` | `30` | Sets duration of the **Adrenaline Rush** effect. |
| `Skills.CannibalAdrenalineRushStaminaModifier` | `0.25` | Sets stamina recovery bonus for **Adrenaline Rush**. |
| `Skills.CannibalAdrenalineRushCooldown` | `60` | Sets cooldown before **Adrenaline Rush** can trigger again. |
| `Skills.CannibalAdrenalineRushHealthRegeneration` | `0` | Sets health regeneration provided by **Adrenaline Rush**. |
| `Skills.CannibalAdrenalineRushMovementModifier` | `0.1` | Sets movement speed bonus provided by **Adrenaline Rush**. |
| `Skills.CannibalPainDamageModifier` | `1` | Sets damage multiplier applied to pain-related effects. |
| `Skills.CannibalApexPredatorDuration` | `90` | Sets duration of **Apex Predator** effect. |
| `Skills.CannibalApexPredatorStaminaModifier` | `0.65` | Sets stamina recovery bonus for **Apex Predator**. |
| `Skills.CannibalApexPredatorCooldown` | `45` | Sets cooldown before **Apex Predator** can trigger again. |
| `Skills.CannibalApexPredatorHealthRegen` | `2.5` | Sets health regeneration provided by **Apex Predator**. |
| `Skills.CannibalApexPredatorMovementMod` | `0.2` | Sets movement speed bonus provided by **Apex Predator**. |
| `Skills.CannibalApexPredatorDamageMod` | `0.5` | Sets damage bonus provided by **Apex Predator**. |
| `Skills.CannibalMinimumSurvivorDistance` | `100` | Sets minimum distance required for a survivor kill to generate experience. |
| `Skills.CannibalKillExperienceCooldown` | `60` | Sets minimum time between survivor kills to generate experience. |
| `Skills.CannibalSameVictimExperienceCooldown` | `3600` | Sets cooldown before the same victim can generate experience again. |

---

## 🥩 Cannibal Devourer

| Parameter | Value | Description |
|---|---:|---|
| `Skills.CannibalDevourerEnergyModifier` | `1.5` | Sets the energy multiplier applied when consuming human flesh. |
| `Skills.CannibalDevourerWaterModifier` | `1.5` | Sets the hydration multiplier applied when consuming human flesh. |
| `Skills.CannibalDevourerHealthModifier` | `1` | Sets the health restoration multiplier applied when consuming human flesh. |
| `Skills.CannibalDevourerEnergyPerLevel` | `0.05` | Sets the additional energy modifier gained per skill level. |
| `Skills.CannibalDevourerWaterPerLevel` | `0.05` | Sets the additional hydration modifier gained per skill level. |

---

## Contact
Want to use it on your server?  
Get in touch via **Discord Direct** or open a **ticket**.  

[Visit our Discord](https://discord.gg/R4eNUDPArW)
