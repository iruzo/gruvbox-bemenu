| Dark | Light |
|-|-|
|![Dark](https://camo.githubusercontent.com/410b3ab80570bcd5b470a08d84f93caa5b4962ccd994ebceeb3d1f78364c2120/687474703a2f2f692e696d6775722e636f6d2f776136363678672e706e67)|![Light](https://camo.githubusercontent.com/d080d9c204408ef06b862b76bc795f930b3a9b1be4c5d2de149f1d8eb765b660/687474703a2f2f692e696d6775722e636f6d2f3439714b7959572e706e67)|

<p align="center">
	<img src="https://raw.githubusercontent.com/iruzo/gruvbox-bemenu/main/assets/preview.webp"/>
</p>

## Previews

<details>
  <summary>:black_circle: Dark</summary>
  <img src="https://raw.githubusercontent.com/iruzo/gruvbox-bemenu/main/assets/bemenu-dark.png"/>
</details>
<details>
  <summary>:white_circle: Light</summary>
  <img src="https://raw.githubusercontent.com/iruzo/gruvbox-bemenu/main/assets/bemenu-light.png"/>
</details>

## Usage

- Launch from your wm, script or command bemenu adding the desired theme as params:
```
# dark
bemenu-run -i -l 20 --fb "#282828" --ff "#ebdbb2" --nb "#282828" --nf "#ebdbb2" --tb "#282828" --hb "#282828" --tf "#fb4934" --hf "#fabd2f" --nf "#ebdbb2" --af "#ebdbb2" --ab "#282828"
# light
bemenu-run -i -l 20 --fb "#fbf1c7" --ff "#3c3836" --nb "#fbf1c7" --nf "#3c3836" --tb "#fbf1c7" --hb "#fbf1c7" --tf "#9d0006" --hf "#b57814" --nf "#3c3836" --af "#3c3836" --ab "#fbf1c7"
```

- Example for i3/sway config:
```
# mocha
set $menu bemenu-run -i -l 20 --fb "#282828" --ff "#ebdbb2" --nb "#282828" --nf "#ebdbb2" --tb "#282828" --hb "#282828" --tf "#fb4934" --hf "#fabd2f" --nf "#ebdbb2" --af "#ebdbb2" --ab "#282828"
bindsym $mod+d exec $menu
```

- You can also use an environment variale to set the theme.
```
export BEMENU_OPTS='-i -l 20 --fb "#282828" --ff "#ebdbb2" --nb "#282828" --nf "#ebdbb2" --tb "#282828" --hb "#282828" --tf "#fb4934" --hf "#fabd2f" --nf "#ebdbb2" --af "#ebdbb2" --ab "#282828"'
```

