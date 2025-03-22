# Dotfiles

Just my personal config files. Nothing fancy, but they work for me.

## What's here

- `.vimrc` - Basic Vim settings (relative line numbers, 2-space tabs, etc.)
- `.zshrc` - Simple ZSH config with some aliases
- `setup.sh` - Links these files to your home directory

## Setup

```
git clone https://github.com/rohitrmohanty/dotfiles.git
cd dotfiles
chmod +x setup.sh
./setup.sh
```

# **!!! NOTE:** Running `setup.sh` will overwrite any existing `.vimrc` and `.zshrc` files in your home directory without asking. Please **BACKUP** your files before running the script!!!!

You'll need to edit the `.zshrc` file after setup to add your own paths.

## About the configs

The Vim config keeps things simple with:
- 2-space indentation
- Relative line numbers
- Some basic search settings

The ZSH config just has:
- A greeting
- An alias for listing files (`la`)
- A template for setting up project paths

Feel free to use these as a starting point for your own configs.

## License

See the [LICENSE](./LICENSE) file.
