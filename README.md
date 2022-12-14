# Rochambeau v2.0

From the Tao came One, and from the One came Two. From the Two, there came Three: The Rock, The Paper, and the Scissors, and glorious, fiery combat immediately ensued. This eternal struggle for supremacy has since intensified with the appearance of two new challengers: a lizard, and Spock from Star Trek. 

From whence did these mysterious opponents come? What is Tao?, What kind of lizard is lizard?, How is a piece of paper or a tiny lizard any match for Spock from Star Trek?, Are you sure you're getting enough sleep, Chris? - All of these questions, and many more, will <em>not</em> be answered, in ROCHAMBEAU V2.0.

ROCHAMBEAU V2.0 is an interactive webpage that enables you to play a pulse-pounding game of Rock, Paper, Scissors, Lizard, Spock against an unpredictable computer opponent.

It is intended to be humorously extreme and epic, as well to graphically resemble a wrestling promotion, and to play similarly to a fighting videogame.

<hr>

## Technologies used
<ul>
    <li>Hypertext Markup Language (HTML)</li>
    <li>Cascading Style Sheets (CSS)</li>
    <li>JavaScript</li>
    <li>Markdown</li>
    <li>GitHub</li>
    <li>GitPod</li>
    <li>Git</li>
</ul>
<hr>

## Features

<hr>

### Existing Features

Upon loading the page, the visitor will be presented with a large modal button. This button can be interacted with by clicking it, or by pressing the Enter key. As the text on this button suggests, interacting with it will begin the game:

<img src="assets/images/screenshot-01-modal-begin-game-button-screenshot.jpg" alt="A screenshot of the begin game button.">
<hr>

Once the modal button is clicked, one of the elements that will immediately stand out, despite being small, is the sound button. Right away, the visitor will notice that the page features a lot of audio. This button provides a quick, one-click way for them to mute the page if they want to.

<img src="assets/images/screenshot-02-sound-button-sound-on-screenshot.jpg" alt="A screenshot of the sound button in the on state.">
<img src="assets/images/screenshot-03-sound-button-sound-off-screenshot.jpg" alt="A screenshot of the sound button in the off state.">
<hr>

Also when the button is clicked, an announcer will audibly prompt the player to select a character from the left hand column, which briefly flashes green to draw the player's attention.

Note that on devices with smaller screen dimensions, the page will automatically scroll to the top of the character column to more fully display its contents.

<img src="assets/images/screenshot-04-character-select-glow-screenshot.jpg" alt="A screenshot of the glowing character selection column.">
<hr>

Hovering over your character of choice will trigger a small animation, play audio, and highlight it, and clicking it will cause the highlighting to turn green. At this point, selection of characters is temporarily disabled.

<img src="assets/images/screenshot-05-hover-over-fighter-highlight-screenshot.jpg" alt="A screenshot of a character being hovered over with the mouse cursor.">
<img src="assets/images/screenshot-06-click-fighter-highlight-screenshot.jpg" alt="A screenshot of a character having just been clicked on.">
<hr>

Once the player has selected their character, there is a short delay to create suspense, and then the computer makes its choice. The same animation and sound is triggered for the character it selects. The two selected characters appear in the discs in the centre element, and both discs light up.

When the characters populate the discs, an auto-scroll is triggered on devices with smaller screens.

<img src="assets/images/screenshot-07-cpu-selects-character-both-appear-in-middle-screenshot.jpg" alt="A screenshot of the computer having selected its character, and both characters appearing in the middle element.">
<hr>

The names of the selected characters appear in the plaques below the discs, and after a moment, the light around disc in which the winning character is set turns green to indicate that said character has won.

<img src="assets/images/screenshot-08-names-appear-below-and-winning-character-glows-green-screenshot.jpg" alt="A screenshot showing the character names in the plaques, and one character winning the round.">
<hr>

Next, one of the lights on the scoreboard will light up depending on who won, not unlike a fighting videogame. The lights on the left indicate rounds won by the player, and the lights on the right represent the same for the computer. 

On devices with different screen dimensions, an automatic scroll will also happen at this point to briefly show the change to the scoreboard, before scrolling back up to the characters.

<img src="assets/images/screenshot-09-lights-turn-on-for-each-win-screenshot.jpg" alt="A screenshot of one of the round lights turning on when a round is won.">
<hr>

After a moment, the game screen resets, and the player is asked to select their character again. There can be a maximum of 3 rounds, and a minimum of 2, again, just like in most fighting videogames.

<img src="assets/images/screenshot-10-fighters-reset-after-round-screenshot.jpg" alt="A screenshot of the game screen having been reset after a round.">
<hr>

When the player or the computer is about to win their second round, the character they select will perform its finishing move. The announcer declares this, and the name of the move is briefly displayed in a small blue text box. A unique sound effect plays for each move, and each is accompanied by a screen shake.

<img src="assets/images/screenshot-11-fighter-uses-ultimate-attack-when-about to-win-match-screenshot.jpg" alt="A screenshot of one of the characters using their finishing move when they are about to win the match.">
<hr>

The match-winning character's disc glows gold, while the match-losing character's portrait darkens. Depending on whether the player or the computer wins the match, a different sound effect is played.

<img src="assets/images/screenshot-12-match-winner-glows-gold-and-loser-darkens-screenshot.jpg" alt="A screenshot of the match-winning character glowing gold, and the match-losing character darkening.">
<hr>

Finally, another modal button appears. The text on this button reads "Play Again" rather than "Begin Game".

<img src="assets/images/screenshot-13-play-again-modal-button-appears-after-match-end-screenshot.jpg" alt="A screenshot of the 'play again' modal button that appears after a match.">
<hr>

### Features yet to be implemented

<strong>Character speech bubbles</strong>: I had wanted to make these appear when a character was selected, and to possibly have them contain different text depending on whether the character was selected by the player or the computer. This was a low-priority feature though, as although I had some funny ideas for it, I felt that it might be too much on top of everything else. I felt that there would be too many things competing for the player's attention, not to mention that these speech bubbles probably wouldn't display for long, unless I wanted to interrupt the flow of the game even more. Moreover, the testing process was time-consuming enough without this feature.

<strong>Character health meters</strong>: This was an idea that popped into my head very late on, and which I would like to add someday. I didn't feel like I had the time to implement it well.

<strong>Different finishing moves</strong>: I either wanted to have the computer use different finishing moves to the player, or I wanted to give the player a choice of two finishing moves per character (and have the computer randomly select from the 2 available to each character). I feel this would have added a layer of fun to the game, but as with the speech bubbles, I was concerned that it would make testing an even lengthier process.

<strong>Secret character(s)</strong>: I considered adding a secret character that wins against all 5 of the other characters, but I never really gave any serious thought to how I would implement it in the game. I initially had a vague idea about having the character click a specific, hidden point on the body element to select the character, but I wasn't too enthusiastic about it. I didn't give this feature all that much thought, and so no interesting ideas for how to implement it ever popped into my head.

<strong>Network play</strong>: This feature is almost certainly beyond my ability to implement at this stage in the course, and perhaps will still be if and when I complete it, but I would like to add a multiplayer mode to the game someday. It would of course only work if the two players couldn't see and hear one another's computers / laptops / phones, and if one player made their choice before the other one, it would have to be invisible to their opponent until they had made their choice too. 

<hr>

## Testing

<em>Please refer to TEST.md.</em>
<hr>

## Deployment

The process followed in order to deploy this project to GitHub Pages was as follows:
<ol>
    <li>I navigated to GitHub.com and logged in to my account.</li>
    <li>Once I was logged in, I navigated to the repository for this project.</li>
    <li>At the page for the project repository, I entered the Settings menu.</li>
    <li>In the Settings menu, I clicked on the Pages section in the left-hand pane.</li>
    <li>In the Pages section, I left the Source drop-down menu set to "Deploy from a branch".</li>
    <li>For Branch, I selected "main".</li>
    <li>Finally, I clicked Save. After a few moments, the URL for my project went live. Please find it below.</li>
</ol>

Live link to this project: 
<hr>

## Credits

### Code

The keyframes code for causing the page to shake was taken from this article: https://www.w3schools.com/howto/howto_css_shake_image.asp

### Content
The fonts used across the website were taken from Google Fonts.
- [Rubik Burned](https://fonts.google.com/specimen/Rubik+Burned?query=rubik+bu)
- [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue?query=bebas)

Using https://gauger.io/fonticon/, I converted a FontAwesome icon into a favicon for the website. The icon I used is here: https://fontawesome.com/v5/icons/hamsa?s=solid&f=classic.

### Media

#### Images

- [fire.jpg](https://wallpaperaccess.com/flame)
- [metal-fighters.jpg](https://wallpaperaccess.com/rustic-metal-iphone) (scroll down)
- [metal.jpg](https://wallpaperaccess.com/metal) (scroll down)
- [bout-plate.jpg](https://depositphotos.com/13861129/stock-photo-metal-plate.html) (found through Google Images)
- [metal-plate.jpg](https://www.istockphoto.com/photo/steel-background-gm624894566-109933631?phrase=metal%20plate) (small version without watermark taken from Google Images link to same page)
- [contender-disc.jpg](https://wellinguk.com/products/sliding-doors/sliding-door-kits/locks-handles-accessories/circular-flush-finger-pull-concealed-satin-stainless-steel/) (found through Google Images)
- [small-plate.jpg](https://www.dreamstime.com/narrow-metal-plaque-plate-clipping-path-included-d-illustration-simple-narrow-metal-plaque-plate-white-image170049242) (see comment after scoreboard background)
- [round-light.jpg](https://www.luminaire.ie/products/vintage-industrial-heavy-round-bulkhead-retro-wall-light-flush-mount) (found through Google Images)
- [rock.jpg](https://modestomilling.com/product/redmond-rock/) (found through Google Images)
- [paper.jpg](https://www.istockphoto.com/photo/white-vertical-paper-sheet-mockup-gm1037276106-277670620?phrase=blank%20sheet%20of%20paper) (see comments after scoreboard background and nameplate) (found through Google Images)
- [scissors.jpg](https://www.nytimes.com/wirecutter/reviews/best-scissors-kitchen-shears/) (found through Google Images)
- [lizard.jpg](https://theconversation.com/lizards-cockroaches-and-batfish-oh-my-see-the-top-ten-new-species-here-1453) (found through Google Images)
- [spock.jpg](https://www.bbc.com/news/entertainment-arts-31662024) (found through Google Images)

#### Audio

All voice audio was generated by the text-to-speech engine at https://www.acapela-group.com/. The voice I used was <em>WillBadGuy (premium voice)</em>, with the language/accent set to <em>English (United States)</em>. I also added reverb to these clips (and all the clips below) using [Audacity](https://www.audacityteam.org/). Note that these voice clips are watermarked, hence the strange bell/chime sound that can sometimes be heard.

The following audio was taken from the website Pixabay:
- [sound-button.mp3](https://pixabay.com/sound-effects/switch-click-and-beep-001a-11602/)
- [mouseover-swish.mp3](https://pixabay.com/sound-effects/swing-6045/)
- [mouseout-swish.mp3](https://pixabay.com/sound-effects/055933-swish-noise-blast-84760/)
- [light-on.mp3](https://pixabay.com/sound-effects/fluorescent-light-switch-fuse-37764/)
- [sisyphean-despair.mp3](https://pixabay.com/sound-effects/rock-destroy-6409/)
- [victory-sting.mp3](https://pixabay.com/sound-effects/hifreq-light-woosh-6828/)
- [defeat-sting.mp3](https://pixabay.com/sound-effects/creepy-hifreq-woosh-6873/)
- [light-off.mp3](https://pixabay.com/sound-effects/085019-desk-lamp-38375/)
- [reset-swish.mp3](https://pixabay.com/sound-effects/double-swish-80143/)

The following audio was taken from the website Pond5, and is watermarked (hence the strange whispers you will hear):
- [start-game.mp3](https://www.pond5.com/sound-effects/item/86122243-trailer-dark-deep-drum-hit-3)
- [drum.mp3](https://www.pond5.com/sound-effects/item/89148813-war-ui-drum-movement-taiko-hits-3)
- [electric-shock.mp3](https://www.pond5.com/sound-effects/item/86515696-electric-shock-sound-effect)
- [electric-shock-short.mp3](https://www.pond5.com/sound-effects/item/8744198-electricityzap)
- [tabula-rasa.mp3](https://www.pond5.com/sound-effects/item/152640528-page-turn-3)
- [abhorrent-shears.mp3](https://www.pond5.com/sound-effects/item/205583074-sword-whoosh-01-blade-dagger-knife-saber-sword)
- [herald-of-ragnarok.mp3](https://www.pond5.com/sound-effects/item/88512812-fantasy-lizard-monster-voice-yes)

The audio clip of Spock was taken from this page: https://movie-sounds.org/spock

