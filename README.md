# vscode-high-feedback-custom-css
***(UNDER CONSTRUCTION)***

This repo contains my custom vscode setup. It tries to enhance your vscode experience by: 
 - Providing more UI feedback (like hover) when there lacks one, or make UI feedback more pronounced when it is not enough, thus reducing your time required to confirm your cursor position, sometimes even enabling operating some UI elements with peripheral vision only, with your eye still focused on the code.
 - More visible seperation so as to minimize the time needed to reparse the user interfaces when glancing at them.
 - Even less animation than the "reduce motion" setting in places where they don't really have any functional value and slows user down when the code is too complex.

... but also at the same time blends naturally into the existing theme(Default Dark+).

It currently contains two files:

 - A custom css file to be appended into `/Applications/Visual Studio Code.app/Contents/Resources/app/out/vs/workbench/workbench.desktop.main.css` if you are using MacOS, and the corresponding folder if you use Windows. It will be properly commented and grouped so you can pick, edit and integrate them to your vscode setup without friction.
 - A json file containing my `workbench.colorCustomizations` in the `settings.json`, designed to enhance some readability(contrast) and designed to work nicely with the custom css. Also designed to work with the color theme "Default Dark+".

## Why I made this
It is not difficult to write css to customize vscode, just open devtools and use the little arrow. However there surely exists many people like me, with similar preferences in terms of UI. This repo may offer a headstart for them, saving them valuable time spent doing repetitive labor.
