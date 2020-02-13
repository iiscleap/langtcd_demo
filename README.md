# Demo to compute reaction time for TCD
TCD stands for talker change detection. This repository shares a html script to compute and display the experimental setup to study the effects of language familiarity on detecting change in talkers in a speech utterance.

# Test it
1. You can open it straightaway by pasting the below URL in your browser.
Link: ???

2. Or, you can download this repository and open rt_speech.html in your local system's web browser.
 

# About the script
To run open the rt_speech.html file.
It contains some simple HTML javascript-ing.
1. Obtains the list of audio files from - Chinese: ./data/rtSamples_c/file_list.txt - English: ./data/rtSamples_e/file_list.txt
2. Obtain the file name and the ground truth change instant for each file and stores these in file_set_test and files_set_key variables, respectively.
3. On pressing Chinese/English 1 and 2 are carried out.
4. On pressing 1 or 2 the hitpressed() function is called to obtain the reaction time and response.


# To know more on TCD
Great to have you interested in this! You can follow our research here:
https://github.com/neerajww/TCD_human_machine
