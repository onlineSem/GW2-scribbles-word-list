# Scribbles word list for Guild Wars 2
_A project for fun guild evenings._

<img src="misc/fractal_boss.PNG" width="200" alt="Great fun, as you can see." /><img src="misc/glenna.png" width="200" alt="Mouse art, best art." /><img src="misc/beetle.png" width="200" alt="Oh god, it was tough to find out this thing was a beetle." />

> Vous parlez français ? Allez lire **README_fr.md**

My love for classics and my GW2 guild planted the seed of a fun idea:  **Guild Wars 2-themed Pictionaries**!

I tried at first to create a list for [this online pictionary client that allows custom lists](skribbl.io) but after a few games, we noticed that my list was not so long and that we were doing the same words again and again. Then, we thought, other guilds might be interested, right? What about sharing this project with other GW2 players from all over the world? 

* [How to use](#how-to-use) 
* [How to contribute](#how-to-contribute)
* [Translations](#translations)
* [Release notes](#release-notes)

## Hows 

### How to use
Navigate into the folders in order to get either the file with all the words (the `ALL_WORDS.md`) or the specific categories you want. 
Copy/paste the text into a pictionary client. I already told you about _skribbl.io_ but this one allows online up to 12 players. 
#### On _skribbl.io_
* Create a private game
* In the text area, simply paste the words you wanna use. 
* Don't forget to check "Only use custom words"

### How to contribute

**Please use the correct branch :**

![develop](misc/branch.PNG)

Edit the files with your words, this will create a request. I'll analyze this request and add it if the content is correct. You can add new files in markdown (`.md`) format if you think of some new subcategories. 

Each word should be separated from the others with a comma. Carriage returns are not taken into account but I recommend doing some in order to have a better looking file. 

Example: 
```
sylvari,norn,charr,human,asura,
kodan,krait,skritt,
```

Please follow the project tree: 
```BASH
├── [Language]
|   ├── Regular
|   |   ├── Alive stuff
|	|   ├── Places
|	|   ├── Objects
|	|   ├── Abilities and actions
|	|   ├── Miscellaneous
|   ├── Expert
|   |   ├── Alive stuff
|	|   ├── Places
|	|   ├── Objects
|	|   ├── Abilities and actions
|	|   ├── Miscellaneous
|   ├── Custom
|	|   ├── TAG - YourGuildName
```
**Note:** I know that difficulty depends on the point of view, but keep in mind that some stuff are really hard to guess and draw: a spider vs Vlast, Lion's Arch vs Orr's magician tower. 

#### WARNING
Be careful with words using `'` character, it won't work in _skribbl.io_ (maybe other clients), and would look like this: 
```
                     word: Lion's Arch
how it appears in skribbl: Lions Arch
``` 

## Translations 
There is not yet a folder for your language in the project? Don't hesitate to ask for it! 

## Release notes

#### 0.2
French words are released. English words are coming shortly. 
