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

| Service | Name | Example |
|---------|------|---------|
|Google Cloud (US)|`en-US-Standard-B`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-B_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-US-Standard-C`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-C_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-US-Standard-D`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-D_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-US-Standard-E`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-E_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-US-Standard-G`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-G_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-US-Standard-H`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-H_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-US-Standard-I`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-I_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-US-Standard-J`|<audio controls style="height: 30px"><source src="../assets/en-US-Standard-J_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Amazon Polly (US)|`Ivy`             |<audio controls style="height: 30px"><source src="../assets/Ivy_Sample.mp3"              type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Joanna`          |<audio controls style="height: 30px"><source src="../assets/Joanna_Sample.mp3"           type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Kendra`          |<audio controls style="height: 30px"><source src="../assets/Kendra_Sample.mp3"           type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Kimberly`        |<audio controls style="height: 30px"><source src="../assets/Kimberly_Sample.mp3"         type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Salli`           |<audio controls style="height: 30px"><source src="../assets/Salli_Sample.mp3"            type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Joey`            |<audio controls style="height: 30px"><source src="../assets/Joey_Sample.mp3"             type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Justin`          |<audio controls style="height: 30px"><source src="../assets/Justin_Sample.mp3"           type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Matthew`         |<audio controls style="height: 30px"><source src="../assets/Matthew_Sample.mp3"          type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Google Cloud (GB)|`en-GB-Standard-A`|<audio controls style="height: 30px"><source src="../assets/en-GB-Standard-A_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-GB-Standard-B`|<audio controls style="height: 30px"><source src="../assets/en-GB-Standard-B_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-GB-Standard-C`|<audio controls style="height: 30px"><source src="../assets/en-GB-Standard-C_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-GB-Standard-D`|<audio controls style="height: 30px"><source src="../assets/en-GB-Standard-D_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-GB-Standard-F`|<audio controls style="height: 30px"><source src="../assets/en-GB-Standard-F_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Amazon Polly (GB)|`Amy`             |<audio controls style="height: 30px"><source src="../assets/Amy_Sample.mp3"              type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Emma`            |<audio controls style="height: 30px"><source src="../assets/Emma_Sample.mp3"             type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Brian`           |<audio controls style="height: 30px"><source src="../assets/Brian_Sample.mp3"            type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Geraint`         |<audio controls style="height: 30px"><source src="../assets/Geraint_Sample.mp3"          type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Google Cloud (AU)|`en-AU-Standard-A`|<audio controls style="height: 30px"><source src="../assets/en-AU-Standard-A_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-AU-Standard-B`|<audio controls style="height: 30px"><source src="../assets/en-AU-Standard-B_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-AU-Standard-C`|<audio controls style="height: 30px"><source src="../assets/en-AU-Standard-C_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-AU-Standard-D`|<audio controls style="height: 30px"><source src="../assets/en-AU-Standard-D_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Amazon Polly (AU)|`Nicole`          |<audio controls style="height: 30px"><source src="../assets/Nicole_Sample.mp3"           type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Russell`         |<audio controls style="height: 30px"><source src="../assets/Russell_Sample.mp3"          type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Google Cloud (IN)|`en-IN-Standard-A`|<audio controls style="height: 30px"><source src="../assets/en-IN-Standard-A_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-IN-Standard-B`|<audio controls style="height: 30px"><source src="../assets/en-IN-Standard-B_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-IN-Standard-C`|<audio controls style="height: 30px"><source src="../assets/en-IN-Standard-C_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`en-IN-Standard-D`|<audio controls style="height: 30px"><source src="../assets/en-IN-Standard-D_Sample.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Amazon Polly (IN)|`Aditi`           |<audio controls style="height: 30px"><source src="../assets/Aditi_Sample.mp3"            type="audio/mp3"> Audio Tag Unsupported. </audio>|
|                 |`Raveena`         |<audio controls style="height: 30px"><source src="../assets/Raveena_Sample.mp3"          type="audio/mp3"> Audio Tag Unsupported. </audio>|

### Supported TTS pitches

Users can set a custom pitch that is used just for their TTS commands with `!set tts pitch <value>`.

* `x-low`
* `low`
* `medium`
* `high`
* `x-high`

### TTS effects

Users can set custom effects and effect chains that are used just for their TTS commands with `!set tts effect <Effects>`.

#### Pitch Shift

A pitch shift can adjust the pitch of a TTS Voice higher or lower. Pitch shifts take the form `PitchShift <shift>`.

| Command | Example |
|---------|---------|
|`PitchShift 0.5`          |<audio controls><source src="../assets/Effects/PitchShift0.5.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`PitchShift 0.75`         |<audio controls><source src="../assets/Effects/PitchShift0.75.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Non-PitchShifted Reference|<audio controls><source src="../assets/Effects/PitchShiftNone.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`PitchShift 1.5`          |<audio controls><source src="../assets/Effects/PitchShift1.5.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`PitchShift 2`            |<audio controls><source src="../assets/Effects/PitchShift2.mp3"    type="audio/mp3"> Audio Tag Unsupported. </audio>|

#### Chorus Effect

A chorus effect can make the TTS voice sound like a chorus of several. A hivemind, of sorts.

| Command | Example |
|---------|---------|
|`Chorus`            |<audio controls><source src="../assets/Effects/ChorusEffect.mp3"     type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Non-Chorus Reference|<audio controls><source src="../assets/Effects/ChorusEffectNone.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|

#### Noise Vocoding

Noise Vocoding can make the TTS voice sound like a creepy serial-killer. Noise vocoding takes the form `Vocode <band>`. The more bands that are used, the more clear the voice will be.

| Command | Example |
|---------|---------|
|`Vocode 5`           |<audio controls><source src="../assets/Effects/Vocoding5Band.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Vocode 10`          |<audio controls><source src="../assets/Effects/Vocoding10Band.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Vocode 20`          |<audio controls><source src="../assets/Effects/Vocoding20Band.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Vocode 30`          |<audio controls><source src="../assets/Effects/Vocoding30Band.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Vocode 40`          |<audio controls><source src="../assets/Effects/Vocoding40Band.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Non-Vocoded Reference|<audio controls><source src="../assets/Effects/VocodingNone.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|

#### Frequency Modulation

Frequency modulation can make the TTS voice sound like its pitch is wavering back and forth.  Frequency modulation takes the form `Modulation <depth> <rate>`, where the depth determines the degree of the modulation, and the rate determines the speed of the modulation.

| Command | Example |
|---------|---------|
|`Modulation 2 10`      |<audio controls><source src="../assets/Effects/Modulation2_10.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 2 50`      |<audio controls><source src="../assets/Effects/Modulation2_50.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 2 200`     |<audio controls><source src="../assets/Effects/Modulation2_200.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 8 10`      |<audio controls><source src="../assets/Effects/Modulation8_10.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 8 50`      |<audio controls><source src="../assets/Effects/Modulation8_50.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 8 200`     |<audio controls><source src="../assets/Effects/Modulation8_200.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 32 10`     |<audio controls><source src="../assets/Effects/Modulation32_10.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 32 50`     |<audio controls><source src="../assets/Effects/Modulation32_50.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Modulation 32 200`    |<audio controls><source src="../assets/Effects/Modulation32_200.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Non-Modulated Reference|<audio controls><source src="../assets/Effects/ModulationNone.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|

#### Reverb Effects

Reverb can make the TTS voice sound like it's emanating from a different environment.  Reverb is somewhat nuanced, so a number of pre-defined options are available. Reverb takes the form `Reverb <effect>`, where effect is one of the options below.

| Command | Example |
|---------|---------|
|`Reverb Mild`         |<audio controls><source src="../assets/Effects/ReverbMildReverb.mp3"    type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb Medium`       |<audio controls><source src="../assets/Effects/ReverbMediumReverb.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb Strong`       |<audio controls><source src="../assets/Effects/ReverbStrongReverb.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb Echo`         |<audio controls><source src="../assets/Effects/ReverbEcho.mp3"          type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb StrongEcho`   |<audio controls><source src="../assets/Effects/ReverbStrongEcho.mp3"    type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb CrappySpeaker`|<audio controls><source src="../assets/Effects/ReverbCrappySpeaker.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb SmallSpeaker` |<audio controls><source src="../assets/Effects/ReverbSmallSpeaker.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb InsideEar`    |<audio controls><source src="../assets/Effects/ReverbInsideEar.mp3"     type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb InsideBox`    |<audio controls><source src="../assets/Effects/ReverbInsideBox.mp3"     type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`Reverb VeryWarm`     |<audio controls><source src="../assets/Effects/ReverbVeryWarm.mp3"      type="audio/mp3"> Audio Tag Unsupported. </audio>|
|No-Reverb Reference   |<audio controls><source src="../assets/Effects/ReverbNone.mp3"          type="audio/mp3"> Audio Tag Unsupported. </audio>|

#### Frequency Shift

Frequency shift effects apply a linear shift to the frequencies making up the TTS voice, which can create unusual patterns of interference.  Frequency shifts take the form `FrequencyShift <shift>`.

| Command | Example |
|---------|---------|
|`FrequencyShift -200`|<audio controls><source src="../assets/Effects/FreqShiftn200Hz.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift -100`|<audio controls><source src="../assets/Effects/FreqShiftn100Hz.mp3"  type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift -50` |<audio controls><source src="../assets/Effects/FreqShiftn50Hz.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift -20` |<audio controls><source src="../assets/Effects/FreqShiftn20Hz.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift -10` |<audio controls><source src="../assets/Effects/FreqShiftn10Hz.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|Non-Shifted Reference|<audio controls><source src="../assets/Effects/FreqShiftNoShift.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift 10`  |<audio controls><source src="../assets/Effects/FreqShift10Hz.mp3"    type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift 20`  |<audio controls><source src="../assets/Effects/FreqShift20Hz.mp3"    type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift 50`  |<audio controls><source src="../assets/Effects/FreqShift50Hz.mp3"    type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift 100` |<audio controls><source src="../assets/Effects/FreqShift100Hz.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`FrequencyShift 200` |<audio controls><source src="../assets/Effects/FreqShift200Hz.mp3"   type="audio/mp3"> Audio Tag Unsupported. </audio>|

#### Chaining Effects

You can chain together multiple effects by just adding a comma between them.  Effects are execute left to right.

| Command | Example |
|---------|---------|
|`NoiseVocodeEffect 30, Chorus, PitchShift 1.4`|<audio controls><source src="../assets/Effects/DemonBees.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|
|`PitchShift 0.8, Reverb InsideBox`            |<audio controls><source src="../assets/Effects/GeenieBox.mp3" type="audio/mp3"> Audio Tag Unsupported. </audio>|

#### Removing Effects

To remove any effect from your TTS voice, use `!set tts effect Normal`.
