# isabelle_dark_theme
EditorSchemes and preferences for dark themes in Isabelle/jEdit.

## Requirements
You need to have the `EditorScheme`, `LookAndFeel` and `FlatLaf` plugin installed. To do this, just go to `Plugins > Plugin Manager > Install`.

## Step 1: Set dark look and feel
Go to `Plugins > Plugin Options > Look And Feel`. Then, set the "Look And Feel" entry to `FlatLaf Dark`.

Afterwards, close your Isabelle IDE.

## Step 2: Import color schemes
1. Append the content of the `preferences` file to `~/.isabelle/Isabelle20__/etc/preferences`.

1. Move the `MyDarkMode.jedit-scheme` file into `~/.isabelle/Isabelle20__/jedit/schemes/`. Create the folder if it is missing. After reopening Isabelle, select the scheme in `Plugins > Editor Scheme > Scheme Selector`.

## Step 3: Finetuning
Some settings may still need to be adjusted. This can be done in `Plugins > Plugin Options > Isabelle > Rendering`.

# Contact
If some color makes code unreadable or you have some suggestions or other proposals for color themes, feel free to send a mail to [bruderjakob17@gmail.com](mailto:bruderjakob17@gmail.com).