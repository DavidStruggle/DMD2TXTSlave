# DMD2TXTSlave

A very basic Timeshock! Ultra Edition slave that allows you to capture the DMD data, that would have been sent to a PINDMD2 slave.


## What is does 
The tool just logs the DMD data that would have been sent to a PINDMD2 slave and stores it in a .txt file.
The .txt file is formatted to be used with PIN2DMD Editor.

## But why?
For a project of mine, I needed the DMD animations of the game. Rather than trying to figure out how the animation data is stored in the game files, I decided to log the DMD data since the new release of Timeshock already has such an interface.

## Limitations
- It capures the raw DMD output. That means, that text and scores are also present on the animations. By changing the content of the fonts in the games directory with an hex editor, you can easily make them invisible. 
- It takes quite an effort to get all dmd animations. But it is definitly doable. Glass-off mode is key.

## Dependencies
- boost (1.60.0)

## Usage
- Copy the DMD2TXTSlave.exe in your game directory
- Start the game with "m3 dDMD2TXTSlave"
- Play
- The logged data is stored in DMD-Dump.txt in your games directory
