# Tile Correction Rules 

For each of the files in the directory I am going to give you, you are going to `spawn` a sub-agent which is goin to perform the task underneath.
If there are other directories you may procced recusively.

--- 

## Task 

All title, subtitle, sub-subtitles in this project should be in **Title Case**, this means that connectors such as "the, an, ..." are only 
capitalized under certain circunstances. Mostly the standard **APA Style**.

```txt 
Title Case Capitalization

APA Style uses two types of capitalization for titles of works (such as paper titles) and headings within works: title case and sentence case.

In title case, major words are capitalized, and most minor words are lowercase. In sentence case, most major and minor words are lowercase (proper nouns are an exception in that they are always capitalized).

major words: Nouns, verbs (including linking verbs), adjectives, adverbs, pronouns, and all words of four letters or more are considered major words.
minor words: Short (i.e., three letters or fewer) conjunctions, short prepositions, and all articles are considered minor words.
Learn more
Title case capitalization is covered in the seventh edition APA Style manuals in the Publication Manual Section 6.17 and the Concise Guide Section 5.7

This guidance has been expanded from the 6th edition.

How to implement title case
In title case, capitalize the following words in a title or heading:

the first word of the title or heading, even if it is a minor word such as “The” or “A”
the first word of a subtitle
the first word after a colon, em dash, or end punctuation in a heading
major words, including the second part of hyphenated major words (e.g., “Self-Report,” not “Self-report”)
words of four letters or more (e.g., “With,” “Between,” “From”)
Lowercase only minor words that are three letters or fewer in a title or heading (except the first word in a title or subtitle or the first word after a colon, em dash, or end punctuation in a heading):

short conjunctions (e.g., “and,” “as,” “but,” “for,” “if,” “nor,” “or,” “so,” “yet”)
articles (“a,” “an,” “the”)
short prepositions (e.g., “as,” “at,” “by,” “for,” “in,” “of,” “off,” “on,” “per,” “to,” “up,” “via”)
```
:w

Your **task** is to convert all wrongly titles to this standard.

### Recomendations

- To be more efficient, only get the necessary line numbers where chapters, sections, subsections and subsubsections are present with their respective content.
- Then proceed to edit those lines explicitely instead of reading unncessary contents.

### Constraints

- You are only allowed to change titles, subtitles, etc. no more. Paragraphs and other type of content in this document are prohibited.
- Modify only one file at time. 
- You should keep the hierarchy of the titles. 

--- 





