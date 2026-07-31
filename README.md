# <p align="center">taro</p>

<p align="center">
  <img src="https://img.shields.io/badge/Available_for-Auro-4c1" alt="Available for Auro" />
  <a href="https://vibescale.github.io/#4">
    <img src="https://vibescale.github.io/badge-bar/4.svg" alt="4/6 LGTM Copilot | Vibescale" />
  </a>
</p>

<p align="center">
  <i>A TUI launcher program to start apps you add.</i>
</p>

---

## Overview
taro is a TUI (text-based user interface) launcher program that enables users to start applications through a command-line interface. The launcher provides an intuitive interface for managing and launching your favorite apps and games from a single, centralized location.

## Features
- Intuitive keyboard navigation for quick app access
- Mouse hover selection support for graphical terminals
- Search functionality to find apps instantly
- Grid-based layout with customizable spacing
- Supports both light and dark terminal themes

## Getting Started

### Prerequisites
- A Unix-like operating system
- A compatible terminal emulator
- Python 3.x (for the Textual framework)

### Installation
1. Ensure you have Python 3.x and pip installed on your system
2. Install the required dependencies:
   ```bash
   pip install textual
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/EliCJonas/taro.git
   ```
4. Navigate to the taro directory:
   ```bash
   cd taro
   ```

### Usage
1. Configure your apps by editing the app configuration file
2. Launch taro:
   ```bash
   ./taro
   ```
3. Use the arrow keys to navigate, Enter to launch, and Escape to quit
4. Use `Ctrl+F` to search for an app

## Configuration
App entries are stored in a configuration file or directory that you can manually edit. Add new entries by specifying the app name, command path, and optional icon for display in the launcher.

## Integration
taro is designed to integrate with the Auro package manager, allowing seamless installation of new apps and updates. Use Auro to manage your app library directly from the terminal.