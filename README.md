# anki-i3blocks

Script to display Anki Deck stats in i3blocks status bar


## Usage

```
[wanikani]
command=~/anki Spanish
label=ES
interval=600
```

Deck names must not include the character `'`.

You can also query multiple decks at once by separating the deck names
with semicolon.

```
[wanikani]
command=~/anki "Spanish;Spanish Books"
label=ES
interval=600
```
