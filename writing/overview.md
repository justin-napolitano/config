---
slug: github-config-writing-overview
id: github-config-writing-overview
title: 'Simplifying My Shell: Insights into the `config` Repository'
repo: justin-napolitano/config
githubUrl: https://github.com/justin-napolitano/config
generatedAt: '2025-11-24T17:12:06.636Z'
source: github-auto
summary: >-
  I’ve spent a fair amount of time tinkering with my shell environments, and
  that led me to create a repository that holds all my system configuration
  files: welcome to my `config` repo. This is where I centralize my
  configurations for Fish and Zsh shells, along with a tailored Starship prompt
  setup.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: writing
entryLayout: writing
showInProjects: false
showInNotes: false
showInWriting: true
showInLogs: false
---

I’ve spent a fair amount of time tinkering with my shell environments, and that led me to create a repository that holds all my system configuration files: welcome to my `config` repo. This is where I centralize my configurations for Fish and Zsh shells, along with a tailored Starship prompt setup.

## What’s the Point?

At the core, this repository exists to make my life easier—plain and simple. Over time, I’ve collected various configurations that help me streamline my environments. Having a consolidated location for these files means I can easily share, adapt, and maintain my setups without scouring through scattered directories.

### Why Fish and Zsh?

I’m a huge fan of both Fish and Zsh. Each has its strengths, and I didn’t want to limit myself to one. Fish gives me a modern, user-friendly experience, while Zsh (especially with Oh My Zsh) offers a ton of customization options. The combination lets me customize my workflow as needed based on what I’m working on at the moment.

## Key Design Decisions

Here are some of the things I considered when building the repo:

- **Separation of Config Files**: I’ve grouped configurations logically. This keeps it clean and easy to extend in the future.
  
- **Custom Starship Prompt**: The Starship prompt is efficient and offers plenty of customization. I wanted my prompt to not only look good but also provide useful information at a glance.

- **Easy Setup**: I prioritized ease of installation. By providing clear commands, I ensure that anyone else can replicate my setup without headaches.

### Features Overview

Here are the cool pieces the repo has to offer:

- **Fish Shell Configuration**: `config.fish` is where I store my Fish shell settings. It’s configured for optimal usability and performance.
  
- **Zsh Configuration**: `zshrc` is tailored for Oh My Zsh, giving it all the bells and whistles I like.

- **Starship Prompt Customization**: My `starship.toml` file configures Starship to capture my style while maintaining functionality.

## Tech Stack

My toolkit for this repo is straightforward:

- **Shell Scripting**: I use Fish and Zsh—there’s no better way to customize your terminal than with shell scripts.
  
- **Starship Prompt**: Built in Rust, Starship adds performance and a snappy feel.

## Getting Started

If you want to dive into the repo, here’s a quick rundown:

### Prerequisites

To set things up, you need:

- Fish shell or Zsh installed
- Oh My Zsh (only if you’re using the Zsh config)
- Starship prompt (optional, but recommended for the prompt enhancements)

### Installation Steps

Setting it up is a breeze. Here’s how I typically do it:

1. Clone the repo:
   ```bash
   git clone https://github.com/justin-napolitano/config.git
   cd config
   ```

2. Copy the configuration files to your desired locations:
   - **For Fish shell**:
     ```bash
     cp config.fish ~/.config/fish/config.fish
     ```

   - **For Zsh**:
     ```bash
     cp zshrc ~/.zshrc
     ```

   - **For Starship**:
     ```bash
     cp starship.toml ~/.config/starship.toml
     ```

3. Reload your shell or fire up a new terminal session. Easy, right?

## Project Structure

Here’s a peek at how I’ve organized the files:

```
config/
├── config.fish       # Fish shell configuration
├── starship.toml     # Starship prompt configuration
└── zshrc             # Zsh shell configuration
```

This neat structure means I can easily add new configurations or update existing ones whenever I want.

## Tradeoffs

Every design comes with its sacrifices. Here are a few I’ve considered:

- **Customization vs. Complexity**: The more tailored my configs are, the more complex they can get. I try to keep them manageable.
  
- **Efficiency vs. Usability**: Certain features can slow down the shell, especially when using multiple plugins. Balancing speed and functionality is crucial for a good user experience.

## What’s Next?

I’m always looking for ways to iterate on my work. Here are some updates I’m eyeing for the future:

- **More Documentation**: I want to add detailed README notes for each config file. Not everyone is familiar with every setting, and I’d like to clarify that.
  
- **Automated Install Scripts**: Automated setups are a game-changer. I want to make it even easier for others (and myself) to get started.

- **Support for Other Shells**: While I mainly use Fish and Zsh, I’m considering adding compatibility for Bash. 

- **Backup/Synchronization Features**: Keeping configs in sync across devices can be a hassle. Possible solutions for this are definitely on my roadmap.

- **Versioning Changes**: I want to track changes in the configs, making it easier to roll back if things go haywire.

## Stay Connected

If you find this interesting, I regularly share updates and insights on social platforms like Mastodon, Bluesky, and Twitter/X. Feel free to follow along for more on shell customizations and more!

---

So there you have it: an unveiled look at my `config` repo. I hope you find it as useful as I do. Happy customizing!
