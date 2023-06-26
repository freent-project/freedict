# FreeDict

FreeDict is an open-source dictionary written by contributors to the FreeNT Project.
We are attempting to get **over 100 languages** in the dictionary. We started off with
writing a dictionary in the English language and are constantly expanding overtime.

## Why does this exist?

You may have heard of, e.g. [Wiktionary](https://wiktionary.org), a free dictionary
from the Wikimedia Foundation. We're not going to get into other dictionaries;
let's just focus on FreeDict.

FreeDict was originally intended for spell-checking text on OpenWindows platforms.
It can, however, be used a reference source for schools, businesses, and people
learning new words.

## Add new definitions

Definitions are stored as basic YAML files that look like this:

```yaml
name: "FreeNT"
definitions:
   - type: noun
     tags: ['computing', 'proper']
     definition: 'a free and open-source kernel written by the FreeNT Project.'
     example: 'If FreeNT didn't exist, open-source would die!'
   - type: 'verb'
     tags: ['computing']
     definition: 'to install a FreeNT-based operating system, such as OpenWindows, on a computer.'
     example: 'After joining the open-source world, I FreeNTed my computer'
```

At least one definition can be defined in FreeDict entries.
