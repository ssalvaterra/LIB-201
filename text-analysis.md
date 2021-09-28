# Introduction to Text Analysis

words about text analysis

### Objectives
* Understand the purpose of distant reading when analyzing a text or texts
* Understand the processes by which computers "read" text (specifically stemming, lemmatization, stop words, and tokenization)
* Define text analysis methods, specifically n-gram analysis, topic modeling, and sentiment analysis
* Select a data set from Smith Papers to clean, perform select text analysis methods on, and analyze.

### Lessons
1. Distant Reading
2. Select Distant reading methods
<!--3. Text cleaning methods-->

### Required Reading
<!--
- Fish, Stanley, 2019. <a href="https://critinq.wordpress.com/2019/04/03/computational-literary-studies-participant-forum-responses-day-3-5/">"Computational Literary Studies: participant forum responses, Day 3"</a>
- section from Drucker's Intro to DH or Ketchley's dh101 course guide? -->

<!--Required Tools
- <a href="https://libguides.muw.edu/DSL">Gale Digital Scholar Lab</a>-->
<!--Optional tools 
- <a href="https://voyant-tools.org/">Voyant</a> 
- <a href="https://mimno.infosci.cornell.edu/jsLDA/">jsLDA: In-browser Topic Modeling</a>  - <a href="https://databasic.io/en/wtfcsv/">wtf CSV</a>
- <a href="http://lexos.wheatoncollege.edu/upload">Lexos</a>-->

### Acknowledgements
- "Distant Reading, Modeling, and Concordances," Brandon Locke and Thomas Padilla, NEH Textual Data Institute, 2018
- Screenshots from projects:
    - Froehlich, Heather. <a href="https://blog.oup.com/2015/11/shakespeare-language-gender/">"Analysing what Shakespeare has to say about gender."</a>. _OUP Blog_, 11/28/2015.
    -  King, Lindsay and Leonard, Peter. <a href="http://bookworm.library.yale.edu/">Robots Reading Vogue</a>. _Digital Humanities at Yale University Library_, 2014.
    - Blei, David M., Andrew Y Ng., and Michael I. Jordan. <a href="https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf">"Latent Dirichlet Allocation,"</a> _Journal of Machine Learning Research 3_, 2003. p. 1009. 
    - Healey & Ramaswamy, <a href="https://www.csc2.ncsu.edu/faculty/healey/tweet_viz/tweet_app/">Visualizing Twitter Sentiment,</a> 2019.

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

Words are so messy! You and I can understand them only after growing up and speaking a language for many years, and even then, we all have different ways of saying and understanding things! So how does a computer begin to "understand" words? With most tools, this is something that goes on automatically in the background, often using a pre-defined list of rules or dictionaries. Let's take a peek behind the curtain!

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

These methods - tokenizing, lemmatizing, stop words (there are more) - are still not perfect! Think of these methods as formulas that you are performing on a text en masse, and the English language often resists a formula. Think of all of the "exceptions to the rule" you have had to learn about. Furthermore, consider texts that are not in English. We use these formulas to help us read a corpus distantly, but that won't replace our abilities to read closely.

<b>These methods are automatic for many tools, but let's not forget them!</b> When we encounter errors or strange findings, it might be that we need to tweak them!

<!--Check-in - tokenizing, lemmatizing, stop words, put distant reading in your own words, and examples of what it lets us do (with pictures? Matching??)-->

# 2. Select Distant Reading Methods

In this class, we're going to use specific text analysis methods that are available in the <a href="https://libguides.muw.edu/DSL">Digital Scholar Lab</a>. (Hint: click Databases from the <a href="https://www.muw.edu/library">MUW Library Homepage</a>, and find it under "D."). You'll need to link your Google MyApps account to this database to get started. These are the tools we'll explore...

## N-gram analysis

![Screenshot of a word cloud of William Wordsworth's distinctive vocabulary words in his poems, from Ted Underwood](https://github.com/hillaryAHR/LIB-201/blob/main/text-analysis-images/ngram-wordsworth.JPG)

N-grams are more commonly known as word clouds. You see words of different sizes, indicating the number of times that word is used throughout the text. The "N" in n-gram stands for number of words you are counting or highlighting in a corpus, so you can also do this with phrases. 

N-grams also show the patterns of those words as they're used throughout the text over time (time can be literal - as in, throughout the years, as seen in the screenshot below, or it can be relative to the text itself, as in how the word is used throughout the course of the corpus.)

![Screenshot of Robots Reading Vogue, showing the uses of corset, girdle, bra, bustier, and hosiery over time](https://github.com/hillaryAHR/LIB-201/blob/main/text-analysis-images/ngram-RRV.JPG)

N-grams can also be used to collocate words or phrases and to determine relationships between word pairs. The example below shows how words with positive connotations are more often associated with gendered words.

![Screenshot of Heather Froehlich's analysis of Shakespeare texts, where male-gendered words have more positive connotations (i.e. Man - young) than female-gendered words (i.e. Woman - wretched)](https://github.com/hillaryAHR/LIB-201/blob/main/text-analysis-images/ngram-shakespeare.JPG)

__You'll use an n-gram analysis to explore word pairs, frequencies, and their use over time.__

## Topic Modeling

<!--screenshot of buckets?-->

Topic Modeling is one of the more difficult text analysis methods because it is based on probability. Topic Modeling uses an algorithm (<a href="">Latent Dirichlet Allocation</a>) to find probabilities of words that co-occur. When you run this algorithm on a body of text, it puts the words that are _more likely_ to occur together in categories, or "bags of words." The idea is that each category represents a topic of discussion in the text. 

![Screenshot of Lincoln Sermons Topic keywords split into 10 columns labeled "topic 1," "topic 2," and so on](https://lincolnlogs.digitalscholarship.emory.edu/wp-content/uploads/2013/02/mallet.png)

Topic modeling requires some inference on behalf of the person running the algorithm - how are these groups of words related? How are they used in the text? Do they signify a distinct theme? The column labels below were chosen to reflect the commonalities among the words below them.

![Screenshot of topic modeling results with columns labeled Arts, Budgets, Children, and Education, in colors corresponding to highlighted words within a paragraph](https://i.imgur.com/9UesuuB.png)

## Sentiment Analysis

![Screenshot of sentiment analysis of tweets using #nationalsonsday](https://github.com/hillaryAHR/LIB-201/blob/main/text-analysis-images/SA-sons.JPG)

![Screenshot of sentiment analysis of tweets using #nationaldaughtersday](https://github.com/hillaryAHR/LIB-201/blob/main/text-analysis-images/SA-daughters.JPG)

_Top: Sentiment analysis of tweets using #nationalsonsday_

_Bottom: Sentiment analysis of tweets using #nationaldaughtersday_. Both images from https://www.csc2.ncsu.edu/faculty/healey/tweet_viz/tweet_app/

A sentiment analysis uses natural language processing to "score" words according to a positive or negative scale. Sentiment analyses are trained on a pre-determined set of words (such as the <a href="http://corpustext.com/reference/sentiment_afinn.html">AFINN lexicon</a>), and show (or attempt to show) the overall positive or negative emotions at any given moment within a corpus. 

![Screenshot of the plot of James Joyce's Portrait of the Artist as a Young Man in a sentiment analysis](https://www.matthewjockers.net/wp-content/uploads/2014/06/poa2.png)

Note: Sentiment analyses have limits! Like toddlers, sentiment analyses **do not** detect sarcasm! ::laughing:: They also commonly do not account for the change in meanings of words over time (i.e. sick = ill v. sick = slang for cool).

<!--link to Becky's project?-->

<!-- ## Named Entity Recognition -->

<!--Check-in- vocab matching, examples of each-->

<!-- # 3. Text Cleaning Methods -->


