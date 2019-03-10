# Project Factory
Enabling democratized production through a virtualized manufacturing platform

## Introduction
Project Factory is the cloud platform for physical manufacturing. It tries to provide a complete digital abstraction of the physical manufacturing process, allowing anyone to design and manufacture products.

## Motivation
Completely virtualized manufacturing is the logical next step for manufacturing. By making this open-source, we ensure that the added value of a cloud manufacturing platform is less centralized in the hands of a couple of early innovators.

## Minimum Viable Platform
For the MVP we do not want to deal with the uncertainty and complexity of the world that we live in. The platform will thus not be connected to the physical world, but instead it will be connected to simulation games. This way the huge cost of dealing with the complexity of the real world is postponed.

Games which could be used for the MVP: Factorio, Minecraft, Scrap mechanic.

On the platform, the designer will specify which product they want to manufacture and how. After pushing this specification, actors in the actual game will execute this specification.

Another, perhaps less attractive, option is to create a simulation of the real world ourselves instead of using an existing game.

## Design philosophies
### Warehouse as an OS
In this design philosophy the Operating System is the metaphor for our warehouse design. The warehouse has inputs (raw materials), outputs (the products/waste), resources (electricity, space, tools...) and these should be managed in the same way as they are managed in operating systems.

This means that we have the base resources, an intermediate kernel (the actual platform) and applications (the actual manufacturing tasks) on top of it.
