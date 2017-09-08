Apply the desired carbonized theme to pantheon-terminal by pasting the corresponding block of `gsettings` commands into the terminal.

The first set of themes feature a background with slight (5%) translucency, like the background in the default pantheon-terminal theme. The second set feature a solid background.

## translucent background

### carbonized-light

```
gsettings set org.pantheon.terminal.settings background 'rgba(255, 250, 224, 0.95)'
gsettings set org.pantheon.terminal.settings foreground '#363534'
gsettings set org.pantheon.terminal.settings cursor-color '#eb6200'
gsettings set org.pantheon.terminal.settings palette '#363534:#eb3b49:#35ab2b:#bf8000:#1391eb:#eb63b2:#00ab9d:#f5f1dc:#2b2b2b:#eb6200:#807f7c:#8a8983:#9e9c93:#9b63eb:#aba89b:#fffae0'
echo 'carbonized-light theme applied'
```

### carbonized-dark

```
gsettings set org.pantheon.terminal.settings background 'rgba(43, 43, 43, 0.95)'
gsettings set org.pantheon.terminal.settings foreground '#f5f1dc'
gsettings set org.pantheon.terminal.settings cursor-color '#eb6200'
gsettings set org.pantheon.terminal.settings palette '#363534:#eb3b49:#35ab2b:#bf8000:#1391eb:#eb63b2:#00ab9d:#f5f1dc:#2b2b2b:#eb6200:#807f7c:#8a8983:#9e9c93:#9b63eb:#aba89b:#fffae0'
echo 'carbonized-dark theme applied'
```

## solid background

### carbonized-light

```
gsettings set org.pantheon.terminal.settings background '#fffae0'
gsettings set org.pantheon.terminal.settings foreground '#363534'
gsettings set org.pantheon.terminal.settings cursor-color '#eb6200'
gsettings set org.pantheon.terminal.settings palette '#363534:#eb3b49:#35ab2b:#bf8000:#1391eb:#eb63b2:#00ab9d:#f5f1dc:#2b2b2b:#eb6200:#807f7c:#8a8983:#9e9c93:#9b63eb:#aba89b:#fffae0'
echo 'carbonized-light theme applied'
```

### carbonized-dark

```
gsettings set org.pantheon.terminal.settings background '#2b2b2b'
gsettings set org.pantheon.terminal.settings foreground '#f5f1dc'
gsettings set org.pantheon.terminal.settings cursor-color '#eb6200'
gsettings set org.pantheon.terminal.settings palette '#363534:#eb3b49:#35ab2b:#bf8000:#1391eb:#eb63b2:#00ab9d:#f5f1dc:#2b2b2b:#eb6200:#807f7c:#8a8983:#9e9c93:#9b63eb:#aba89b:#fffae0'
echo 'carbonized-dark theme applied'
```
