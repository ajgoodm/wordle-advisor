# wordle-adviser
Solve Wordle puzzles with various strategies

Wordle is a game that became popularized in late 2021. You can play Wordle [here](https://www.powerlanguage.co.uk/wordle/),
and can read more about the development of the game in this [NYTimes story](https://www.nytimes.com/2022/01/03/technology/wordle-word-game-creator.html)

This command line utility is an assistant to playing Wordle. It's a personal exploration
of the strategy of Wordle and will provide solutions along several strategies
(e.g. minimize the worst-case final score, minimize the expected final score, ...)

For now, this only supports filtering 5-letter words to viable guesses. To run,
make sure you have the [Rust tool chain installed](https://doc.rust-lang.org/book/ch01-01-installation.html)
and then start the CLI with:

```bash
cargo run
```
