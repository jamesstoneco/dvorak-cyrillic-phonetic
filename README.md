# dvorak-cyrillic-phonetic

A Cyrillic Phonetic Keyboard Layout for Dvorak Typists

## Why would you want this?

**Dvorak** is an alternative typing layout for English based languages.  It is one of the most popular alternative layouts and if you have invested into Dvorak and haven't maintained your Qwerty touchtyping it can be quite awkward to go back.  

**Cyrillic Phonetic** is a keyboard layout that is designed to make typing Cyrillic for native english speakers easier, by transliterating (finding similar sounds and letters across both languages) the keys.  This often makes learning to type Cyrillic easier for English speakers because it doesn't require memorizing a completly new layout that is the typical Cyrillic layout.  

I couldn't find a Dvorak based one for macOS so created one using [ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele).  Also instrumental was [on how to create a keyboard layout for macosx on Super User](http://superuser.com/questions/665494/how-to-make-a-custom-keyboard-layout-in-macos) explaining the process step-by-step.  

**NOTE: Requires use of the command line for installation.**

## Installation

1. Copy the file to `/Library/Keyboard Layouts`.

Example:

```
sudo cp -R \
 ~/Downloads/dvorak-cyrillic-phonetic-master/Cyrillic\ Phonetic\ (Dvorak).bundle \
 /Library/Keyboard\ Layouts/
```

2. Touch the directory

```
touch /Library/Keyboard\ Layouts/
```

3. Restart your mac -- A full restart is required
4. Open System Preferences -> Keyboard
5. Under the Input Sources Tab Click the + Button
6. Under Ukrainian choose Cyrillic - Phonetic (Dvorak)

## Learning the Layout

You might find it useful to turn out the keyboard viewer when learning this layout.

1. Go to System Preferences -> Keyboard
2. Click on the Input Sources Tab
3. Check the Show Input menu in menu bar
4. Click the Keyboard Tab
5. Check the Show Keyboard & Character Viewersin the menu bar
6. Under the Keyboard Menu -> Show Keyboard Viewer  (This menu will look like DV if you are set to Dvorak, a US Flag if Qwerty or a DV with a Blue dot if set to Cyrillic Phonetic (Dvorak)

## Release Notes

Jun-26-2017: Renamed to Cyrillic Phonetic (Dvorak).  Arrange layers with option and shift plus option modifiers.  Make it more Ukrainian-friendly.  Fix command and control layers according to Dvorak.  Update Readme.  
Jan-08-2016: All top level keys are remapped.  The ` is missing. With the option modifier, only yo ê is mapped to option-e.  The rest of the option and other characters remain the same as the standard Russian - Phonetic Qwerty Keymap.  

