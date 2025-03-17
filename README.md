# Farsidic - A Simple CLI Farsi (Persian) Dictionary

Farsidic is a lightweight command-line interface (CLI) tool designed to provide quick and easy access to Farsi (Persian) dictionary definitions. 

## Features

- **Simple and Fast**: Quickly look up Farsi words directly from your terminal.
- **Lightweight**: Minimal dependencies and easy to install.
- **Cross-Platform**: Works on most Linux distributions.

## Installation

Farsidic can be installed on various Linux distributions using different methods. Below are the installation instructions for Debian-based, Red Hat-based, and Arch-based systems.

### Debian-Based Systems (e.g., Debian, Mint , Ubuntu)

1. **Download the `.deb` package**:
   - Go to the [Releases](https://github.com/mohammadrostamiorg/farsidic/releases) page.
   - Download the latest `.deb` package.

2. **Install the package**:
   ```bash
   sudo apt install farsidic-1.1-1.deb
   ```


### Red Hat-Based Systems (e.g., CentOS, Fedora)

1. **Download the `.rpm` package**:
   - Go to the [Releases](https://github.com/mohammadrostamiorg/farsidic/releases) page.
   - Download the latest `.rpm` package.

2. **Install the package**:
   ```bash
   sudo dnf install farsidic-1.1-1.noarch.rpm
   ```

### Arch-Based Systems (e.g., Arch Linux, Parchlinux , Manjaro)

Farsidic is available in the Arch User Repository (AUR). You can install it using an AUR helper like `yay` or `paru`.

1. **Install using an AUR helper**:
   ```bash
   yay -S farsidic
   ```
   or
   ```bash
   paru -S farsidic
   ```

2. **Manual installation from AUR**:
   ```bash
   git clone https://aur.archlinux.org/farsidic.git
   cd farsidic
   makepkg -si
   ```

## Usage

Once installed, you can use Farsidic directly from your terminal.

```bash
farsidic <word>
```

Replace `<word>` with the Farsi word you want to look up.

### Example

```bash
farsidic developer
```

Output :

```
"عکاسی ظاهر کننده عکس‌"
"توسعه دهنده‌"
"توسعه دهنده"
"گستران گر"
"محلول ظاهر کننده فیلم"
```


## Contributing

We welcome contributions! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.


## Support

If you find Farsidic useful, consider giving it a star on GitHub! Your support helps us improve the tool and add more features.

---

Enjoy using Farsidic! For any questions or issues, feel free to reach out or open an issue on the GitHub repository.
