RPG Battle, vol.1

This is my first small game project using python and OOP.

It is played by two players, Player 1 and Player 2.

The players have to choose their race:

1. Human
2. Orc
3. Elf
4. Dwarf

The game then generates the two heroes, based on their class.
Each hero has a name, health points and low and high attack.

After that, the players watch their heroes fight until
one of the heroes dies.

Whos turn is to attack is defined by probability.

In each attack round, the current damage of the attacking hero
is calculated as a random number between his low and high attack power.

The current damage is then substracted from the opponents health points.

The game continues until the health points of one of the heroes is 0 or less.

The players then can choose whether to play another game and choose different race
or to quit the game.

-----------------------------------

In the next version of the game I will add more functionality so that the players
will have more options to choose from and will add additional properties for the heroes.

For example:
1. Armor or shield for the heroes, so that they can defend themselves from the attack of the opponent.
2. Health potions, which can be drunk when the health is below some specified level.
3. Ability to flee from the battlefield, which will make the opponent winner of the battle.
