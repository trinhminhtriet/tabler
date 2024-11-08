# 📊 Tabler

```text

 _____         _      _
|_   _|  __ _ | |__  | |  ___  _ __
  | |   / _` || '_ \ | | / _ \| '__|
  | |  | (_| || |_) || ||  __/| |
  |_|   \__,_||_.__/ |_| \___||_|

```

📊 Tabler: A lightweight TUI tool to view, query, and navigate CSV, TSV, and Parquet data files.

![Screenshot](/images/screenshot.png "Screenshot")

## ✨ Features

## Features

- ⌨️ **Vim-style Keybindings** - Navigate efficiently with familiar, keyboard-driven controls.
- 🛠️ **SQL Query Support** - Perform advanced queries directly within the interface.
- 🗂️ **Multi-table Management** - Seamlessly load and switch between multiple data tables.
- 📊 **Broad File Format Support** - Compatible with CSV, Parquet, JSON, JSONL, Arrow, and Fixed-Width Formats (FWF).

## 🚀 Installation

To install **tabler**, simply clone the repository and follow the instructions below:

```bash
git clone git@github.com:trinhminhtriet/tabler.git
cd tabler

cargo build --release
cp ./target/release/tabler /usr/local/bin/
```

Running the below command will globally install the `tabler` binary.

```bash
cargo install tabler
```

Optionally, you can add `~/.cargo/bin` to your PATH if it's not already there

```bash
echo 'export PATH="$HOME/.cargo/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

## 💡 Usage

Run **tabler** with the following command to start cleaning your filesystem:

```sh
./tabler [options] [path]

```

## 🗑️ Uninstallation

Running the below command will globally uninstall the `tabler` binary.

```bash
cargo uninstall tabler
```

Remove the project repo

```bash
rm -rf /path/to/git/clone/tabler
```

## 🤝 How to contribute

We welcome contributions!

- Fork this repository;
- Create a branch with your feature: `git checkout -b my-feature`;
- Commit your changes: `git commit -m "feat: my new feature"`;
- Push to your branch: `git push origin my-feature`.

Once your pull request has been merged, you can delete your branch.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
