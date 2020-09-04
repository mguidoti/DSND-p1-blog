# README
This is my work for the very first project of the [Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025) from Udacity.

You can access my [blog post here](https://hackmd.io/@mguidoti/S1HcGMJ4w).

### Disclaimer
I applied the [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/) in this repository, with one addition to the type list: `file`, used when I uploaded or changed non-coding files, like the charts' *.png.

I also used [Pipenv](https://pipenv-fork.readthedocs.io/en/latest/), hence the [Pipfile](https://github.com/mguidoti/DSND-p1-blog/blob/master/Pipfile) and [Pipfile.lock](https://github.com/mguidoti/DSND-p1-blog/blob/master/Pipfile.lock) in this repository.

```
In fact, I wrongly use files, in plural (commit 8fbda29).
```

### Files
```
|--charts
  |--question_01.png
  |--question_02.png
  |--question_03.png
  |--question_04.png
  |--question_05.png
|--data                                             # Data and related files
  |--README_2020.txt
  |--so_survey_2020.pdf
  |--survey_results_public.csv                      # Raw data
  |--survey_results_schema.csv
|--.gitignore
|--.LICENSE
|--Pipfile
|--Pipfile.lock
|--README.md
|--stackoverflow_survey_2020.ipynb                  # Actual notebook with all code
```

## Motivation
Well, I have a PhD and I'm trying to break into the tech industry. With that being said, and, after [Josh Bernhard's Medium post on how to become a programmer](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711) where Josh analyzed the strategy people used to break into the field, I felt compelled to take a quick look on how sucessfull were the people that also have PhDs or any other doctoral degree - and perhaps more importantly, if their outcome have anything to do with their field of origin.

## Data
I used the [Stack Overflow Developer Survey 2020](https://insights.stackoverflow.com/survey) in this project. It has around 60 different questions and almost 65000 respondents.

From their [own website](https://insights.stackoverflow.com/survey/2020#overview):
> This year, rather than aiming to be the biggest, we set out to make our survey more representative of the diversity of programmers worldwide. That said, the survey is still big. This year’s survey was taken by nearly 65,000 people.

## Questions
1. What's the employment rate of the group and how does it compare with the other educational backgrounds?
2. What's the employment rate per field of origin?
3. Can the differences in the employment rate per field of origin be explained by the average programming experience, prior to first pro activity?
4. Can we draw any conclusions on the observed average compensation per field of origin?
5. Is there any field of origin that is more succesfull (job satisfaction X compensation) than the others?

## Libraries
- [pandas](https://pypi.org/project/pandas/)
- [numpy](https://pypi.org/project/numpy/)
- [ipykernel](https://pypi.org/project/ipykernel/)
- [matplotlib](https://pypi.org/project/matplotlib/)

## Summary of Results
1. Actually, surprisingly enough, doctoral degree holders have the highest employment rate.
2. Natural sciences, my field of origin, is not fair away from Social Sciences, which presented the highest employment rate.
3. Fine & Perfoming Arts presented the largest experience before first job. Natural sciences were in the middle, closer to the top than to the bottom.
4. Social Sciences presented the highest average, on top of Info. Systems and Engineering. Natural sciences was again in the middle, closer to Social Sciences than to the bottom.
5. Matural Sciences had the second largest job satisfaction. Humanities, the highest. Comp. Science & Eng. the lowest.

## Acknowledgements
Matplotlib documentation, StackOverflow (several questions) and [The Python Graph Gallery](https://python-graph-gallery.com/) helped me along the way.

## License
MIT
