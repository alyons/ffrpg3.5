# Random Number Generator
**Status:** Designing
**Deciders:** Alex, Joel
**Date:** 2022-10-02

## Context and Problem Statement
As part of a table top roleplaying game, we want to have a way to describe variance within gameplay mechanics. This will be used in conjuction with player choices in the actions within the moment as well as choices the player has made in creating their character.

### Terms
**Actor:** The player or game master rolling on behalf of a character in the game.
**Critical Success:** The check always succeeds, regardless of if the DC is met.
**Critical Failure:** The check always fails, regardless of if the DC is met.
**Difficulty Class (DC):** The value against which an actor is rolling to see if an action is successful.
**d20:** A 20 sided die. A critical success is defined as a natural 20. A critical failure is defined as a natural 1.
**d%:** A 100 sided die. This is emulated by using two d10, signifying one as the 10's digit. If both numbers are 10, this is treated as a 100.

## Decision Drivers
1. We need a system that is simple to use. _Simple is not easy._
2. We need a system that encourages player choice.

## Considered Options
### d20
The actor rolls a d20 and adds a specific number appropriate to the test being applied. If the value meets or beats the set difficulty value, the check is successful.  
In certain tests, rolling a 1 on the d20 counts as a failure and rolling a 20 on the d20 counts as a success.  

Difficulty Class
| Difficulty      | Average Value |
| --------------- | ------------- |
| Trivial         | 5             |
| Easy            | 10            |
| Moderate        | 15            |
| Hard            | 20            |
| Monumental      | 25            |
| Nigh Impossible | 30            |

#### Pros
- Simple system to use
#### Cons
- Just like D&D
- The status numbers have be adjusted to make decision matter.
#### Others


### d%
The actor rolls a d% and checks against a percentile DC.
### Dynamic Dice
The actor rolls a certain set of dice depending on their proficiency with a test.