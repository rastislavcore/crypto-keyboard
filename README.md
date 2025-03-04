# US Crypto Keyboard for Mac

A customized US keyboard layout with cryptocurrency and financial symbols.

## Installation

### Using DMG (Recommended)

Download and mount the latest `.dmg` file from the [releases page](https://github.com/rastislavcore/crypto-keyboard/releases). Double-click the installer package to install.

### Manual Installation

Choose one of the following methods:

**Per User Installation:**

```sh
git clone https://github.com/rastislavcore/crypto-keyboard.git
cd crypto-keyboard/
cp crypto.bundle ~/Library/Keyboard\ Layouts/
cd .. && rm -rf crypto-keyboard/
```

**System-wide Installation:**

```sh
git clone https://github.com/rastislavcore/crypto-keyboard.git
cd crypto-keyboard/
sudo cp crypto.bundle /Library/Keyboard\ Layouts/
cd .. && rm -rf crypto-keyboard/
```

After installation, enable the keyboard layout in System Settings > Keyboard > Input Sources > + > Others > Crypto Keyboard.

### Special Characters

This keyboard includes special glyphs in the Private Use Area (PUA):

- Shift + Option + 1: Open-Source logo (uniE0A9)
- Shift + Option + 2: Digital Euro (uniE926)
- Shift + Option + 3: Digital Franc (uniEAFA)
- Shift + Option + 4: Digital Dollar (uniE227)
- Shift + Option + B: Satoshi Symbol (uniF1B6)

These glyphs require the [Machine font](https://github.com/rastislavcore/machine) to display properly.

### Modifications

Feel free to [fork](https://github.com/rastislavcore/crypto-keyboard/fork) the repository and modify the keyboard layout with [Ukulele](https://software.sil.org/ukelele) software.

### Layout

> State `Default`

![Default](images/state-none.png?raw=true "Default")

> State `Shift`

![Shift](images/state-shift.png?raw=true "Shift")

> State `Caps`

![Caps](images/state-caps.png?raw=true "Caps")

> State `Option`

![Option](images/state-option.png?raw=true "Option")

> State `Option - Shift`

![Option - Shift](images/state-option-shift.png?raw=true "Option - Shift")

> State `Option - Caps`

![Option - Caps](images/state-option-caps.png?raw=true "Option - Caps")

> State `Control`

![Control](images/state-control.png?raw=true "Control")

### License

This keyboard layout is licensed under the [CORE](LICENSE) License.
