# How to add a dictionary for spell check

In Android Studio (1.2.1.1 - 2.3.3) you can find this here:

File -> Settings -> Editor -> Spelling -> Dictionaries, and click "+" sign next to "Custom Dictionaries Folders" grid.

Important Note: You need to use UTF-8 character coding in your "language.dic" file if you would like to use an exotic language like Hungarian, Spanish, Portuguese, etc.

Download from http://www.winedt.org/dict.html the UNICODE language file.
Unzip and open it with Windows Notepad.
Use "Save as" and choose UTF-8 coding.
Open this file with Android Studio: File -> Settings -> Editor -> Spelling -> Dictionaries, and click "+" sign next to "Custom Dictionaries Folders" grid.
Restart Android Studio. Smile! You have not problems with nasty letters like "éÉíÍóÓöÖőŐúÚüÜűŰ".

- Référence 
  - https://stackoverflow.com/questions/16709263/how-to-add-a-dictionary-for-spell-check-in-android-studio-intellij-idea#answer-30445503
