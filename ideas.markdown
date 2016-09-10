# Ideas

Here are some hackathon/project/app/etc. I've had.

I've been working on this as a private Trello board for since 2013 or so.
But I thought it might be beneficial if I made it open.
I will probably never get to most of these, and a lot of them are half-baked.
Feel free to take any of them. Just let me know so I can add a link to your project!

## Web

- A web app that allows people to create music playlists as a community
- Instagram "competition" website
- A website that allows you to photoshop your friends' (but not your own) Instagram photos
- A recipe interpreter that substitutes unhealthy ingredients for healthy ones
- Cards Against Humanity Twitter bot
- A website that helps to stop domain squatters and to broker deals
- Spoken word/slam poetry/English education teaching app
- A website that lets people post potential events and see who would be interested in joining
  - A similar website, but for going to restaurants
- A web service that allows students to do inTRAnational school exchange (sort of like a long-term REU)
- "What's the world's favorite color?"
  A website that receives a person's favorite color and then adds it to the average color of the background of the website.
  It would also collect their location and map the color to a zone on the site.
- User-generated Facebook stickers
- Movember competition web app
- Web cam light detection app
- Politics web app for showing what bills are being voted on that affect users
- Markov chain-backed TODO list (what tasks do you need to complete today given previous tasks)
- Fizz buzz certification API
- Web app for introducing proof-based math to pre-college students
- Finish [Illuminati in the News](https://github.com/lozord/illuminati_in_the_news)
- Parallax design library
- Cretin: GitHub for non-code related purposes (e.g. poetry and creative writing)
- Vaporcoin: no-value cryptocurrency, cannot be used for anything
- DotStyles: Pinterest-like app that suggests music and fashion depending on your GitHub language activity
  - E.g. C -> 70s/80s style, JS -> 90s tech and hipsters
- Restarting Loadin
- Restarting D3 (SWE project)
- Restarting Moov
- Accessabeer: open web accessibility site that tells users if bars are handicap-accessible
- `Enhance your calm` (Express) error handler :arrow_right: Macintosh Plus :palm_tree:
- [CurrentCondition](https://www.reddit.com/domain/currentcondition.org/), but with [XScreenSaver](https://en.wikipedia.org/wiki/XScreenSaver)
- "Radio" on GitHub pages

## Games

- Galaga with stackable/collectable power-ups
- "You only have one bullet"
  - Inspired by a Ludum Dare theme a while back
  - Could work really well in a post-apocalyptic or stealth scenario
- [Pool's Closed](http://knowyourmeme.com/memes/pools-closed): The Game
  - A team-based multiplayer game wear you work together to keep other teams out of the pool
  - Like King of the Hill in TF2 :heart:
- If you look at the HTML of webpages, it often very ugly (WRT indentation)
  - This should be used to create random worlds for a game
- Reviving the apocryphal [UPL](http://upl.cs.wisc.edu) Shadow Children game
- Strobe game
  - A 2D turn-based multiplayer game which chunkifies gameplay into quanta
  - Users buffer input while an "update timer" counts down
  - The game takes place on a symmetric map with "base" structures
  - The guts would be similar to [Xanadu](https://github.com/lozord/xanadu), but more like TF2/Battlefront
  - The goal of the game would be to capture enemy bases
- A game about keeping one single secret from NPCs
- "Vectors on a plane game"
  - I'm pretty sure this has been done before
  - Players attempt to "sail" a token through a grid, and the token's movement is defined by vectors on the map
- Create a 2D "multiple choice" game engine
  - Kind of like a low-budget, hacky, Telltale game
- Point-and-click game engine that just consumes a static HTML/Markdown file for how the game works
- __2D__ Rubik's Cube web game
  - Responsive (works perfectly on mobile)
  - Animated movements (time for CSS...)
  - Instead of 3D, the cube would be cut into different shapes (think of peeling an orange)
- A collaborative teamwork programming game similar to telephone
- Implement Guitar Hero controller processing to "play guitar"
  - Use beat analysis and pattern matching to create sample loops for instruments
  - Integrate with Sonic Pi
  - Integrate with Pianobar
- A Vaporwave-themed crypto puzzle game
  - Graphic novel-style ASCII art
- Implement a card counting algorithm
- An evolving (maze/platformer) game
  - When someone beats a level, a new one is procedurally generated and added to the "canon" of the game
  - Everyone plays the same levels, but new ones have to be unlocked first!
- Space rover resource/pipe direction game
  - Challenge: implement it in a single HTML `<table>`
  - Updates on every keypress
- [Strikers 1945](https://en.wikipedia.org/wiki/Strikers_1945)-style game
  - up to 4 players
  - "borderless" horizontal movement
  - different types of levels/missions
- [Cool Games Inc.](http://www.polygon.com/coolgamesinc) Ideas
  - Permadeath, unliscensed, multiplayer wrestling game
  - Procedurally generated shower UI VR game
  - One night (real time) to make $1M
- Drunken sailor game
  - Drunken Sailor tries to escape 1-dimensional street while being chased by 2 constables and 1 sheriff
  - The DS wins if he escapes
  - The police win if they contain him with `[C,S,DS,C]` (or reflection) formation
- A similar game as the Drunken Sailor one mentioned above, but with two players or teams trying to catch eachothers' sheriff
  - Perhaps game board is a circle instead of a strip
- Number zombie game
  - start with `x` health, lose `y` health per move
  - grid with blank cells and numbered cells
  - zombie moves `y` spaces each turn
  - when you move onto a number, `y` becomes that number, and `y` is added to your health
  - ergo, higher numbers move you faster but lose more health
  - the numbers in the grid move at their own speed as well
  - numbers try to avoid you
  - 0 will kill you. Numbers are 0-9?
- A medieval bard game that uses Guitar Hero/Rockband controllers
- Spacebard: a sci-fi version of the game above
  - Possibly JRPG/Pokemon style gameplay and combat?

## Compilers and Languages

- Prolog^Rails framework
  - Basically a Prolog-style database wrapper using Rails
- Medusa: Python to Ruby compiler
  - Snazzy name, right?
- D to C++ compiler
- asm.js to x86 (or MIPS :smile:)
- Prepositions to "dot" notation
  - `append de array` instead of `array.append`
  - This is completely useless but very funny
- Postgres as a programming language
- Bycom: a programming language (factory) designed __by committee__
  - This would be like MadLibs but for language design
- Blintz: a linter for the visually impaired
  - Takes errors with code and transforms it so it can be piped into something like `say`
- Add "Allman style" bracing to Io, `else if` lists, single quote strings
  - I messed around with Io back in the summer of 2014 and really liked it
  - I think these would be cool features/additions to propose
- The ultimate compiler: find a way to translate simple English instructions into code
  - I feel like this is more of a linguistic and philosophical problem than computational
- Make a programming language that is the unholy union of [Rail](https://esolangs.org/wiki/Rail) and [Factorio](https://www.factorio.com/)

## Art and Music

- Actually implement Autoszkiewicz
  - Attempted [here](https://github.com/LOZORD/autoszkiewicz)
- Transparent/window-like TV screen that dynamically glitches whatever is behind it (i.e. looks at contours)
  - Should also detect motion and sound to produce different effects
- Solar-powered robot whose goal is to be in the dark/shade
- Pure HTML/CSS responsive silhouette
- Pure HTML/CSS responsive self-portrait
- A library to dynamically generate arabesques (Middle Eastern geometric tile art)
  - [Wallpaper groups](https://en.wikipedia.org/wiki/Wallpaper_group)
  - [HTML Canvas Patterns](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors#Patterns)
  - Might be also good to do with cosmic bowling/90's graphic patterns
- Lost and stolen art reporting and verifying site
- Dueling banjos for Sonic Pi
  - Extra points if the two computers pass their code between each other and evolve it over time
  - Read [this](http://joearms.github.io/2016/01/28/A-Badass-Way-To-Connect-Programs-Together.html)
- Integrate [Mittsu](https://github.com/jellymann/mittsu) into Sonic Pi for music visualization
  - Plan visualization based on Sonic Pi input code (e.g. beat, instrumentation, complexity, etc.)
- Lorem ipsum image generator
- "OpenGL/WebGL scene to ASCII" library
  - Shoutout to [zeroeth](https://github.com/zeroeth) and [this video](http://sol.gfxile.net/litterae/)

## Mobile

- A dating app that uses the Stable Marriage Algorithm
- A phone app that simplifies DJing for radio DJs
- A phone app that does supports the trend of taking pictures of your food
  - Would bring in information about menus, nutritional info, ingredients,
    recipes, similar meals and photos, and suggestions
- A phone app whose goal is to replace the business card
  - Could add dynamic features such as stock prices or map integration
- Security and permissions through selfies (groan)
- A messaging game where players have to guess each others' secret words
  - The twist is that if a text contains a certain player's secret word,
  the player will not see that message.
  - Sort of like reverse Taboo?
- Uber for Ninjas: hire people to find other people for you
  - E.g. you and your friend are mutually lost at a large event
- Mobile keyboard for learning a new human language

## Artificial Intelligence, Machine Learning, and Natural Language Processing

- Can we program gullibility?
  A "simple" CLI program (would probably ressemble Prolog) that would represent a gullible AI.
- An NLP CLI tool that colorizes and categorizes output for the Linux `cal` command.
- A program that translates common English to Carnegie's simplified English.
- A Twitter bot whose sole job is, when given another user's handle, to produce humorous profile picture edits or insults.
- An "iconoclastic" Twitter bot: find stuff with positive remarks/reviews and create new negative Tweets
- A CSS/JS extension for outputting formatted images from [this library](https://github.com/jaysalvat/jquery.facedetection/tree/master)
- Derive a typeface using an evolutionary algorithm. It should go from square blocks to readable letters.
  - Attempted by me [here](https://github.com/LOZORD/octothorpe)
  - [This project](https://github.com/nodebox/opentype.js) might be useful
- Dance party music mixer AI
- Given an emoji "sentence," transform it into a likely English sentence
  - See [whatmoji.com](http://whatmoji.com/) for a similar idea

## Hardware

- Parabolic fan/umbrella with solar cells so that it can track the sun and
  properly block it
- (Open source) lazer tag
- Computer vision theremin
- Nod ring/Myo armband for manipulating CAT scans and 3D radiology images
- Using Walkmans and tape recorders as portable storage drives

## Miscellany

- Terminal-based guitar tab (teacher)
- CLI app that inspects directories to determine an "optimal" file/subdirectory
  hierarchy
- Algorithm: Given a phone number, can its digits represent any (English) words via T9?
- A cryptocurrency used (exclusively) in the competitive gaming community
  - Use case: "money matches"
- Look into the modularization of hospital rooms
  - I.e. room design and objects would better reflects patients' needs
- Store an encrypted password file using git
  - This would basically be like using keepass with remote SCM
- Using Slack/[slackcat](https://github.com/rlister/slackcat) as an SCM tool
- [Reverberation Radio](http://reverberationradio.com) CLI like `pianobar`
  - I attempted this with [reve.rb](https://github.com/LOZORD/reve.rb)
  - Use React Native for non-CLI?
- A human-readble (i.e. memorizable) hash translator
  - For example, instead of the latest download of _ having a SHA of 12345,
  it would be "awesome antelope" or something like that
  - Check [this](https://tools.ietf.org/html/rfc1751) out
- Reviving the Geek Code
  - Larry Wall's [Geek Code](http://www.wall.org/~larry/ungeek.html)
  - Possibly creating a friendship/dating app off of Geek Code :laughing:
- `sqalloc` - a SQL interface for memory allocation in C (or Go?)
  - my attempt at taking the whole transactional memory thing a little too seriously
  - it basically turns your available heap chunk into a database with tables for different types
  - might be a worse version of slab allocation :grinning:
