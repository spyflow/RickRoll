# Rickroll in C

This repository contains a program written in C that performs a "Rickroll" by opening the video of Rick Astley's "Never Gonna Give You Up" using the default media player on Windows.

## Description

The program is a fun demonstration that opens the Rick Astley video using the Windows media player. It showcases how to use system calls in C to interact with the operating system and launch external applications.

## Repository Contents

- `rickroll.c`: The main source file containing the C code.
- `README.md`: This documentation file.
- `LICENSE`: The project license.

## Requirements

To compile and run this program, you will need:

- A C compiler (e.g., `gcc`).
- A Windows operating system.

## How to Compile and Run

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/spyflow/RickRoll
   cd RickRoll
   gcc -o RickRoll rickroll.c -lshell32
   .\RickRoll.exe
   
