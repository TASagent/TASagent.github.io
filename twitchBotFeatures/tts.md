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

* `/yougotthething` - The classic "You Got The Thing" sound effect

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

Users can set a custom voice that is used just for their TTS commands with `!set tts voice <ttsVoice>`.  To see samples of some of the various voices that are available, check out the <a href="https://cloud.google.com/text-to-speech/docs/voices">Google Cloud TTS Voices Page</a>.

* Valid US English Values:
    * Google Cloud TTS
        * `en-US-Standard-B`
        * `en-US-Standard-C`
        * `en-US-Standard-D`
        * `en-US-Standard-E`
        * `en-US-Standard-G`
        * `en-US-Standard-H`
        * `en-US-Standard-I`
        * `en-US-Standard-J`
    * Amazon Polly
        * `Ivy`
        * `Joanna`
        * `Kendra`
        * `Kimberly`
        * `Salli`
        * `Joey`
        * `Justin`
        * `Matthew`
* Valid UK English Values:
    * Google Cloud TTS
        * `en-GB-Standard-A`
        * `en-GB-Standard-B`
        * `en-GB-Standard-C`
        * `en-GB-Standard-D`
        * `en-GB-Standard-F`
    * Amazon Polly
        * `Amy`
        * `Emma`
        * `Brian`
* Valid Australian English Values:
    * Google Cloud TTS
        * `en-AU-Standard-A`
        * `en-AU-Standard-B`
        * `en-AU-Standard-C`
        * `en-AU-Standard-D`
    * Amazon Polly
        * `Nicole`
        * `Russell`
* Valid Indian English Values:
    * Google Could TTS
        * `en-IN-Standard-A`
        * `en-IN-Standard-B`
        * `en-IN-Standard-C`
        * `en-IN-Standard-D`
    * Amazon Polly
        * [`Aditi`](../Assets/Aditi_Sample.mp3)
        * `Raveena`

### Supported TTS pitches

Users can set a custom pitch that is used just for their TTS commands with `!set tts pitch <value>`.

* `x-low`
* `low`
* `medium`
* `high`
* `x-high`
