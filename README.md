# config

System configuration files for shell environments and prompt customization.

## Features

- Configuration for Fish shell (`config.fish`)
- Starship prompt customization (`starship.toml`)
- Zsh configuration with Oh My Zsh integration (`zshrc`)

## Tech Stack

- Shell scripting (Fish, Zsh)
- Starship prompt configuration (Rust-based prompt)

## Getting Started

### Prerequisites

- Fish shell or Zsh installed
- Oh My Zsh installed (for Zsh configuration)
- Starship prompt installed (optional, for prompt customization)

### Installation

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/config.git
cd config
```

Copy or source the configuration files to your home directory or appropriate config locations:

- For Fish shell:
  ```bash
  cp config.fish ~/.config/fish/config.fish
  ```

- For Zsh:
  ```bash
  cp zshrc ~/.zshrc
  ```

- For Starship prompt:
  ```bash
  cp starship.toml ~/.config/starship.toml
  ```

Reload your shell or start a new terminal session to apply changes.

## Project Structure

```
config/
├── config.fish       # Fish shell configuration
├── starship.toml     # Starship prompt configuration
└── zshrc             # Zsh shell configuration with Oh My Zsh
```

## Future Work / Roadmap

- Add README documentation for individual config files
- Include installation scripts for automated setup
- Expand support for other shells (e.g., Bash)
- Add backup and sync options for config files
- Integrate versioning for config changes
