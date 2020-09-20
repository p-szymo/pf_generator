# pf_generator

Using [Max Woolf](https://minimaxir.com/)'s [textgenrnn](https://github.com/minimaxir/textgenrnn) and a PoetryFoundation corpus (created in this [project]('https://github.com/p-szymo/poetry_genre_classifier')), I build character-based and word-based LSTM models capable of generating poetry.

## Future steps

Create an app.

Make separate models for each movement of poetry used in this [project]('https://github.com/p-szymo/poetry_genre_classifier') and analyze the differences between their respective generated texts.

In a larger context, I'd like to use the process here to train an LSTM model on Markov chain poetry generations across several corpora. I envision some sort of text generation loop, the visual/written equivalent of audio feedback.

EARLY STAGES!!

## List of files
- **archives** folder - scrap and backup files.
- **data** folder - text files to use as a source for the generator.
- **gens** folder - screenshots and text files of choice generations.
- **.gitignore** - list of files to ignore.
- **README.md** - this very file!
- **pf_generator.ipynb** - workbook using textgenrnn to develop LSTM models.
	- NOTE: best used in Google Colab, for much faster computation.
- **text_gen.ipynb** - workbook using models to generate poetry.

<!-- - **Procfile** - requirement for Heroku deploy. -->
<!-- - **app.py** - file with app layout and tankanizer function call. -->
<!-- - **requirements.txt** - requirement for Heroku deploy.
- **setup.sh** - requirement for Heroku deploy. -->