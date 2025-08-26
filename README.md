## Hi there! <img src="https://emojis.slackmojis.com/emojis/images/1536351075/4594/blob-wave.gif" width="25"/>👋

```bash
#!/usr/bin/env bash

# "Constructor" - initialize properties
name="Mohamed Hakim"
role="Web Developer"
languages=("ar_AR" "en_US" "fr_FR")
hobbies=("Doing CTFs" "Anime")

# "Method"
say_hi() {
  echo "Thanks for dropping by, hope you find some of my work interesting."
}

# Simulate an "object" by just using variables + functions
echo "Name: $name"
echo "Role: $role"
echo "Languages: ${languages[*]}"

say_hi
```
