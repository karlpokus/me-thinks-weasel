# me-thinks-weasel
A Demo of the infinite monkey theorem
> I don't know who it was first pointed out that, given enough time, a monkey bashing away at random on a typewriter could produce all the works of Shakespeare. The operative phrase is, of course, given enough time. Let us limit the task facing our monkey somewhat. Suppose that he has to produce, not the complete works of Shakespeare but just the short sentence 'Methinks it is like a weasel', and we shall make it relatively easy by giving him a typewriter with a restricted keyboard, one with just the 26 (capital) letters, and a space bar. How long will he take to write this one little sentence?

[src](https://en.wikipedia.org/wiki/Weasel_program)

# Procedure
- [x] Start with a random string of 28 characters
- [x] Make 100 copies of the string (reproduce)
- [x] For each character in each of the 100 copies, with a probability of 5%, replace (mutate) the character with a new random character.
- [x] Compare each new string with the target string "METHINKS IT IS LIKE A WEASEL", and give each a score (the number of letters in the string that are correct and in the correct position).
- [x] If any of the new strings has a perfect score (28), halt. Otherwise, take the highest scoring string, and go to step 2.

# Demo
[Demo](http://codepen.io/KarlPokus/pen/gLzdNK?editors=0010)

# Licence
MIT
