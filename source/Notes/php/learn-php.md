---
title: Learn PHP
date: 2023-02-17 20:57:07
---

## PHP, learn by doing

Using sqlite3 and PHP to create a simple web form

### Practice on my Ubuntu Laptop

```bash
# Install php, Current package version, on 2023-02-17, is v8.1.2
sudo apt install php-cli

# Install sqlite3
sudo apt install sqlite3

# Install libapache2-mod-php; a server-side, HTML-embedded scripting language (Apache 2 module)
sudo apt install libapache2-mod-php

# Install sqlite3 module
sudo apt install php8.1-sqlite3
```

## sqlite3

Some command

```SQL
.tables

.headers ON

CREATE TABLE user_table(id INTEGER PRIMARY KEY, username TEXT, description TEXT, points INT);

INSERT INTO user_table(username, description, points) VALUES('Alex', 'This is a good name', 52642);

select * from usertable;

DROP TABLE table01;

.exit
```
