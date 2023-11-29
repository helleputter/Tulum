# Tulum

This project was created to build a ComputerCraft program that has hive mind behaviors
with a central controlling agent just like bees.

## What is ComputerCraft?

ComputerCraft is a mod (short for modification) for the popular PC game called Minecraft.
It allows you to build ingame computers and turtles (computers that can move and interact more with the world), and write programs for them using the Lua programming language.

## Development

The development of the communication system will be tested automatically with pytest in an simulated environment using CraftOS-PC. This way we can spin up and add as many clients as needed for a certain test without the need for setup in Minecraft.
This reduces development time and ensures a working communication base.

The parts that can't be tested in the emulation will either be added with the creation of personal plugins for CraftOS-PC or run directly in minecraft.
