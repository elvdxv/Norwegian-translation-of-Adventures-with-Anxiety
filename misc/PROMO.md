# intro

`SceneSetup.intro();`

# intro-play-button

[<div class="mini-icon" pic="play1"></div> PLAY! <div class="mini-icon" pic="play2"></div>](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: derp

`publish("show_options_bottom")`

# intro-start-2

`clearText()`

(...1000)

`publish("intro-to-game-2")`

n2: DETTE ER ET MENNESKE

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

`SceneSetup.act1();`

(...300)

n: OG DETTE ER MENNESKETS ANGST

n: _DU_ ER ANGSTEN

[Du spiser lunsj alene! Igjen!](#act1a_alone)

[Du er ikke produktiv når du spiser!](#act1a_productive)

[Den loffen er dårlig for deg!](#act1a_bread)

# act1a_alone

`bb({mouth:"small", eyes:"narrow"})`

b: Vet du at ensomhet er assosiert med tidlig død like mye som å røyke 15 sigaretter vær dag?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (Holt-Lunstad et al, 2010, PLoS Medicine)

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

h: Uh, takk for å sitere kildene dine men--

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({body:"fear", mouth:"normal", eyes:"fear"})`

b: Som betyr om du ikke henger med noen *akkurat nå* så vil du-

`bb({body:"panic"})`

b: DØØØØØØØØØØØØØØØ

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("20p", "alone");
publish("hp_show");
```

(...2500)
