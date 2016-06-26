# Review

![screenshot](screenshot.jpg)

## Description

Create a project called `People` with [this file](https://raw.githubusercontent.com/oakes/java-assignments/master/projects/People/people.csv) in the project root. Read the csv file into a `HashMap<String, ArrayList<Person>>` that maps country name to a list of people who are from that country. Then loop over the lists in your `HashMap` and sort them by last name.

## Requirements

* Create a `Person` class to store all the columns in the csv file.
* Create a `HashMap<String, ArrayList<Person>>` that maps country name to a list of people from that country.
* Loop over the `HashMap` and sort each list by last name.
* Override `toString` in the `Person` class to print out a nicely-formatted string for that person (something like "Martha Jenkins from France").
* Print out the entire `HashMap` at the end.
* Break your code into separate methods.
* Modify your `compareTo` method so it sorts by first name if the last names are the same.

### Hard Mode
  * Write tests for your methods.
  * Write the resulting `HashMap` to a file called "people.json" formatted as JSON.
