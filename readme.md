# Separate each line in time of your .srt file!
No more overlap between subtitles: each line of subs starts after the previous ends.

# Requirements
Python3.

# Purpose
This script was created to have working .srt subtitles on Chrome extension Substitial.
The extension seems to have troubles processing -srt subtitle that have multiple lines in the same time interval: the subs go out of timing.

This scripts takes an .srt file and creates a copy having totally time-separated subs: where you have two overlapping lines, the previous is cut where the current begins: the result is that some line are cut, but you can still listen  to everything on time.

# Usage
Put the script and the target file in the same folder. 

Input: `file_name.srt`\
Output: `file_name_edited.srt`\
From terminal run: `$ python3 separate_srt.subtitles.py file_name.srt`
