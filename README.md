# Rust energy project
This beginner project demonstrates a Rust-based implementation of various energy systems and fuels. It models different types of fuels, energy containers, and energy providers (like nuclear reactors and internal combustion engines) using Rust traits and generics. I also add some methods and a series of validation tests.

## Features
* **Fuel Types**: Joule, Calorie, and BTU are used to represent different units of energy. The project provides conversion methods between these units.
* **Fuel Providers**: NuclearReactor, InternalCombustion, OmniGenerator, GreenEngine, and BritishEngine are some of the energy providers implemented in the project.
* **Fuel Mixing**: Supports mixing of two different fuels to create a custom fuel blend with an energy density calculated as a weighted average.
