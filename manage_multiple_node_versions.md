# How to manage multiple node versions:

## Step 1: Uninstall node (if any).

### note:

```diff
- make note of node current version before deleting.(cmd: "node --version") (ex: v16.15.1 or v14.17.0)
```

## Step 2: Install nvm:

```bash
https://github.com/coreybutler/nvm-windows/releases
```

Then download file npm-setup.zip and open file nvm-setup.exe

## Step 3: Download the nodejs versions you want to use. (cmd: "nvm install version_number"):

### Example:

```bash
nvm install 14.17.0
```

## Step 4: Switch to use the specified version:

```bash
nvm use [version_name]
```

## Bonus:

- List the node.js installations.

```bash
nvm list
```
