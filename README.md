# Readability

This is a Python program that calculates the approximate grade level required to understand a piece of text. It is based on the [Coleman-Liau index](https://en.wikipedia.org/wiki/Coleman%E2%80%93Liau_index), a formula for computing the U.S. grade level for a given block of text. The formula is:

```TeX
index = 0.0588 * L - 0.296 * S - 15.8
```

where `L` is the average number of letters per 100 words in the text, and `S` is the average number of sentences per 100 words in the text.

## Getting started

### Prerequisites

You will need Python 3.6 or later to run this program. You can check your version of Python by running `python3 --version` in your terminal. If you do not have Python 3.6 or later, you can download/update it in Self Service. If you are confused about how to do this, please ask me for help.

This is a [template repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template), and you can generate your own version of this repository by clicking on the green `Use this template` button on the home page. Once you have created your new repository, you can then clone it to your computer via the command line:

```bash
git clone https://github.com/<your-github-username>/readability.git
```

Then, you should see a folder called `readability` in your current directory. Change into that directory by running:

```bash
cd readability
```

Now, run `ls` to see the contents of the folder. You should see a file called `readability.py`. This is the Python program that you will be building on. There is also a file called `helpers.py` which contains some helper functions that you can use in your program. You can read more about them in the comments in the file.

## Your task

Your task is to complete the `readability.py` program so that it calculates the approximate grade level required to understand some text. You should use the `get_string` function from the `helpers.py` file to prompt the user for a string of text (using `input`). Then, you should print the grade level using the `print` function after calculating it using the Coleman-Liau formula.

## Sample usage

```bash
$ python3 readability.py
Text: Congratulations! Today is your day. You're off to Great Places! You're off and away!
Grade 3
```

```bash
$ python3 readability.py
Text: Maybe it's not the mountains ahead to climb that wear you out; it's the pebble in your shoe.
Grade 6
```

## Submission

To submit, commit your changes and push them to your fork of the repository. Then, send me a link to your forked repository on Google Chat. If you are confused about how to do this, please ask me for help.

- [ ] Fork this repository
- [ ] Clone your fork to your computer
- [ ] Complete the `readability.py` program
- [ ] Commit your changes
- [ ] Push your changes to your fork
- [ ] Send me a link to your fork on Google Chat

## References

This problem is a modified version of Problem Set 6 from [CS50](https://cs50.harvard.edu/x/). The original problem description can be found [here](https://cs50.harvard.edu/x/2020/psets/6/readability/).
