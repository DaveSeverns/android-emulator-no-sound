# android-emulator-no-sound

To run the AVD emulator with no sound...
Locate the emulator file: `$ find ~ d -name emulator 2> /dev/null` you will be looking for the 
path which contains `../../Android/sdk/emulator/emulator`

Go there `$ cd <your-path>/Android/sdk/emulator` and find the file named `emulator` and rename it
`$ mv ./emulator ./emulator_original`
