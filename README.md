# Speaking Swahili Clock⏰🦁
A program with interactive interface that lets you choose a time zone, shows you the current time in the chosen time zone in Swahili and reads it out for you!

The repository contains folder "audios" that includes the .wav files the programme uses. They were scraped from https://www.spokenswahili.com/blog/telling-the-time-in-swahili/.

The .png files in the repository are used as background for the clock window.

Within the terminal, move to the root directory, where the requirements file is located. With the command ``pip install -r requirements.txt`` you can install all necessary packages to run the code. In case you get a tkinter ImportError, please refer to: https://tkdocs.com/tutorial/install.html. Next, run the file code.py from the root directory with the command ``python code.py``.

Two windows open when the command is executed. The main window contains the welcome text and the control buttons. The other window is where you can have a clock showing the current time in your timezone. 

To start, choose a timezone from the scrollable listbox and confirm it with button "Show time in zone". The current time in the timezone will be displayed. To see translation to Swahili, press "Translate to Swahili". Please make sure to press the buttons in this order! To draw the clock - press "Draw clock". Its background will depend on whether it is daytime or nightime. Once closed this window does not open again, unless you execute the code again. Finally, to have the program pronounce the time, press "Tell me the time"!

To start again with a new timezone, just choose a new timezone and press "Show time in zone" and any other feature buttons again!

The time is Swahili is told different then how it is told in Europe. Swahilian time begins when the sun rises. The days are divided in two cycles of 12 hours, one during the day and one during the night. This means that when the clock hits 7, it is 1 in the morning in Swahili, saa moja (hour one). At 7 o’clock in the evening the sun will be down, signifying that it is 1 in the night in Swahilitime. In the first 30 minutes of an hour, you combine the current hour and minutes. So 8.26 in the morning would become “saa mbili na dakika ishirini na sita (hour two and minute twenty and six). If it has been 15 minutes since the hour has started, they will say “saa tatu na robo” (hour three and a quarter). When the hour is halfway to the next hour, for example 11.30, the time is "saa tano na nusu" (hour 5 and half). If it has been over 30 minutes in the hour, the time will be read as a statement of subtraction from the coming hour. 7.40 will be “saa mbili kasoro dakika ishirini” (hour two without minute twenty). The same goes if there are 15 minutes to an hour, 9.45 will be “saa nne kasoro robo” (hour four without a quarter). To indicate if the time said is during the day or during the night the sentence will end in this specification, “asubuhi” for morning and “usiku” for evening. Together it will look as “saa nne na dakika ishirini na saba asubuhi” (hour 4 and minute twenty and seven morning) for 10.27am.
