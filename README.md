# Asta's sketchybar
My current sketchybar dotfiles, designed to immitate the look of the current macOS dock in dark mode.
![Screenshot 3](https://github.com/user-attachments/assets/1ce7ccf6-5cbe-49e3-9aae-859891a87159)

## Prerequisites 
This config requires the fonts SF Compact and SF Mono. Both can be installed via [Apple's developer fonts website](https://developer.apple.com/fonts/) or via Homebrew:
```
brew install --cask font-sf-compact
brew install --cask font-sf-mono
```
## Configuration and Troubleshooting
The config specifically is made to synergise with my Yabai install, which is why it is set to have a 4px y offset and margin. This is the same offset that the vanilla dock has.
![Screenshot 4](https://github.com/user-attachments/assets/6205d8aa-0fdf-49ed-b288-3ab823328128)

The shadow can sometimes look a bit weird to me, but the vanilla dock also has a shadow, so I left it turned on for consistency. 

If the symbols don't work, try the [SF Symbols](https://developer.apple.com/sf-symbols/) app and copying the relevant symbols over to the configuration file(s).
