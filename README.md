
## A little description
Four Singletons are the most important part of the project

### ```CenterController```
It controls the behaviours of the app stores all the information needed in solo mode, including quizes, solo challenges, player info, and all the local data, notice that there is a ```PartyGame``` instance need to be initialized here using ```startPartyGame(ArrayList<String> names)``` method.

### ```BackgroundController```
This is the music system of the app

### ```AchievementSystem```
This holds all the information about how to categorize different identities and achievement info about a player, a lot of utility method can be found here

### ```ProfileController```
This is responsible for profile log changes.

## Utility Class
All the unility class can be found under ```extension``` package.
```PartyModeActivity``` and ```SoloModeActivity``` is the parents classes which mostly define the behaviours of activity bar.</br>
```ResourceTool``` is a class provide different assets for the same content under different identities
