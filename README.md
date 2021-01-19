**ArenaSimpleTargets** creates macros for targeting the party and the enemy in the Arena that you can then bind to whatever key you like.

## Motivation

Targeting in the arena is one of the pain points for many player because the default UI doesn't provide enough support to do that in a friendly way so you either end up manually editing macros or using addons similar to this one that can automate the process and I've tried a few but they didn't quite work for me so I made my own and hopefully it can help you too.

## How it works?

The way it works is pretty simple, when you are in the preparation room the addon edits the mentioned macros below dynamically based on the party members and the enemy roles as follow:

### Party Macros:

* **AST:PartyX** - Targets the 1st party member that isn't yourself.
* **AST:PartyY** - Targets the 2nd party member that isn't yourself.

### Enemy Macros:

* **AST:EnemyX** - Targets the 1st DPS/Tank.
* **AST:EnemyY** - Targets the 2nd DPS/Tank.
* **AST:EnemyZ** - This should always target the healer as long as one exists; otherwise, it will target the 3rd DPS/Tank.

## How do I set the keybinds for it?

Type `/macro` and then drag the macros to the `Action Bar`, finally go to the `Game Menu` and click on Key Bindings to bind the key to the action button.

## What are you binding it to?

* Alt+Scroll Up/Down for the party.
* Shift+Scroll Up/Down and Shift+Scroll Click for the enemy.

But really you should bind it to whatever is the most comfortable for your setup.

## Enjoy!