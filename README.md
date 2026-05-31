# Life Simulator

An interactive implementation of Conway's Game of Life built with C# and Windows Forms.

This project simulates cellular automata behavior in real time, allowing users to generate, observe, and modify evolving life patterns through an interactive graphical interface.

## Features

* Real-time Game of Life simulation
* Interactive cell creation and removal
* Adjustable simulation resolution
* Configurable initial population density
* Infinite world wrapping (toroidal grid)
* Live generation counter
* Start and stop simulation controls
* Graphical visualization using WinForms
* Console and desktop application implementations

## Technologies

* C#
* .NET 10
* Windows Forms (WinForms)
* Object-Oriented Programming (OOP)
* Graphics Rendering
* Event-Driven Programming

## How It Works

The simulation follows Conway's classic Game of Life rules:

1. Any live cell with fewer than two live neighbors dies.
2. Any live cell with two or three live neighbors survives.
3. Any live cell with more than three live neighbors dies.
4. Any dead cell with exactly three live neighbors becomes alive.

Each generation is calculated based on neighboring cell states, creating complex and emergent patterns over time.

## Controls

### Resolution

Controls the size of each rendered cell.

### Density

Controls the probability of cells being alive when a new simulation starts.

### Start

Begins the simulation.

### Stop

Pauses the simulation.

## Skills Demonstrated

* C# Development
* Algorithm Implementation
* Cellular Automata
* Object-Oriented Design
* Desktop Application Development
* WinForms UI Development
* Graphics Rendering
* State Management
* Software Architecture

## Future Improvements

* Simulation speed controls
* Save and load patterns
* Built-in pattern library (Gliders, Pulsars, Gosper Gun)
* Zoom and pan support
* Performance optimizations
* Additional visualization themes

## Status

Completed personal software engineering project demonstrating algorithm implementation, simulation systems, and desktop application development using C# and .NET.
