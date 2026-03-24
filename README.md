# CryptoZombies - Blockchain Based Systems Assignment 🧟‍♂️🐱

This repository contains my progress through the CryptoZombies curriculum as part of the **Blockchain Based Systems** course in the **Computer Science (English)** program at **Tbilisi State University**.

## Project Overview
The project evolves from a simple zombie factory to a multi-contract system where zombies can interact with other smart contracts on the Ethereum blockchain.

## My Generated Zombies 🔗
* **Lesson 1 (Random Generation):** [View My First Zombie](https://share.cryptozombies.io/en/lesson/1/share/Zombie?id=Y3p8NjcxNjI0)
* **Lesson 2 (Kitty-Feeding):** [View My Cat-Zombie](https://share.cryptozombies.io/en/lesson/2/share/Zombie?id=Y3p8NjcxNjI0)

## Technical Concepts Applied 🧠

### Lesson 1: Basic Factory
* **State Variables & Structs:** Defining the core data structure of our zombies.
* **Hashing:** Using `keccak256` for pseudo-random DNA generation.
* **Events:** Notifying the frontend when a new zombie is created.

### Lesson 2: Contract Interaction & Inheritance
* **Inheritance:** Using `is` to split logic between `ZombieFactory` and `ZombieFeeding`.
* **Inter-Contract Communication:** Defining a `KittyInterface` to interact with the external **CryptoKitties** smart contract.
* **Visibility:** Understanding `internal` vs `private` to allow inherited contracts to access functions.
* **Data Location:** Managing `storage` pointers vs `memory` variables.
* **Multiple Return Values:** Handling complex function returns from external contracts.
* **Logic Gates:** Implementing `if` statements and string hashing comparisons.
