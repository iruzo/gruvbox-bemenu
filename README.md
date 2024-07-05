<h3 align="center">
    Gruvbox theme for <a href="https://github.com/Cloudef/bemenu">bemenu</a>
</h3>

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
```sh
# dark
bemenu-run -i -l 20 --fb "#282828" --ff "#ebdbb2" --nb "#282828" --nf "#ebdbb2" --tb "#282828" --hb "#282828" --tf "#fb4934" --hf "#fabd2f" --nf "#ebdbb2" --af "#ebdbb2" --ab "#282828"
# light
bemenu-run -i -l 20 --fb "#fbf1c7" --ff "#3c3836" --nb "#fbf1c7" --nf "#3c3836" --tb "#fbf1c7" --hb "#fbf1c7" --tf "#9d0006" --hf "#b57814" --nf "#3c3836" --af "#3c3836" --ab "#fbf1c7"
```

- Example for i3/sway config:
```sh
set $menu bemenu-run -i -l 20 --fb "#282828" --ff "#ebdbb2" --nb "#282828" --nf "#ebdbb2" --tb "#282828" --hb "#282828" --tf "#fb4934" --hf "#fabd2f" --nf "#ebdbb2" --af "#ebdbb2" --ab "#282828"
bindsym $mod+d exec $menu
```

- You can also use an environment variale to set the theme.
```sh
export BEMENU_OPTS='-i -l 20 --fb "#282828" --ff "#ebdbb2" --nb "#282828" --nf "#ebdbb2" --tb "#282828" --hb "#282828" --tf "#fb4934" --hf "#fabd2f" --nf "#ebdbb2" --af "#ebdbb2" --ab "#282828"'
```

