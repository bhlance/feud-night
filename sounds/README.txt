SOUNDS THAT COME WITH THE GAME
==============================

Put audio files (mp3, m4a or wav) in this folder, then list them in manifest.json.
Anything listed here is used automatically — no uploading in the Menu needed.

Slots (use these names inside manifest.json):

  pre    = prelude music: plays on the setup page and repeats until you click Start new game
           (up to 3 minutes of the file is looped)
  aww    = disappointed audience reaction  (Fast Money, low scores)
  clap   = generous applause               (Fast Money, middle scores)
  cheer  = loud cheering                   (Fast Money, high scores)
  r1     = song after Round 1
  r2     = song after Round 2
  r3     = song after Round 3
  r4     = song after Round 4
  r5     = song after Round 5 and any later round
  win    = fallback song for any round that has no song of its own
  game   = song when a team wins the game (plays right when they reach the target score,
           in place of that round's song)
  fm     = song when a team wins Fast Money

Example manifest.json:

  {
    "aww": "aww.mp3",
    "clap": "applause.mp3",
    "cheer": "cheer.mp3"
  }

Order of preference for each sound:
  1. a file uploaded in the Menu (on that laptop)
  2. a file listed here
  3. the built-in computer-made version

Only use recordings you have the right to publish — this folder is part of the public web page.
