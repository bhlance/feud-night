SOUNDS THAT COME WITH THE GAME
==============================

Put audio files (mp3, m4a or wav) in this folder, then list them in manifest.json.
Anything listed here is used automatically — no uploading in the Menu needed.

Slots (use these names inside manifest.json):

  aww    = disappointed audience reaction  (Fast Money, low scores)
  clap   = generous applause               (Fast Money, middle scores)
  cheer  = loud cheering                   (Fast Money, high scores)
  win    = song after every round
  game   = song when a team wins the game
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
