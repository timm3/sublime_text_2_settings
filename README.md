# sublime_text_2_settings
Theme Files and Editor(User level) Preferences
----------
----------

Theme files, *.tmtheme, are place in 

\Users\_user_name_\AppData\Roaming\Sublime Text 2\Packages\_theme_folder_

The default theme folder is "Color Scheme - Default", but I personally recommend you make a different one for custom builds.

Themes are chosen in Sublime Text 2 through Preferences > Color Scheme > folder > theme

----------

Theme files, *.sublime-theme, are placed in 

\Users\_user_name_\AppData\Roaming\Sublime Text 2\Packages\Theme - Default

I believe these can ultimately take the place of .tmTheme files, but DarkPop is not not configured that way, so you need to use both.

Anywho, replace the appropriate sections with the code found in DarkPop.sublime-theme

It is responsible for the coloring of the sidebar

NOTE FOR SUBLIME TEXT 3 USERS:

For the ST3 users who don't have the Default.sublime-theme file (which is actually the default configuration), the simplest procedure is:

Navigate to Sublime Text -> Preferences -> Browse Packages
Open the User directory
Create a file named Default.sublime-theme (if you're using the default theme, otherwise use the theme name, e.g. Material-Theme-Darker.sublime-theme) with the following content (modify font.size as required):

I've not tested this, but found it as part of an answer here:
http://stackoverflow.com/questions/18288870/sublime-text-3-how-to-change-the-font-size-of-the-file-sidebar

And this is supposed to be a copy of Default.sublime-theme, but cannot promise that it is or be held accountable:
https://gist.github.com/anonymous/89867e9cb63f7e811a39


----------

Editor (User level) Preferences (settings) files, *.sublime-settings, are placed in

\Users\_user_name_\AppData\Roaming\Sublime Text 2\Packages\User

They are used to change how the editor behaves or look-and feel, such as indentation spaces vs tabs or line highlighting.

They are not necessary for the color themes.

----------

