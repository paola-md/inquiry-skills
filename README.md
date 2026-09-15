# Teaching and measuring multidimensional inquiry skills

Notebooks and study materials for the experiment on inquiry strategies in an interactive simulation (PhET Beer's Law Lab): parsing the logs, sequencing actions, labelling them by strategy, and clustering students into profiles.

**Teaching and Measuring Multidimensional Inquiry Skills using Interactive Simulations**  
Ekaterina Shved, Engin Bumbacher, Paola Mejia-Domenzain, Manu Kapur, Tanja Käser. *AIED 2024*, 2024.  
[DOI](https://doi.org/10.1007/978-3-031-64302-6_34) · [Preprint](https://osf.io/ag3tb) · [Abstract and BibTeX](https://paola-md.github.io/papers/teaching-and-measuring-multidimensional-inquiry-skills-using-interactive.html)

This is a fork of [epfl-ml4ed/inquiry-skills](https://github.com/epfl-ml4ed/inquiry-skills), kept under my account with a standardised README and a clean-up pass (unused imports, stray OS files, personal paths). The code is otherwise as published; open issues upstream.

## What is here

```
Parser.ipynb       raw log files to dictionaries
Sequencer.ipynb    dictionaries to (state, action) sequences
Labeling.ipynb     actions labelled by inquiry strategy
Clustering.ipynb   the multi-step clustering into profiles
Experiment Flow.pdf            structure of the experiment
Pre-test Inquiry skills.pdf    the pre-test
Tests Answers.pdf              answer keys
Beers Law Lab sim.html         the simulation as the students saw it
LICENSE
```

## How to run

Run the four notebooks in the order listed. They expect the raw simulation logs, which are not included.

## Data

The student logs are not public.

## Cite

```bibtex
@incollection{shved2024teaching,
  title      = {{Teaching and Measuring Multidimensional Inquiry Skills using Interactive Simulations}},
  author     = {Ekaterina Shved and Engin Bumbacher and Paola Mejia-Domenzain and Manu Kapur and Tanja Käser},
  year       = {2024},
  booktitle  = {Lecture Notes in Computer Science (AIED 2024)},
  publisher  = {Springer Nature},
  doi        = {10.1007/978-3-031-64302-6_34},
  url        = {https://paola-md.github.io/papers/teaching-and-measuring-multidimensional-inquiry-skills-using-interactive.html}
}
```


## Licence and status

MIT, see `LICENSE`.

Not maintained: kept as the record of the paper.
