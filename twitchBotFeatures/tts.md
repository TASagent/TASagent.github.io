# TASagent TwitchBot TTS

Users with elevated permissions can trigger TTS with a simple chat command: `!tts This is how I can use TTS in chat`

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

## TTS Personalization

Users can set a custom voice that is used just for their TTS commands with `!set tts voice <ttsVoice>`.  To see samples of the various voices that are available, check out the <a href="https://cloud.google.com/text-to-speech/docs/voices">Google Cloud TTS Voices Page</a>.

### Supported TTS voices

* Valid Australian English Values:
    * `en-AU-Standard-A`
    * `en-AU-Standard-B`
    * `en-AU-Standard-C`
    * `en-AU-Standard-D`
* Valid Indian English Values:
    * `en-IN-Standard-A`
    * `en-IN-Standard-B`
    * `en-IN-Standard-C`
    * `en-IN-Standard-D`
* Valid UK English Values:
    * `en-GB-Standard-A`
    * `en-GB-Standard-B`
    * `en-GB-Standard-C`
    * `en-GB-Standard-D`
    * `en-GB-Standard-F`
* Valid US English Values:
    * `en-US-Standard-B`
    * `en-US-Standard-C`
    * `en-US-Standard-D`
    * `en-US-Standard-E`
    * `en-US-Standard-G`
    * `en-US-Standard-H`
    * `en-US-Standard-I`
    * `en-US-Standard-J`

## TTS Management

(For Mods)

* `!set tts enabled` - Enables TTS
* `!set tts disabled` - Disables TTS
* `!set tts timeout <timeout>` -  Sets the per-user TTS timeout (in seconds)