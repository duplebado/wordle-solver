## Wordle Solver

### Objective

This is a script to solve the worldle game.

Don't know what Wordle is? Here [here is a proper explainer by the good folks at C|NET](https://www.cnet.com/how-to/wordle-explained-what-you-need-to-know-about-the-viral-word-game/).

#### How To Use Wordle Solver

Wordle Solver is an interactive script that requires inputs from you to effectively solve the Wordle challenge.

Start Wordle Solver by running the command `npm start`

After `Wordle Solver` has been launched, `Wordle Solver` would ask if you want the first word to try autogenerated for you or you'd rather a word of your choice. The valid response to this is either `yes` or `no`.

If you used a word of your choice, you'd be prompted to enter it, so `Wordle Solver` is aware.

Subsequently you'd be asked the `color representation` of the word you attempted to use in solving `Worldle`. Color representation is simply the color feedback from `Wordle` on each attempt.

`colorRepresentation should be exactly 5 characters (each a digit between 0 and 2) long`
`The digits 0 - 2 denotes color of each letter of the word`
`0 means grey`
`1 means yellow`
`2 means green`
`Examples are: 01222, 00000, 01112, 22210, e.t.c`

Have fun!
