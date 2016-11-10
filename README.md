# The US-2014 Airline Recovery Dataset

This repository was created by Hewlett Packard Labs to host the dataset used in an Airline Recovery Management project performed in 2016 and publicized in our paper [here (TBD)](http://tbd.tbd). 

The source data (airlines_tables.tgz) and scenarios themselves (scenarios.tgz) are hosted in this [dropbox](https://www.dropbox.com/home/Personal/US2014). Scenarios are given in two formats. The [ROADEF09'](http://challenge.roadef.org/2009/en/sujet.php) format, and a database dump of a vertica database we used. 

The [wiki](https://github.com/tomersagi/us2014/wiki) contains instructions how to generate new scenarios from this dataset. 

The code contains some auxilliary tables, the code for a plan validator, and java code which can be used to parse the scenarios from the database.
