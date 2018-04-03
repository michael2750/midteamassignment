# midterm_assignment
### This assignment was made in a group by Laura Hartig, Tim Hemmingsen, Ørvur Guttesen and Michael Daugbjerg.
### Project 2
[Click here](https://github.com/michael2750/startCodeForTesting1) to review the code.

The first thing we did for this assignment was to setup the test enviroment for this project and followed the guide to setup the DateFormatter class aswell as the test.

We refactored our code using Mockito to mock the used objects in JokeFetcherTest by the `@Mock` annotation.
Also we used jupyters `assertAll` to iterate over multiple jokes. 

The image below shows the results of the two test classes DateFormatterTest and JokeFetcherTest with all test passed.
![test results](https://github.com/michael2750/midterm_assignment/blob/master/test-results.PNG)

The image below shows that we have a total code coverage on 45.21%, but this include the getters for the different jokes which is not supposed to be covered by tests.
![jacoco image](https://github.com/michael2750/midterm_assignment/blob/master/jacoco-coverage.PNG)
