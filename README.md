# android-emulator-no-sound

To run the AVD emulator with no sound...

1. Locate the emulator file: `$ find ~ d -name emulator 2> /dev/null` you will be looking for the 
path which contains `../../Android/sdk/emulator/emulator`

2. Go to that location `$ cd <your-path>/Android/sdk/emulator` and find the file named `emulator` and rename it
`$ mv ./emulator ./emulator_original`

3. You can edit your `.zshrc` or `.bashrc` file to add an environment variable `export EMULATOR=<path-to-your-emulator>`
      see <img width="413" alt="image" src="https://user-images.githubusercontent.com/15655675/181522915-5470ce6e-afeb-4bf6-8697-976eb9af5338.png">
      run `$ source .zshrc` (or applicable).
      and then clone this repo and move the `emulator` "script" to the /emulator director and you are good to go. You may need to restart Android Studio
      for the updated script to work.
     
### Note: may be anecdotal but with updates via JetBrains toolbox it seems to overwrite this so you may need to repeat step 2 and parts of step 3 after updating.
