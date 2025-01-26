# Hello World in Ruby

A minimal "Hello, World!" implementation in Ruby. Ruby is a dynamic, object-oriented programming language designed to be simple and productive, with an emphasis on making programming enjoyable.

## Installation

### macOS
Ruby comes pre-installed, but you can get the latest version with:
```bash
brew install ruby
```

### Linux
Ubuntu/Debian:
```bash
sudo apt-get update
sudo apt-get install ruby
```

Fedora/RHEL:
```bash
sudo dnf install ruby
```

### Windows
Download the installer from [RubyInstaller](https://rubyinstaller.org/).

## Running

Execute the script directly:
```bash
ruby main.rb
```

Or make it executable and run:
```bash
chmod +x main.rb
./main.rb
```

## Code Explanation

The program starts with a shebang line (`#!/usr/bin/env ruby`) that allows the script to be run directly on Unix-like systems when marked as executable. The `puts` method is one of Ruby's core methods for printing output, automatically adding a newline at the end of the string.
