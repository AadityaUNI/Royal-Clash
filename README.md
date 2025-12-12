# Royal-Clash

A tower defense strategy game built in C++ using SFML (Simple and Fast Multimedia Library). Battle against another player by deploying units, managing elixir, and destroying enemy towers! 

## Features

- **Main Menu** - Navigate between Play, Stats, and Exit options
- **Battle Mode** - Deploy units and attack enemy towers in real-time combat
- **Stats Tracking** - View player wins and losses
- **Deck System** - Manage and deploy units from your deck
- **Elixir Management** - Strategically spend elixir to deploy units

## Screenshots:
<img width="1169" height="571" alt="image" src="https://github.com/user-attachments/assets/7924609a-4997-471d-9125-d90313604b5c" />
<img width="1168" height="576" alt="image" src="https://github.com/user-attachments/assets/7dbafdc1-a44d-4679-873c-34aab5479375" />

## Prerequisites

Before running the game, ensure you have **SFML** installed on your system. 

### macOS (Homebrew)
```bash
brew install sfml
```

### Linux (Ubuntu/Debian)
```bash
sudo apt-get install libsfml-dev
```

### Linux (Fedora)
```bash
sudo dnf install SFML-devel
```

## Getting Started

### Quick Start (Pre-compiled)

1. Clone the repository: 
   ```bash
   git clone https://github.com/AadityaUNI/Royal-Clash.git
   cd Royal-Clash
   ```

2. Run the game:
   ```bash
   ./royal_clash
   ```

### Building from Source

If you need to compile the project yourself:

1. Clone the repository:
   ```bash
   git clone https://github.com/AadityaUNI/Royal-Clash.git
   cd Royal-Clash
   ```

2. Build the project:
   ```bash
   make all
   ```

3. Run the game:
   ```bash
   ./royal_clash
   ```

### Other Make Commands

| Command | Description |
|---------|-------------|
| `make all` | Build the project |
| `make clean` | Remove object files |
| `make fclean` | Remove object files and executable |
| `make re` | Rebuild the project from scratch |

## Project Structure

```
Royal-Clash/
├── include/          # Header files
├── src/              # Source files
│   └── Units/        # Game unit implementations
├── Makefile          # Build configuration
├── stats.txt         # Player statistics
└── royal_clash       # Compiled executable
```

## Requirements

- **C++17** or later
- **SFML 3.0+**
- **g++** compiler
