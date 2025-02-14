# Running my website!

## Step One

Before running, clone this repository and run the following commands:

```bash
npm install
```
## Step Two

You can run the website through Live Preview VSCode extension which will start the local server for the webpage, run it with the following keystroke: 

    Ctrl+Shift+P
    Live Preview: Start Sever

From here you should be able to use the website and be able to view the letter.
You can also use the same URL from the live preview and use it in an actual browser page and be able to see the same result. 

You can also run the website within VSCode through the built in Run and Debug tool, with these key strokes:

    Ctrl+Shift+D

## Accessibility Lab Answers

I ran lightroom dev test and it stated that the colors between the background and the text had a very low contrast and needed to be adjusted. So I went ahead and adjusted the contrast of everything to fix it and make it more readable.

The content is still not very accessible — report on what happens when you try to navigate it using a keyboard.

    The tabbing is not reaching all of the options on the screen meaning not all of the buttons are accessible.

Can you update the article text to make it easier for screen reader users to navigate?

    Yes, you can update the size of the font and the so that it makes it easier for users to read and follow along with. Currently it's very small and hard to see even with the contrast corrected. So I have updated the CSS styling to make it easier for users to see. 
    
The navigation menu part of the site. Could be made more accessible by putting it in a proper HTML semantic element. Which one should it be updated to? Make the update.

    I have just updated to be wrapped in a nav label instead which makes it easier to understand that this is the navigation system, and nav is best practice for html for a navigation bar.

The images are currently inaccessible to screen reader users. Can you fix this?

    Yes, you can add alternative text tag for the screen read version to get a brief description of the image.

The audio player isn't accessible to hearing impaired (deaf) people — can you add some kind of accessible alternative for these users?

    I decided to add the transcription onto the screen, you could also make a hover label if you wanted but because the transcription so short I elected to just transcribe it onto the website for people who are hearing impaired and for those who cannot.

The audio player isn't accessible to those using older browsers that don't support HTML audio. How can you allow them to still access the audio?

    I think the same thing I have done still applies, just transcribing the script onto the page will still still make it accessible for those who don't have html.

The input element in the search form at the top could do with a label, but we don't want to add a visible text label that would potentially spoil the design and isn't really needed by sighted users. How can you add a label that is only accessible to screen readers?

    You can make it label box for it and in the css styling make the visibility hidden but it will still be detected by screen readers.

The two input elements in the comment form have visible text labels, but they are not unambiguously associated with their labels — how do you achieve this? Note that you'll need to update some of the CSS rule as well.

    You will make a separate label from their original names so that they are still invisible labels but their are still also visual representations for screen readers. Similar to the invisible label for search.

The show/hide comment control button is not currently keyboard-accessible. Can you make it keyboard-accessible, both in terms of focusing it using the tab key and activating it using the return key?

    Yes you have to make the show/hide comment an actual button in HTML and then you can make it accessible through tabbing when you update the functionality in the main java. 

The data table is not currently very accessible — it is hard for screen reader users to associate data rows and columns together, and the table also has no kind of summary to make it clear what it shows. Can you add some features to your HTML to fix this problem?

    



### Outside Sources 
