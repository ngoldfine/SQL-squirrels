# SQL Squirrels
Using SQLite to answer questions about the 2018 Central Park Squirrel Census

### The Squirrel Census

In October 2018 a team of volunteers descended upon New York City's Central Park with an ambitious goal: count all the squirrels.

The Squirrel Census is self-described (on the group's [about page](https://www.thesquirrelcensus.com/about)) as "a multimedia science, design, art, and storytelling project focusing on the Eastern gray (Sciurus carolinensis)... _Yes, this is real_". The group has launched projects counting squirrels in parks in NYC and Atlanta over the course of the last decade. In their 2018 Central Park census, they recorded details of the appearance, location and behavior of over 3,000 squirrels. This is pretty impressive, if a little unusual.

The Squirrel Census have kindly made their 2018 Central Park data available for download [here](https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw/about_data) on NYC's OpenData website.

### SQL Squirrels

Using the OpenData dataset, SQLite, and a little bit of Python in Jupyter Notebooks, I am exploring the data collected in the 2018 Squirrel Census.

My partial data exploration is structured around questions. Are squirrels with certain fur colors more likely to approach humans? Are adult squirrels or juvenile squirrels more likely to run? (Unfortunately, questions such as _"Why try to count every squirrel in Central Park?"_ are beyond the scope of this project.)

**Files:**
- `set_up_database.ipynb` imports the census data into a SQL database.
- `questions.ipynb` is where the ✨magic✨ happens. The questions about the census data and their answers are here, along with cells containing my SQL queries (and a smidge of Python).
