# Homebrew_Mac
Detaild steps to install and uninstall brew

### Remove the Xcode Command Line Tools

```
xcode-select -p
```

```
sudo rm -rf /Library/Developer/CommandLineTools
```

```
brew services stop
```

```
brew --prefix
```

```
/opt/homebrew
```

```
sudo rm -rf /opt/homebrew
```

```
echo $SHELL
```

```
nano ~/.bashrc
```

```
nano ~/.zshrc
```

```
export PATH="/usr/local/bin:$PATH"
```

```
export PATH="/opt/homebrew/bin:$PATH"
```

