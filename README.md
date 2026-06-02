# omp-zen-p10k
Oh-My-Posh implementation of Powerlevel10K command prompt based on Zen.

![Screenshot](https://raw.githubusercontent.com/rheijden/omp-zen-p10k/refs/heads/main/zen-p10k-omp.png)

## Why
I like minimalistic and wanted to use Powerlevel10K for my terminal prompt. But as it's unmaintained at the moment, this was a good moment to think about alternatives.

After watching [We may have killed p10k, so I found the perfect replacement.](https://www.youtube.com/watch?v=9U8LCjuQzdc) by Dreams of Autonomy on YT I decided to rebuild his exact set up in YAML (my preferred config format).

## How
Just copy the yml into your config directory of choice, eg. `~/.config/oh-my-posh`

and supply the config argument to point to this location from your shell rc file:

`eval "$(oh-my-posh init zsh --config ~/.config/oh-my-posh/zen.yml)"`

or use it from this repo directly:

`eval "$(oh-my-posh init zsh --config https://raw.githubusercontent.com/rheijden/omp-zen-p10k/refs/heads/main/zen.yml)"`
