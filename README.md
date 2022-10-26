# Readability

This is a Python program that calculates the approximate grade level required to understand a piece of text. It is based on the [Coleman-Liau index](https://en.wikipedia.org/wiki/Coleman%E2%80%93Liau_index), a formula for computing the U.S. grade level for a given block of text. The formula is:

```TeX
index = 0.0588 * L - 0.296 * S - 15.8
```

where `L` is the average number of letters per 100 words in the text, and `S` is the average number of sentences per 100 words in the text.

## Getting started

Clone the repository by running the following command in your terminal:

```bash
git clone https://github.com/SAIS-Hack-Club/readability.git
```

Then, you should see a folder called `readability` in your current directory. Change into that directory by running:

```bash
cd readability
```

Now, run `ls` to see the contents of the folder. You should see a file called `readability.py`. This is the Python program that you will be building on. There is also a file called `helpers.py` which contains some helper functions that you can use in your program. You can read more about them in the comments in the file.

## Sample usage

```bash
$ python3 readability.py
Text: Congratulations! Today is your day. You're off to Great Places! You're off and away!
Grade 3
```

## References

This problem is a modified version of Problem Set 6 from [CS50](https://cs50.harvard.edu/x/). The original problem description can be found [here](https://cs50.harvard.edu/x/2020/psets/6/readability/).
