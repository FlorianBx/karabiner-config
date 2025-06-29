# Karabiner Elements - Hyper Mode Configuration ⚡

A powerful keyboard configuration that transforms Caps Lock into a "Hyper Mode" key for enhanced productivity and vim-style navigation.

## 🚀 Core Feature

**Caps Lock → Hyper Mode/Escape**
- **Tap**: Escape key
- **Hold**: Activates Hyper Mode for custom shortcuts
- **Ultra-low latency**: 150ms threshold for responsive feel

## 🔥 Git Mode

**Hold 'g' → Git Mode**
- **Hold g + i** → My GitHub Issues (Raycast)
- **Hold g + p** → My GitHub Pull Requests (Raycast)
- **Hold g + r** → My GitHub Repositories (Raycast)
- **Hold g + c** → Create New Repository (Web)

## Quick Reference

### Navigation (Vim-style)
- `Hyper + h/j/k/l` → Arrow keys (left/down/up/right)
- `Hyper + w` → Word forward (Option + Right)
- `Hyper + b` → Word backward (Option + Left)

### App Launchers
- `Hyper + n` → Notes
- `Hyper + t` → Ghostty (Terminal)
- `Hyper + e` → Microsoft Edge
- `Hyper + v` → Visual Studio Code
- `Hyper + s` → Beeper Desktop
- `Hyper + m` → Spark Desktop (Mail)

### Workflow Shortcuts
- `Hyper + u` → Screenshot area to clipboard (Cmd+Ctrl+Shift+4)
- `Hyper + y` → Search YouTube via Raycast

### App-Specific Shortcuts

**Notes App**
- `Hyper + n` → New note (Cmd+N)

**Microsoft Edge**
- `Hyper + d` → Developer Tools (Cmd+Option+I)
- `Hyper + Cmd + k` → Previous tab (Ctrl+Shift+Tab)
- `Hyper + Cmd + j` → Next tab (Ctrl+Tab)

## Installation

1. Install [Karabiner Elements](https://karabiner-elements.pqrs.org/)
2. Import this configuration file
3. Enable the "main" profile
4. Start using Caps Lock as your new productivity key

## Configuration Structure

The configuration includes optimized rules with settings for ISO keyboard layout and low-latency response times.

### Timing Thresholds
- **Hyper Mode**: 150ms for activation/deactivation
- **Git Mode**: 200ms for activation by holding 'g'
