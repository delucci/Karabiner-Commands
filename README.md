# Karabiner-Commands

A collection of Karabiner-Elements shortcut configurations for the Majestouch Xacro M10SP tenkeyless keyboard.

## Overview

This repository contains JSON files for use with [Karabiner-Elements](https://karabiner-elements.pqrs.org/), a key remapping tool for macOS. It provides custom shortcuts specifically designed to improve productivity on compact tenkeyless keyboards.

## Configuration Files

### 1. map_arrows.json - Arrow Key Mapping

Control arrow keys using Left Option + keys around the semicolon.

**Key Mappings:**

- `Left Option + ;` → `↑` (Up Arrow)
- `Left Option + .` → `←` (Left Arrow)
- `Left Option + /` → `↓` (Down Arrow)
- `Left Option + \` → `→` (Right Arrow) _Note: On JIS keyboards, this is the `ろ` key_

**Benefits:**

- Navigate without moving your right hand from home position
- Improved efficiency for text editing and navigation
- Better arrow key access on tenkeyless keyboards

### 2. sleep_mac.json - Mac Sleep Shortcut

**Key Mapping:**

- `Left Command + Left Option + Delete` → Put Mac to Sleep

**Benefits:**

- Quick way to put your Mac to sleep
- More convenient than using the power button

## Installation

1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
2. Open Karabiner-Elements
3. Go to the "Complex Modifications" tab
4. Click "Add predefined rule"
5. Import the configurations:

**Option A: Clone this repository**

- Copy each JSON file to `~/.config/karabiner/assets/complex_modifications/`
- Restart Karabiner-Elements
- Enable the rules from "Add rule"

**Option B: Import from web**

- Click "Import more rules from the Internet (Open a web browser)"
- Use the provided URLs (see releases)

## Compatible Keyboards

- Majestouch Xacro M10SP
- Other tenkeyless keyboards
- Both JIS and US layout keyboards

## Requirements

- macOS
- Karabiner-Elements installed
- Note: Key mappings may conflict with other application shortcuts

## License

MIT License

## Contributing

Bug reports and feature requests are welcome via Issues. Pull requests are also appreciated.
