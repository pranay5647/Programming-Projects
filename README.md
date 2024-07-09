# Programming-Projects
ECS7023P - Programming for Artificial Intelligence and Data Science - Projects Completed for this module are presented here. 

# Coursework 1: Movie ratings
This is the first coursework of ECS7023P Programming for AI and Data Science, which counts 35% towards the final grade of the module. The coursework is graded out of 100 marks.

**Deadline:** Thursday 5th October, 2023 - 11.59pm

**How to submit:** You will submit a completed Jupyter notebook file with your solutions, as well as a PDF version of the Jupyter notebook which includes the outputs of your code. You need to submit the python code that produces the required answers. Answers produced through means other than python code will not be deemed acceptable.

**Note:** This is an individual coursework, the solutions you submit need to be your own and developed on your own.
## Dataset
For this exercise, you are given a dataset that contains information about a collection of movies, along with ratings assigned by 2,500 users to those movies.

The dataset contains two files:
* movies.json: a JSON file with information about movies, including their ID, title, language, release date, country(ies) of origin and genre(s).
* ratings.csv: a CSV file that contains an entry for each movie rating, where a user ID rates a movie ID with a rating on a likert scale from 1 to 5 at a particular time.

The **movieId** column in ratings.csv can be linked to the IDs within movie.json, so you know which particular movie a user is rating in each case.

**Note:** ratings.csv contains entries only for movies that each user has rated, i.e. for many movies, a user may not have entered any ratings so we don't have that information.

# Coursework 2: Wikipedia articles
This is the second coursework of ECS7023P Programming for AI and Data Science, which counts 65% towards the final grade of the module. The coursework is graded out of 100 marks.

**Deadline:** Thursday 2nd November, 2023 - 11.59pm

**Marking criteria:** While the most important marking criterion will be for the code to achieve the expected objective and output, marks will also be given for partial or close solutions, whereas marks can be deducted for code that is overly complex, inefficient, difficult to understand and/or to maintain.

**Use of packages:** In addition to built-in python functions and elements that we have seen in the lectures (see lecture notes), the only additional packages allowed for this exercise include *string* and *json*.

**How to submit:** You will submit a completed Jupyter notebook file with your solutions, as well as a PDF version of the Jupyter notebook which includes the outputs of your code (either two separate files or a single zip file that contains both the .ipynb and .pdf files). Your submission will include the python code that produces the required answers. Answers produced through means other than python code will not be deemed acceptable.

**Note:** This is an individual coursework, the solutions you submit need to be your own and developed on your own.
## Dataset
For this exercise, you are given a dataset that contains a sample of Wikipedia articles, with their content reduced to only text (that is with images and other non-textual content removed).

The dataset is contained in a file called 'wiki-articles.json', where each line contains an entry with a Wikipedia article: an ID, a URL, title and body text.
## Note
**Note:** For this coursework, you should remove all the punctuation prior to processing the text. To do this, use the following code, where *text* is the variable where you want to remove the punctuation:

```
import string

translator = str.maketrans('', '', string.punctuation)
text = text.translate(translator)
```
