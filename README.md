# midterm_assignment
#### This assignment was made in a group by Laura Hartig, Tim Hemmingsen, Ørvur Guttesen and Michael Daugbjerg.

### Project 1

[Click here](https://github.com/michael2750/midterm_assignment/blob/master/RecognitionAllIT.java) to review the test class.

The test class RecognitionAllIT is an extention from the frist `@Test` method used in the RecognitionIT test class. The main difference is that RecognitionAllIT uses `Parameterized testing`, which is easy to handle and safes us from making alot of test cases. The `@RunWith(Parameterized.class)` annotation tells the class to run all the parameters given as an injection to the `@Test`. We got a total of 54.64% passed tests, and this reveal which of the images that fails to the recognition system.

### Project 2
[Click here](https://github.com/michael2750/startCodeForTesting1) to view the startCodeForTesting1 project.

The first thing we did for this assignment was to setup the test enviroment for this project and followed the guide to setup the DateFormatter class aswell as the test.

We refactored our code using Mockito to mock the used objects in JokeFetcherTest by the `@Mock` annotation.
Also we used jupyters `assertAll` to iterate over multiple jokes. 

The image below shows the results of the two test classes DateFormatterTest and JokeFetcherTest with all test passed.
![test results](https://github.com/michael2750/midterm_assignment/blob/master/test-results.PNG)

The image below shows that we have a total code coverage on 45.21%, but this include the getters for the different jokes which is not supposed to be covered by tests.
![jacoco image](https://github.com/michael2750/midterm_assignment/blob/master/jacoco-coverage.PNG)

### Project 3

[Click here](https://github.com/cph-lh/monopoly) to view the monopoly project.

All our objects are mocked, which means that we can test our method even without  implemeting them yet. When implemented, the classes can be used to test the method.
The method results from the classes we use are also mocked up. This means the results are the same every time, which is good when we test our die/dice since they gives us a random number. Our coupling is low which means we can easily mock our classes and put the actual one in when we are done.
With mocking can we easily TDD and make our tests before we have made the code working. So writing test before coding is also much easier with mocking.
