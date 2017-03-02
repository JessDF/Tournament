# Tournament
Udacity Full Stack Developer Nanodegree - Project 4: Swiss System Tournament

SETUP

This program is created and run on a virtual machine using vagrant.
If you don't already have your database created, navigate to the tournament folder (Using Git Bash/ a command line), then type "psql" and enter The following:

    CREATE database tournament

    \c tournament

    \i tournament.sql

You're database should be set up now, type "\q" to quit from the database set up and to return to your command line.
There is a test script that will verify all fuctions of the code and database are interacting properly. To run the test program type:

    python tournament_test.py

If anything isn't working as intended, the system will throw an error message. If all tests pass, you're good to go!
