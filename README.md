# isabelle_dark_theme
Style sheets and EditorSchemes for dark themes in Isabelle/jEdit.

## Requirements
You need to have the `EditorScheme` and `LookAndFeel` plugin installed. To do this, just go to `Plugins > Plugin Manager > Install`.

## Step 1: Set dark look and feel
Go to `Plugins > Plugin Options > Look And Feel`. Then, set the "Look And Feel" entry to `FlatLaf Dark`.

Afterwards, restart your Isabelle IDE.

## Step 2: Import color schemes
1. Move the `isabelle.css` file into the `etc` folder of your Isabelle installation, e.g. `/opt/Isabelle2021/etc/isabelle.css`.

1. Move the `MyDarkMode.jedit-scheme` file into `~/.isabelle/Isabelle20__/jedit/schemes/`.

## Step 3: Finetuning
I just edited the default `isabelle.css` file, where I did not find all settings. Some settings still need to be adjusted in `Plugins > Plugin Options > Isabelle > Rendering`:
* Active Color: `#333333`
* Active Hover Color: `#336600`

# Contact
If some color makes code unreadable or you have some suggestions or other proposals for color themes, feel free to send a mail to [bruderjakob17@gmail.com](mailto:bruderjakob17@gmail.com).