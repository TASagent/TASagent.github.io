# TASagent TwitchBot TTS

TASagentPuppet features a simple TTS system.  Users with elevated permissions can trigger TTS with the command: `!tts This is how I can use TTS in chat`

## TTS sound effects extension

TTS supports the inline insertion of sound effects, used like this: `!tts Hey, TASagent!  Lookout!  Try not to /bao too hard`

### Super Mario World sound effects

* `/bao` - Yoshi spit sound
* `/midway` - Midway sound
* `/jump` - Mario's ordinary jump sound
* `/kick` - Mario kicks a koopa shell sound
* `/pipe` - Mario enters a pipe sound
* `/powerup` - Mario gets a cape powerup sound
* `/messageblock` - Mario hits a message block sound
* `/1up` - One Up sound
* `/balloon` - Mario gets a P-Balloon sound
* `/blargg` - Blargg sound
* `/bonus` - Musical outro at the end of the Bonus game
* `/bowser` - Sound of Bowser Returning
* `/breakblock` - Block-breaking sound
* `/bubble` - Bubble Popping sound
* `/caperise` - Cape swoop sound
* `/castleclear` - Castle Clear outro
* `/coin` - Coin collection sound
* `/courseclear` - Course Clear outro
* `/dragoncoin` - Dragon Coin collection sound
* `/egg` - Egg Hatching
* `/feather` - Mario gets a Feather
* `/fireball` - Mario launches a fireball
* `/gameover` - Game Over outro
* `/goaliris` - Level outro
* `/flyinghit` - Mario hit while flying
* `/keyhole` - Keyhole Exit sound
* `/correct` - Correct boss hit sound
* `/incorrect` - Incorrect boss hit sound
* `/died` - Mario Dies outro
* `/magikoopa` - Magikoopa casts a Beam
* `/pause` - Pause sound
* `/powerupappears` - Power up appears sound
* `/princess` - Princess cries for Help
* `/reserve` - Reserve Item Release sound
* `/save` - Save Menu sound
* `/scroll` - Scroll sound
* `/shellricochet` - Shell Ricochet sound
* `/spinjump` - Spin Jump sound
* `/springjump` - Spring Jump sound
* `/stomp` - Stomp sound
* `/stompbones` - Stomping on Bones
* `/stompchuck` - Stomping on a Chuck
* `/spinstomp` - Spin Stomp sound
* `/swim` - Swim sound
* `/switch` - Switch block hit sound
* `/thud` - Thwomp Thud sound
* `/vine` - Vine sound
* `/yoshimount` - Yoshi Mount sound
* `/yoshifire` - Yoshi Fire sound
* `/yoshihit` - Yoshi Hit sound
* `/yoshispit` - Yoshi Spit sound
* `/yoshistomp` - Yoshi Stomp sound
* `/yoshitongue` - Yoshi Tongue sound

### A Link To The Past sound effects

* `/itemfanfare` - The classic "You Got The Thing" item fanfare sound effect
* `/yougotthething` - An alias for the classic "You Got The Thing" item fanfare sound effect

### Final Fantasy 7 sound effects

* `/ff7alarm` - Alarm sound effect
* `/ff7battleswirl` - Intro battle swirl sound effect
* `/ff7chest` - Chest opening sound effect
* `/ff7chocobokweh` - Chocobo kweh sound effect
* `/ff7chocobowark` - Chocobo wark sound effect
* `/ff7chocobowark2` - Another chocobo wark sound effect
* `/ff7drumroll` - Drum roll sound effect
* `/ff7elevatording` - Elevator ding sound effect
* `/ff7falling` - A falling sound effect
* `/ff7founditem` - Item find sound effect
* `/ff7heartbeat` - Heart beat sound effect
* `/ff7hit` - Getting hit sound effect
* `/ff7hop` - Hopping sound effect
* `/ff7item` - Item use sound effect
* `/ff7jump` - Jump sound effect
* `/ff7kill` - Enemy kill sound effect
* `/ff7limit` - Limit break charged sound effect
* `/ff7menuaccept` - Accept menu sound effect
* `/ff7menubuzzer` - Buzzer menu sound effect
* `/ff7menucancel` - Cancel menu sound effect
* `/ff7menuequip` - Equip menu sound effect
* `/ff7menulearnlimit` - Learn limit break menu sound effect
* `/ff7menumove` - Move menu sound effect
* `/ff7menuset` - Set menu sound effect
* `/ff7menuuse` - Item use menu sound effect
* `/ff7notification` - Notification sound effect
* `/ff7phsring` - PHS ringtone sound effect
* `/ff7purchase` - Store purchase sound effect
* `/ff7run` - Escape combat sound effect
* `/ff7savepoint` - Savepoint activation sound effect
* `/ff7scan` - Scan sound effect
* `/ff7searching` - Rummaging sound effect
* `/ff7chant0` - A Sephiroth chant sound effect
* `/ff7chant1` - A Sephiroth chant sound effect
* `/ff7chant2` - A Sephiroth chant sound effect
* `/ff7chant3` - A Sephiroth chant sound effect
* `/ff7chant4` - A Sephiroth chant sound effect
* `/ff7chant5` - A Sephiroth chant sound effect
* `/ff7slots` - Slot machine sound effect
* `/ff7train` - Train sound effect
* `/ff7trainhorn` - Train horn sound effect
* `/ff7typing` - Typing sound effect
* `/ff7victoryfanfare` - Victory fanfare sound effect

Included are some convient aliases for the more noteworthy sounds

* `/alarm` - An alias for the alarm sound effect
* `/drumroll` - An alias for the drumroll sound effect
* `/chant` - An alias for the most memorable part of the Sephiroth chant sound effect
* `/longchant` - An alias for the two sequential chants, overlaid with proper timing
* `/sephiroth` - An alias for the Sephiroth chant sound effect
* `/victoryfanfare` - An alias for the victory fanfare sound effect
* `/buzzer` - An alias for the buzzer sound effect
* `/heartbeat` - An alias for the hearbeat sound effect
* `/chocobo` - An alias for the chocobo wark sound effect

## TTS Effect Markup

A few features have been added to allow greater control over the voicing of TTS text.

### Emphasizing

To emphasize a word or phrase in the sentence, surround it with underscores (`_`) or asterisks (`*`).  Example: `!tts What on _earth_ are you talking about?`.

### Whispering

The Amazon Polly voices support a whisper mode.  To whisper text, simply surround it with parentheses (`(text)`).  Exmaple: `!tts Oh my! (That was intense!)`.

### Pausing

To insert a pause in the TTS output, use `!pause(duration)`, where the duration is specified in milliseconds.  Example: `!tts Wait for it! !pause(3000) There it is`.


## TTS Voice Personalization

A number of features exist that allow you to personalize your TTS voice

### Supported TTS voices

Users can set a custom voice that is used just for their TTS commands with `!set tts voice <ttsVoice>`.  To hear a sample of any voice saying `!tts Hello, my name is <name>.  This is a test *with emphasis* (and a whisper). rrrrrrrrrrrrrrrrrrrrrrrrrrrrrr`, simply click on corresponding name below.

* Valid US English Values:
    * Google Cloud TTS
        * `en-US-Standard-B` ![Sample](../assets/en-US-Standard-B_Sample.mp3)
        * `en-US-Standard-C` ![Sample](../assets/en-US-Standard-C_Sample.mp3)
        * `en-US-Standard-D` ![Sample](../assets/en-US-Standard-D_Sample.mp3)
        * `en-US-Standard-E` ![Sample](../assets/en-US-Standard-E_Sample.mp3)
        * `en-US-Standard-G` ![Sample](../assets/en-US-Standard-G_Sample.mp3)
        * `en-US-Standard-H` ![Sample](../assets/en-US-Standard-H_Sample.mp3)
        * `en-US-Standard-I` ![Sample](../assets/en-US-Standard-I_Sample.mp3)
        * `en-US-Standard-J` ![Sample](../assets/en-US-Standard-J_Sample.mp3)
    * Amazon Polly
        * [`Ivy`](../assets/Ivy_Sample.mp3)
        * [`Joanna`](../assets/Joanna_Sample.mp3)
        * [`Kendra`](../assets/Kendra_Sample.mp3)
        * [`Kimberly`](../assets/Kimberly_Sample.mp3)
        * [`Salli`](../assets/Salli_Sample.mp3)
        * [`Joey`](../assets/Joey_Sample.mp3)
        * [`Justin`](../assets/Justin_Sample.mp3)
        * [`Matthew`](../assets/Matthew_Sample.mp3)
* Valid UK English Values:
    * Google Cloud TTS
        * [`en-GB-Standard-A`](../assets/en-GB-Standard-A_Sample.mp3)
        * [`en-GB-Standard-B`](../assets/en-GB-Standard-B_Sample.mp3)
        * [`en-GB-Standard-C`](../assets/en-GB-Standard-C_Sample.mp3)
        * [`en-GB-Standard-D`](../assets/en-GB-Standard-D_Sample.mp3)
        * [`en-GB-Standard-F`](../assets/en-GB-Standard-F_Sample.mp3)
    * Amazon Polly
        * [`Amy`](../assets/Amy_Sample.mp3)
        * [`Emma`](../assets/Emma_Sample.mp3)
        * [`Brian`](../assets/Brian_Sample.mp3)
        * [`Geraint`](../assets/Geraint_Sample.mp3)
* Valid Australian English Values:
    * Google Cloud TTS
        * [`en-AU-Standard-A`](../assets/en-AU-Standard-A_Sample.mp3)
        * [`en-AU-Standard-B`](../assets/en-AU-Standard-B_Sample.mp3)
        * [`en-AU-Standard-C`](../assets/en-AU-Standard-C_Sample.mp3)
        * [`en-AU-Standard-D`](../assets/en-AU-Standard-D_Sample.mp3)
    * Amazon Polly
        * [`Nicole`](../assets/Nicole_Sample.mp3)
        * [`Russell`](../assets/Russell_Sample.mp3)
* Valid Indian English Values:
    * Google Could TTS
        * [`en-IN-Standard-A`](../assets/en-IN-Standard-A_Sample.mp3)
        * [`en-IN-Standard-B`](../assets/en-IN-Standard-B_Sample.mp3)
        * [`en-IN-Standard-C`](../assets/en-IN-Standard-C_Sample.mp3)
        * [`en-IN-Standard-D`](../assets/en-IN-Standard-D_Sample.mp3)
    * Amazon Polly
        * [`Aditi`](../assets/Aditi_Sample.mp3)
        * [`Raveena`](../assets/Raveena_Sample.mp3)

### Supported TTS pitches

Users can set a custom pitch that is used just for their TTS commands with `!set tts pitch <value>`.

* `x-low`
* `low`
* `medium`
* `high`
* `x-high`
