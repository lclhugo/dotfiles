## 🚀 My Dotfiles

This repository contains my personal dotfiles, managed using the powerful [Chezmoi](https://www.chezmoi.io/) tool. Chezmoi is a command-line utility that helps you manage your dotfiles across multiple machines, ensuring consistency and making it easy to keep your configuration files in sync.

### 🌟 Features

- **Seamless Synchronization**: Chezmoi allows you to effortlessly synchronize your dotfiles across different machines, ensuring a consistent setup wherever you go.
- **Version Control**: Your dotfiles are stored in a Git repository, enabling you to track changes, revert to previous versions, and collaborate with others if needed.
- **Templating**: Chezmoi supports templating, allowing you to customize your dotfiles based on machine-specific variables or conditions.
- **Encryption**: Sensitive data can be encrypted and decrypted seamlessly, keeping your private information secure.
- **Dry Run**: Before applying any changes, you can perform a dry run to preview the modifications Chezmoi will make, giving you full control over the process.

### 🛠️ Installation

1. Install Chezmoi by following the [official installation guide](https://www.chezmoi.io/install/).
2. Clone this repository to your desired location:

```bash
git clone https://github.com/lclhugo/dotfiles.git ~/.dotfiles
```

3. Initialize Chezmoi and apply your dotfiles:
```bash
chezmoi init --apply ~/.dotfiles
```

### 🚀 Usage

After the initial setup, you can use the following commands to manage your dotfiles:

- `chezmoi edit` - Edit your dotfiles using your preferred editor.
- `chezmoi diff` - Show the differences between your dotfiles and the actual files on your system.
- `chezmoi apply` - Apply the changes from your dotfiles to your system.
- `chezmoi update` - Pull the latest changes from the Git repository and apply them.

For more advanced usage and customization options, refer to the [Chezmoi documentation](https://www.chezmoi.io/docs/how-to/).

### 🌈 Customization

This repository contains my personal dotfiles, but you can easily fork it and customize it to suit your needs. Feel free to modify the dotfiles, add or remove applications, and tweak the configurations to your liking.
