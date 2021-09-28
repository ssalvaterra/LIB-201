# Introduction to Text Analysis

words about text analysis

### Objectives

### Lessons
1. Distant Reading
2. Select Distant reading methods
<!--3. Text cleaning methods-->

### Required Reading

<!--Required Tools-->

### Acknowledgements
- "Distant Reading, Modeling, and Concordances," Brandon Locke and Thomas Padilla, NEH Textual Data Institute, 2018

# 1. Distant Reading

## Distant v. Close Reading
If you have been in an English class before, you are familiar with the phrase "close reading." If you have not, close reading refers to choosing part of a text - a word, a symbol, an image - to closely analyze the context of the whole work. In other words, why did the author make these word choices? What factors (e.g. historical, intellectual, subliminal, etc.) have gone into influencing the text that show up in this text over and over again? Close reading is one method used analyze a text. Distant reading, which uses computer assistance to process large amounts of text, is the method we are going to use!

Distant reading with computers is not a way to replace the levels of interpreting that humans are able to do! In fact, distant reading <a href="https://en.wikipedia.org/wiki/Index_Thomisticus">is possible without a computer</a>--the work of the computer just saves time!  Additionally, distant reading loses its impact without the context and interpretation from human eyes. <!--cite the several opinions on this?--> All sorts of distant reading projects have enhanced and changed the ways we look at entire works of a specific collection, an author, or even genre. <!--cite these?--> Like close reading, though, distant reading will allow us to address a hypothesis about a text, and through analysis and interpretation, address that hypothesis with textual evidence.

Unlike close reading, distant reading allows us to:
* Link specific words to the context in which they were used throughout a text (as in a concordance)
<!--image-->
* Visualize a single text (or a collection of texts, allowing us to 
    - interact with it graphically
    - compare patterns up close and zoomed out
    - gain new insight
<!--image-->
* See patterns or changes in a text(s) over time 
<!--image-->
* Compare one author's body of work to another, to
    - identify distinctive vocabulary (This person used this word more than that person)
<!--image-->
* Structure a text with
    - hyperlinks
    - other metadata
<!--* Model or predict an explanation-->
<!--* unsupervised modeling-->
* and more!

## How does this work?

    "The difference between the almost right word and the right word is the difference between lightening and a lightening bug" -Mark Twain

Words are so messy! You and I can understand them only after growing up and speaking a language for many years, and even then, we all have different ways of saying and understanding things! So how does a computer begin to "understand" words? With most tools, this is something that goes on automatically, in the background. But let's take a peek behind the curtain.

## Tokenizing

Computers can recognize characters in sequence. But what words say, and what they mean, aren't always so clear! So in order to have a computer "read" something and pull information from it, you have to "tokenize" a text. Tokens can be separated by spaces, but they can also be punctuation (hyphens, commas, parentheses), they could be differently capitalized, and they can have different meanings, even though they're spelled the same way. <!--use example from letters?-->

    Hello, I am the all-knowing magician!
 
 To a computer, this is just a series of characters. A computer might separate ```all``` from ```knowing``` when tokenized, simply because they are joined by a hyphen. But that changes the meaning of the sentence. By tokenizing, we can tell the computer what and how we want it to read.

* Hello
* ,
* I
* am
* the
* all-knowing
* magician
* !

## Lemmatizing

Lemmas are root words, or common base words for different variations of a word. Lemmatizing a word is a Natural Language Processing process, which groups words by their roots and parts of speech for analysis. For example: 

| Word | Lemma |
|------|--------|
| good, better, best | good |
|library, librarian, libraries | librar |
| sounding (v.), sounds (n.) | sound |

You can look at all of the instances of the sentiment "good" by lemmatizing the words that mean "good" (i.e. better and best) at their root.

## Stop Words
In a large text, stop words are words like "the," "some," "of," <!--link to a stop word list--> "that," etc. that you would like to exclude from analysis. These words are determined to be of less value than the other words, but be warned! Sometimes these little words mean a lot! See this blog post about <a href="https://onezero.medium.com/how-data-science-pinpointed-the-creepiest-word-in-macbeth-3150995d3808">"the creepiest word in Macbeth"</a> to see why!

<!--not a perfect process. These distant reading methods will, like language, always throw an error that is going to be an exception to a conventional rule-->

<!--Check-in - tokenizing, lemmatizing, stop words, put distant reading in your own words, and examples of what it lets us do (with pictures? Matching??)-->



