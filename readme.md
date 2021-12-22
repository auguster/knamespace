# Knamespace
A rapid namespace switching command line for kubectl.

# How to use

## Install
Copy the script to a folder in the PATH

```bash
sudo cp knamespace /usr/local/bin/
```

## List namespaces
Run knamespace without arguments:

```bash
knamespace
```

The current namespace is highlighted.

## Change namespace
Run knamespace with the namespace as argument:

```bash
knamespace default
```

# Todo
- [ ] autocomplete knamespaces
- [ ] find other suggestions (please post issues)

# Author
Dr Rémi AUGUSTE (<remi@weaverize.com>)