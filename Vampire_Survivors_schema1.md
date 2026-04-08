# Vampire Survivors Counting 

![MNL_logo](https://github.com/jtlunaSB/Record/blob/main/MNL.png)

## Purpose
Provide coders with an expiditious way to code the videos that remains **wholly** grounded in the [codebook](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md) while being **specific** to the game of interest (Vampire Survivors). To that extent, this guide will exhaustively classify specific instances of rewards and punishments in the video game Vampire Survivors, define counting strategies for these rewards, and reference the [codebook](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md) with explicit reasons for each categorization and counting rule. Vampire Suvivors is a **_real time_** video game; unlike turn-based strategy games, it must be coded with real time actions and events in mind.

1. Please be familiar with the operational criteria and counting strategies for major/minor rewards and punishments, as defined in the [codebook originally](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#minor-rewards)
2. Please be familiar with the [Specific Reward and Punishment Categories](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#specific-reward-punishment-categories), although Vampire Survivors features few of them, in total

> [!TIP]
> Familiarization with the aforementioned will assist coders in making decisions in the absense of a clear rule.

## Formatting
This guide will list the following for each relevant category (Instrumental and Systemic Rewards and Punishments [4 total])

1. A specific of the reward/punishment
2. An instance within the game
3. A rule for counting
4. Citation from the [codebook](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md) while being **specific** to the game of interest (Vampire Survivors), justifying the rule

## Definitions
**Individualized**: Refers to something which is coded as 1 reward/punishment per instance

**Sequential**: Refers to _somethings_ (a sequence of events) which are coded as 1 whollistically (or _in total_)

## Instrumental Rewards

| Reward | video + Time point | Counting Rule | Codebook Justification |
|-------|--------------|------------------|-----------------------------|
| Individualized defeat of an enemy resulting in score increase | Occurs 3 times in Video 1, 0:06-0:11 | Count each instance as 1 minor reward (so 3 minor total here) | [Instrumental Rewards](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#instrumental-rewards:~:text=one%20minor%20reward.-,Instrumental%20Rewards,-Definition%3A) describes quantifiable markers of progression |
| Sequential defeat of enemies resulting in score increase | Occurs 3 times in Video 1, 0:12-0:15 | Count each **_sequential_** instance as 1 minor reward (so 3 minor total here as well) | [Simultaneity of Events](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#simultaneity-of-events) descibes that if same-type event A (Counter increasing as 1st bat dies) concludes with the begining of event B (Counter increasing as 2nd bat dies) then these are counted as 1 minor reward |
| Individualized obtaining of gem (and experience bar increase) | Occurs 3 times in Video 2, 0:50-0:55 | Count each instance as 1 minor reward (so 3 minor total here) | [Instrumental Rewards](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#instrumental-rewards:~:text=one%20minor%20reward.-,Instrumental%20Rewards,-Definition%3A) describes quantifiable markers of progression |
| Sequential obtaining of gems (and experience bar increase) | Occurs 1 time in Video 1, 2:54-2:57 | Count all gems obtained as 1 minor reward; gems may be considered sequential if they are, _without interruption_, floating toward the player | [Simultaneity of Events](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#simultaneity-of-events) descibes that if same-type event A (gem 1 floating toward player) concludes or co-occurs with the begining of event B (gem 2 floating toward player) then these are counted as 1 minor reward |
| Sequential obtaining of gems (and experience bar increase) (Large screen change) | Occurs in Video 1, 11:15 | Count all gems obtained as 1 Major reward | [Simultaneity of Events](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#simultaneity-of-events) allows for sequential events to be counted as 1 event, a [large screen change is Major](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#major-rewards), thus, a series of simultaneuos events with a sufficiently large screen change is Major |
| Level-Up |  |  | The reason this is not systemic is because [Systemic Rewards](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#systemic-rewards) are, definitionally, non-quantifiable (antithetical to leveling up in a video game) |
| Gain of a weapon (e.g. from Level-Up) |  | Count as 1 major/minor reward |  |
| Gain of a non-gem item |  | Count as 1 minor reward unless the ensuing screen change is large (e.g. Pentagram) |  |
| Gain of loot box |  | Count intial onset of screen change as 1 Major reward  |  |
| Gain of a weapon (loot box specific) |  | Count all weapons gained, no matter quantity, as 1 minor reward _at the end_ of the animation |  |
| Gain of coins (loot box specific) |  | Count entire duration of coin increase as 1 'running' minor reward | [Simultaneity of Events](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#simultaneity-of-events) captures sequential events |


> [!TIP]
> The most common type of reward will be sequential minor as the player get groups of 2 or 3 gems at a time in the early game.

## Systemic Rewards

| Reward | video + Time point | Counting Rule | Codebook Justification |
|-------|--------------|------------------|-----------------------------|
| Individualized gain of 4th weapon choice upon Level-Up | Occurs in Video 1, 7:30 | Count additional weapon choice as 1 minor reward at the time it appears on screen | A single additional choice is, like all [Systemic Rewards](https://github.com/jtlunaSB/MNL_Codebook/blob/main/CodeBook.md#systemic-rewards), non-quantifiable; nor does this originate from a source other than luck |
|  |  |  |  |

## Instrumental Punishments

| Reward | video + Time point | Counting Rule | Codebook Justification |
|-------|--------------|------------------|-----------------------------|
|  |  | [Loot obtained from defeating enemies](https://www.youtube.com) |  |
|  |  |  |  |

## Systemic Punishments

| Reward | video + Time point | Counting Rule | Codebook Justification |
|-------|--------------|------------------|-----------------------------|
| Additional weapon choice |  | [Loot obtained from defeating enemies](https://www.youtube.com) |  |
|  |  |  |  |
