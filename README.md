"this is repository for project_1 which is done using hive"
# Analyze MovieLens data

## Project Description

I set up a standalone single node cluster in Hadoop to utilize YARN and HDFS to perform Apache Hive queries through a CLI application to analyze data from a Movie-lens dataset.
## Technologies Used

* Hadoop - version 2.7.3.2.6.5.0-292
* HDFS - version 2.7.3.2.6.5.0-292
* Hive - version 2.6.5.0-292

## Features

List of features ready and TODOs for future development
* using this project some query are solved using hiveQL following query are listed below:

* 01. first 5 entries from movies table
* 02. number of unique movies
* 03. summary of ratings data
* 04. minimum rating given to a movie
* 05. maximum rating given to a movie
* 06. is any row null in tags
* 07. number of unique tags 
* 08. drop null rows from tags and create another table of the resulting rows
* 09. filtering to get the list of drama movies
* 10. total number of drama movies
* 11. filtering to get the list of comedy movies
* 12. total no. of comedy movies
* 13. search movie id by tag search
* 14. displays first 5 data from ratings table
* 15. merging two tables movies and ratings into a new table without the "timestamp" column from the ratings table.
* 16. display high rated movies (rating > 4)
* 17. display low rated movies (rating < 4)
* 18. total number of unique movie genres
* 19. top 25 most rated movies
* 20. slicing out columns to display only title and genres columns from movies table
* 21. extract year from title of the movie
* 22. count how many times each of genres occur
* 23. Which movie received the highest number of ratings?



## Getting Started
   
(include git clone command)
(include all environment setup steps)

> Be sure to include BOTH Windows and Unix command  
> Be sure to mention if the commands only work on a specific platform (eg. AWS, GCP)

- All the `code` required to get started
- Images of what it should look like

## Usage

> Here, you instruct other people on how to use your project after they’ve installed it. This would also be a good place to include screenshots of your project in action.

## Contributors

> Here list the people who have contributed to this project. (ignore this section, if its a solo project)

## License

This project uses the following license: [<license_name>](<link>).


