
All code is yours to own.
- gem install bundler 
- bundle install

Available rake tasks:
	* `rake` or `rake spec` to run all specs


## Introduction

"Alchemy is the science of understanding, deconstructing, and reconstructing matter. However, it is not an all-powerful art. It is impossible to create something out of nothing. If one wishes to obtain something, something of equal value must be given. This is the law of equivalent exchange; the basis of all alchemy."

The year is 1016 and the economy has been blighted.
Every famous bard has been killed off, including David Bowith and the Prince.
It has been discovered that alchemy can be used to turn lead to gold and create the elixir of life.

## Task

You are an apprentice alchemist and your master has left you a note of tasks to undertake in the apothecary.

There are three types of methods which you need to do:

### ADD
Reconstructs the elements into one

Example Expected Input: "WATER", "FIRE", "ADD"

Example Expected Output: "WATERFIRE"

### STIR
Reconstructs the elements into one in reverse order

Example Expected Input: "WATER", "FIRE", "STIR"

Example Expected Output: "FIREWATER"

### MIX
Interweaves the elements into one

Example Expected Input: "WATER", "FIRE", "MIX"

Example Expected Output: "WFAITREER"

NOTES:

1. You may receive any elements to combine but you only know these three methods.
   If you are asked to perform something else which you do not know, yell "HELP ME, SENPAI!"
2. You only know how to deal with two elements at a time
3. Don't worry if one of the elements is shorter than the other (see example)

## EXTENSION TASK

You are the master alchemist checking up on your apprentice's work to see if they have produced the correct potions.
In order to do this, you will need to perform a deconstruction.

### DECONSTRUCT
Given the result and the two elements, find out which method was used for combining these.

Example Expected Input: "WATER", "FIRE", "FIREWATER"

Example Expected Output: "STIR"