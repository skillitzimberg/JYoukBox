# jYoukBox

#### A multi-user song/video player

#### Scott Bergler, Chris Cahill & Ryan Leslie

## Description
The goal of this project is to create a Spotify-like song/video player. A user can create/generate a list of media to play. It will play through that list and the user can continue to add to the list as it plays. Ultimately, we would like multiple users to be able to add to the list from their own devices (tablets, phones, etc.).

This web app is advantageous over a normal YouTube playlist in a number of ways. Firstly, the web app requires no sign in and so can be shared among a number of users. Secondly, the web app can tell when a video added to the queue is not playable in an embedded environment - and it will skip over that video in the queue.

### Specifications:
##### Spec 1: Create a song object:
- [ ] **Expect:** input/output expected;

##### Spec 2: Create a new song:
- [ ] **Expect:** input/output expected;

##### Spec 3: Add song to play queue:
- [ ] **Expect:** input: a song/output: song added to queue;

##### Spec 4: console.log queue:
- [ ] **Expect:** input: console.log(queue)/output: list of songs added to queue;

### Things we'll need:
BUSINESS LOGIC
Jukebox object
  -queue array
  -history queue
  -now playing
  -skip songs which cannot be embedded
  -digests youtube.com and music.youtube.com URLs and retrieves only YoutTube VideoIDs
  * add media method

Song/Video object
  -title
  -duration
  -queueId
  * create song method

USER INTERFACE
Show queue on screen
Show now playing on screen
Show history on screen
Search for songs
Add songs



## Setup/Installation Requirements
To view or clone the code, go to [GitHub](https://github.com/skillitzimberg/JYoukBox).

The page is live at: [GitHub]( ).

## Known Bugs

## Support and contact details

Where to complain/suggest

## Technologies Used

HTML, CSS, & Javascript. More?

### License

Licensed under the MIT license.

Copyright (c) 2018 ** Authors **
