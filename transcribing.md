# Introduction to Transcribing Documents

Why do we transcribe documents? On one level, transcribing something allows you to become intimately familiar with the contents of a document. By the end of this semester, you may be invested in a family that isn't your own! <!-- Link to article in History Newsletter--> 

Furthermore, transcribing makes physical documents, especially handwritten documents, **machine readable**. In other words, it allows computers to recognize text. Think about it -- scanned letters are pictures of text, which is something a machine cannot translate. Even though there are programs that can attempt to read handwriting (like Transkribus) and even typed text<!--link to Explain that stuff "What is OCR-->, computers aren't smart enough to read things humans are! 

**Transcribing something bridges the gap between reading a document, and storing a picture of one.**

<hr>

In this module, you will learn:
* Basic transcribing guidelines
* How to create and edit text regions in Transkribus
* How to use style and metadata tags in Transkribus

<!--Link somewhere the transcribing a letter start-to-finish video https://youtu.be/-cDD9P0rnLw-->
<!--Link to Transkribus Installation page somewhere https://readcoop.eu/transkribus/wiki/download-and-installation/-->

# I. Transcribing Guidelines

In order to maintain the integrity of your original document while you are translating it for the computer, consider a few things while you're transcribing.

## Stay as true to the document as you can!
* Include all text as it is written. This includes errors in spelling and grammar, and words you might not be familiar with. Transcribing is NOT editing!
* If there are images in the text, describe them in brackets (e.g. "[doodle of a curly-haired smiling face]").
* Keep it simple! You want people to be able to read the transcription without looking at the original letter. Your transcriptions will be plain text files (e.g. files with no formatting), so, without editorializing, keep the text readable as possible.
<!--link to Smithsonian Guidelines https://transcription.si.edu/instructions-->

## If you have trouble reading the text...
  * Take a break and come back. Fresh eyes make a difference!
  * Try to read the words in context. The word might look like "fhe," but it doesn't make sense to read "And then fhe called her sister." You would realize the word is "she."
  * Ask for help. Send a screenshot to your classmates, or post it in the Teams channel.
  * If you've tried all these things, and it's just not possible to figure out, write [illegible] in brackets and tag that text with the "gap" tag (more on tags in section IV!).

## Take notes while you are transcribing
* Make note of things you don't understand, and Google them to see if you can make sense of the reference.
* You might find something interesting that you want to come back to! Take notes of the letters you transcribe, and what you find interesting about them.

<!--examples of transcription images as formative assessment-->


# II. Text Regions in Transkribus

Before we get started actually transcribing, we have to tell Transkribus what parts of the page have text on them, and what order to read that text! (Remember, computers aren't smart enough to read like humans!)

## Run a Layout Analysis

1. Double click the document you’ve uploaded, and click on the Tools tab. 
2. Under Layout Analysis, make sure you’ve selected all pages.
3. Click Run

<!--Screenshot from https://docs.google.com/document/d/1ogfhkVSdr3QtiXzqLc-sSA0qWtS_WJgzOMGH5ZF8VwY/edit?usp=sharing-->

4. A notification that the layout analysis is in progress will pop up. After a few moments (between 3 and 10 seconds), the layout (green squares, blue rectangles, and dark blue lines) will appear over the letter’s text.
5. Correct errors in the layout (e.g. delete text regions or lines that don’t cover text, resize regions that cut off text, reorder line numbers, or merge lines that have been split). Screenshots of example corrections:

<!--screenshot1-->
<!--screenshot2-->
<!--screenshot3-->

# III. Handwritten Text Recognition

We are using the Transkribus software because it allows you to create Handwritten Text Recognition (HTR) models. <!--link to HTR blog post?--> Over the past 2 years, we have transcribed over 100 letters, and trained the program to begin to recognize Pauline Smith's handwriting. This allows us to run the model on letters in the collection, and start with a more complete transcription to correct, rather than having to transcribe the letter from scratch. 

1. To transcribe with the HTR model, click on the Tools tab, and under Text Recognition, select the model called “Pauline Smith.” You might have to navigate to the next page to find the Pauline Smith model.

<!-- 2 screenshots-->

2. Click Run. The HTR analysis may take anywhere from 20 seconds to 2 minutes. A notification that the “job” is done will pop up when analysis is complete. From there, correct the transcription.
3. Transcribe each page as you see it, following Smithsonian and Transkribus transcription guidelines. 
4. Mark your progress as you complete each page.

<!--Progress screenshot-->

5. After you've completed editing the transcription, go back over the letter, making sure you didn't miss typos, and you can simultaneously begin tagging the document, which will be explained in the next lesson! 

# IV. Metadata Tags

Tagging, annotating, or marking-up a document is a common practice for text analysis. Why is this? Think about the things someone might talk to you about in a letter. They might mention people they talked about, places they went, or a book they read. Now think about the contents of 6,000 letters, and all of this information together! Tagging will allow us to use the information in the collection of thousands of letters to track these trends over time. 

Think of tagging the letter like highlighting categories of information with a different color highlighter. All of the people's names are blue, the places are purple, etc. Transkribus does the same thing.

## Categories of metadata tags

It is tempting to tag everything, but not necessary! You only need to tag:
1. Important words (e.g. people and places)
2. When you add something for clarity that isn't there originally (e.g. "[illegible]"). 
3. If you want to provide further information as context.

## Metadata tags, defined.

Here are the tags we have, up until now, decided to use for the Smith Collection. <!--more tag info at https://readcoop.eu/transkribus/howto/how-to-enrich-transcribed-documents-with-mark-up/-->

1. **person** - when any person’s name is mentioned within the body of the letter (e.g. “Daddy,” Martha, Gilbert, etc.)
2. **place** - when a place name is mentioned within the body of the letter. This does not usually include general places like Sunday school or hospital. Examples would be town names like Bruce or Memphis.
sender - The person who sent the letter, either in the return address, or in the letter’s closing.
3. **recipient** - The person the letter is addressed to, either on the envelope, or in the salutation.
4. **address** - The address the letter was sent to.
5. **return-address** - the address the letter came from (not always included)
6. **organization** - a specific group, corporation, or entity (e.g. the Senate, the T.V.A., or Ole Miss), not a generic place like hospital or school.
7. **sic** - for an error in the original letter (i.e. spelling, grammar, etc.) that you include it in the transcript for accuracy, tag it with “sic,” showing that it’s “as is,” and you didn’t make the error in transcribing.
8. **title** - the title of a book, play, radio show, government decision, etc. Anything that is published, for example. Specifications may include full title, author, and publication date.
9. **date** - a specific date (e.g. January 15th, 1948). This does not include general references to days of the week or years (e.g. “Saturday nite” or “next year.”)
10. **unclear** - when you write something in the transcription, but aren’t sure of what it actually says in the letter: a guess.
11. **gap** (formerly supplied) - when you include something (i.e. [illegible], a note, etc.) that isn’t in the original letter to give clarity, but to prevent the HTR from picking up the note.

<!--Assessment with examples of different scenarios for tags. Include recipient v. person, place v. organization, title, gap, and return address-->

## How to tag something

1. To tag something, highlight the text you want to tag, right-click, and from “All tags,” select the relevant tag.
<!--screenshot-->

2. If the tag isn’t in the list, go to the metadata menu, then the Textual menu, and click Customize. 
<!--screenshot-->
3. Click “Create new tag,” then type in the name of the tag, lowercase, like it’s shown in the Tag definitions document. 
<!--screenshot-->

