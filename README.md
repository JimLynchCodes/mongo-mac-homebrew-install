# Mongo Mac Homebrew Install

Commands that worked for me circa 10/2023.

---

## Part 1: Install MongoDB Dev Tools

First, tap the proper cask:
```bash
brew tap mongo/brew
```

Then install mongo community edition:
```bash
brew install mongodb-community
```

---

## Part 2: Start MongoDB Running

Start mongo community edition running locally:
```bash
brew services start mongodb/brew/mongodb-community
```

---

## Part 3: Usage

Go into mongo daemon with mongod:
```bash
mongod
```
