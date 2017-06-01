## IBM Verse Tone Analyzer Sample

This sample demonstrations how to integrate the [Watson Tone Analyzer](https://www.ibm.com/watson/developercloud/tone-analyzer.html) with IBM Verse.

1. Set up the Tone Analyzer Node.js starter application
    1. Follow instructions posted [here](https://github.com/watson-developer-cloud/tone-analyzer-nodejs)
1. Extend the starter application to perform tone analysis for mails being read in Verse
    1. Clone or copy this project
    1. Copy the section commented 'Handle request to analyze tone for Verse' into apps.js in the tone-analyzer-nodejs project
    1. Add the file `verse-tone.ejs` into the views folder in the tone-analyzer-nodejs project
    1. Restart the starter application
1. Use Verse Developer Chrome extension to register the sample
    1. Set up the Verse Developer Chrome extension using these [instructions](https://ibmcnxdev.github.io/verse-developer-chrome-ext/tutorials/tutorial_verse_developer.html)
    1. Replace the `applications.json` with the one from this project
    1. Reload the extension and reload Verse
1. Run the sample
    1. Select a mail and read it in Verse
    1. Open he overflow menu (select '...') and select the 'Analyze Tone' action
    1. A window will open and the tone analysis will be displayed

