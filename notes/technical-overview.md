---
slug: github-config-note-technical-overview
id: github-config-note-technical-overview
title: Config
repo: justin-napolitano/config
githubUrl: https://github.com/justin-napolitano/config
generatedAt: '2025-11-24T18:33:11.333Z'
source: github-auto
summary: >-
  This repo contains system config files for shell environments, focusing on
  Fish and Zsh, along with a Starship prompt setup.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo contains system config files for shell environments, focusing on Fish and Zsh, along with a Starship prompt setup.

## Key Components
- **Fish Shell**: Config is in `config.fish`.
- **Zsh**: Config integrated with Oh My Zsh in `zshrc`.
- **Starship Prompt**: Customizations in `starship.toml`.

## Getting Started

### Prerequisites
- Install Fish or Zsh.
- Have Oh My Zsh for Zsh configurations.
- Starship prompt (optional, but recommended).

### Installation Steps
1. Clone the repo:
   ```bash
   git clone https://github.com/justin-napolitano/config.git
   cd config
   ```
   
2. Set up the config files:
   - For Fish:
     ```bash
     cp config.fish ~/.config/fish/config.fish
     ```
   - For Zsh:
     ```bash
     cp zshrc ~/.zshrc
     ```
   - For Starship:
     ```bash
     cp starship.toml ~/.config/starship.toml
     ```

Reload your terminal to see changes.
