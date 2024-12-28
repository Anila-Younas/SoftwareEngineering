# AntFarm Simulation Assignment using C++ Design Patterns

## Project Overview

The AntFarm Simulation Assignment is a C++ implementation that demonstrates the application of various design patterns in software engineering. It includes creational, structural, and behavioral patterns to simulate the behavior and management of ant colonies in a meadow environment. The project fulfills academic requirements for implementing design patterns while fostering creative problem-solving skills.

## Key Features

- **Singleton Pattern**: Ensures only one Meadow instance exists throughout the simulation.
- **Builder Pattern**: Constructs ant farms incrementally by building rooms.
- **Factory Pattern**: Creates Drones, Warriors, and Queens in their respective contexts.
- **Decorator Pattern**: Tracks and extends the attributes of ants dynamically.
- **Mediator Pattern**: Manages tick-based simulation events and interactions between ants and colonies.
- **Templates**: Implements generic ant farms capable of handling any ant type.

## Functional Requirements

- A single meadow capable of spawning multiple ant farms.
- Each ant farm contains rooms that facilitate ant activities like spawning and resting.
- Ant colonies engage in battles, and attributes transfer based on the outcomes.
- Queens can take over rival colonies and merge their attributes.
- Ant farms have a limited capacity for resting ants based on room availability.
- The simulation ends when only one active colony or queen remains.

## Simulation Commands

The command-line interface supports the following operations:

- **spawn X Y T**: Creates a colony at coordinates X, Y of species T and assigns it an identifier.
  - Example: `spawn 14 32 Killer`

- **give I R A**: Allocates resources R of amount A to the colony identified by I.
  - Example: `give 1 food 50`

- **tick [T]**: Executes T tick operations or a single tick if T is unspecified.
  - Example: `tick 10`

- **summary I**: Displays the status and statistics of the colony identified by I.
  - Example: `summary 1`

## Design Patterns in Use

- **Singleton**: Restricts Meadow to a single instance.
- **Builder**: Constructs ant farms in a step-by-step process.
- **Factory**: Creates ants based on type and context.
- **Decorator**: Dynamically adds or modifies ant attributes.
- **Mediator**: Coordinates the tick-based events of the simulation.
- **Templates**: Provides flexibility in handling various ant types.

## Requirements

### Software

- C++ Compiler (GNU GCC or equivalent)
- GitHub for version control and submission

### Resources

- Completed LinkedIn Learning courses:
  - C++ Design Patterns: Structural
  - C++ Design Patterns: Behavioral
  - C++ Design Patterns: Creational
