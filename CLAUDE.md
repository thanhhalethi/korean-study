# Korean and Japanese vocabulary study

I am learning Korean and Japanese. Each language has its own folder:
korean/ holds questions/, keys/, vocabulary.md and grammar.md for Korean.
japanese/ holds questions/, keys/, vocabulary.md and grammar.md for Japanese.

## Detecting the language
Look at the script of the word or phrase I give you.
If it uses Hangul, it is Korean, so work only inside korean/.
If it uses Hiragana, Katakana or Kanji, it is Japanese, so work only inside japanese/.
If it is unclear, ask me which language I mean.

## Steps
When I give you one or more words, or a phrase containing both vocabulary and grammar:
1. Search all files in the questions/ folder of that language for each word.
2. Words change form, so search using the word stem to also find the variations.
   Korean example: 먹다 can appear as 먹어요, 먹었어요, 먹고.
   Japanese example: 食べる can appear as 食べます, 食べた, 食べて, so search for 食べ.
3. For each match, show the file name and the full sentence containing that specific word. If more than one sentence contains that word, just pick a random one among them.
4. Add the word to that language's vocabulary.md with its meaning and its number in the list. Skip it if it is already there. Note if the word is a noun (n), a verb (v), an adjective (adj), etc. Number the words, do not start them with a bullet point or a hyphen.
   Korean example: 1. 먹다 (v) to eat
   Japanese example: 1. 食べる (たべる) (v) to eat
   For Japanese words containing Kanji, always add the reading in Hiragana.
5. If there is a grammar point in the phrase I provided, add it to that language's grammar.md (create the file if needed) with its usage and its number in the list. Skip it if it is already there. Number the grammar points, do not start them with a bullet point or a hyphen.

Keep explanations short and clear. Use English for explanations.

For now, if i ask you about japanese words, do not add into vocabulary.md yet. i am only learning how to read japanese words