# jspsych-vislexdec
Visual [Lexical Decision](https://en.wikipedia.org/wiki/Lexical_decision_task) Experiment (template)

# Connected templates

### Visual Templates
1. [vislexdec](https://github.com/UiL-OTS-labs/jspsych-vislexdec)
2. [vislexdec-vp](https://github.com/UiL-OTS-labs/jspsych-vislexdec-vp)
3. [vislexdec-vp-mp](https://github.com/UiL-OTS-labs/jspsych-vislexdec-vp-vm)

### Audio and/or visual Templates
4. [audlexdec](https://github.com/UiL-OTS-labs/jspsych-audlexdec-vp)
5. [audlexdec-vp](https://github.com/UiL-OTS-labs/jspsych-audlexdec-vp)
6. [audlexdec-vp-mp](https://github.com/UiL-OTS-labs/jspsych-audlexdec-vp-mp)

# Task Description

## Short description
The participant first sees a fixation cross, then a word or a non word is presented. Participants are instructed to respond as quickly as possible to make the decision wether the string is a word or not, using the keyboard.

- The _'test stimulus'_ (called 'word') is a string of letters and can be a real word or a nonword.

The reaction time, response and correctness of the response are usually the important variables for analysis. By default, the data of all sub trial phases are logged in the data, but the output data can quite easily be filtered after data collection.

# Getting started (the easy way, working internet connection required)
For now, the easiest way to test these templates, is:

1. Download this repository by clicking the green code button above and Download zip.
2. Unzip the jspsych-vislexdec-main.zip at a location of your choosing.
3. Inside the folder is a file called index.html, double click it in order to open it
   in a browser.

# Getting started (the harder way, local and/or custom setup)

You need this github repository and to download the jsPsych library version 6.1
complete the following steps. When downloading and extracting folders please
keep in mind that once working on the server, filenames are case sensitive and
"jsPsych.js" and "jspsych.js" are two distinct filenames. It might work on your
machine, but it might not work on the server hosting your experiment.

You will need to adapt your own directory structure/naming convention in the 
top ```<script>``` tags as defined in index.html, if you want your own local jsPsych setup.

1. Download this repository by clicking the green code button above and Download zip.
2. Unzip the jspsych-vislexdec-main.zip at a location of your choosing.
3. Download jsPsych-6.1.0 (-6.1.0 is the version) from the jsPsych releases website
   https://github.com/jspsych/jsPsych/releases. You might need to scroll down a little.
4. Extract the jsPsych folder into the jspsych-vislexdec folder you extracted earlier.
5. Inside the folder is a file called index.html, double click it in order to open it
   in a browser.
