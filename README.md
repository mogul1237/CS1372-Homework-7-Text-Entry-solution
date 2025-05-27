# CS1372-Homework-7-Text-Entry-solution

Download Here: [CS1372 Homework 7: Text Entry solution](https://jarviscodinghub.com/assignment/cs1372-homework-7-text-entry-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

This assignment is to make sure you have are able to integrate multuple systems together. In this case,
you will integrate tiles, sprites, and sound on the GBA. Leahy wanted me to add this stuff in, so blame him
if you want to whine about this.
Instructions
Your assignment is to create a text entry system for the GBA. Your system should be entirely implemented
in an independent library that a programmer could use when he desires text input on the GBA. The primary
function for this library should be void getText(char* buffer). The variable buffer is a pointer to where
the text is to be stored. As the prototype suggests, it is supplied by the user. This assignment is fairly
open-ended, but has several requirements:
1. Tiles must be used for all letters.
2. At least one sprite must be used. I suggest that you use the sprite as a cursor to select the letters to
enter.
3. The string should appear on the screen as the user is entering it.
4. There should be some background music or sounds continuously looping during the getText function
to alert the user that the GBA is waiting for input. In addition to this, a beep or typewriter click
should be produced each time a letter is chosen.
5. The user should either have to press a button or select a button on screen (i.e. an “End” or “Enter”
button) to finalize the input.
6. The function should place the entered, null-terminated string in buffer.
You may format the screen in any way you wish so long as it displays all the letters and uses some form of
a cursor to select them. Do not worry about incorporating all symbols. At a minimum, you must have all
26 capital letters. In addition, you may find the following sites useful:
• Reaper.fm: REAPER is a shareware sequencer/multitrack audio editor. It is a very powerful program
and does everything you need by way of mixing, transcoding, etc.
• Freesound.org: this site contains just about any random sound samples you could want under a creative
commons license. I have even found drum samples on this site worthy of being used to replace poor
sounding drums in recordings.
Submit all C files, header files, and your makefile on T-Square. In addition, be sure that all code files are .c
files and not .cpp files. If you use .cpp, the compiler does not enforce proper C syntax.
As before, include the following in the top of your main file:
///////////////////////////////////////////////////////////////////////
// Name: //
// Prism Account: //
// Collaboration: //
// “I worked on the homework assignment alone, using only //
// course materials.” //
// or //
// “I received outside aid on this assigned from the following //
// person(s): //
///////////////////////////////////////////////////////////////////////
