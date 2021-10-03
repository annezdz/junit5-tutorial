# JUnit5 by Test Automation University

This is going to be a very interesting journey as we're going to go through all of the features of this framework, and I really hope this is going to be something that will help you to use JUnit 5 in your testing from now on.

Now this is quite an interesting library - it has a lot of great features for our testing, and we will go through all of them chapter by chapter.

We will start with a little bit of setup in order to create a project to write our tests and to enable the use of JUnit 5 in the project.

We will then start with writing a few very basic tests and then we will introduce the so-called lifecycle methods, the befores and afters of this framework.

We will then have a few chapters where we will see how to run the same code from a test method, but with different values that will be passed to the method by means of parameter values.

We will see how in JUnit 5, we can use different ways of providing the values for those parameters.

Then we will take a look at how to run our tests in the order in which we want them to run.

We will take a look at assumptions, which are an interesting feature of this framework - namely, having code run only when certain conditions are met.

After, we will take a look at how to enable and disable tests based on certain conditions.

In chapter 11, we will take a look at how to repeat tests, meaning how to run the exact same test several times.

Then in the next chapter, we will see how we can add tags to our tests, which will allow us to select them based on their tags in order to run them for certain, either CI jobs or for the testing of certain features.

We will introduce assertions in chapters 13 and 14 and we will start with the JUnit 5 specific assertions.

After, we will take a look at how to use assertions from an external library - in the case of this tutorial, we will look at Hamcrest.

We will then go a bit more in depth into how to run the tests.

In chapter 16, we will see how to grab some information from the test run in order to generate our useful testing reports.

In chapter 17, we will briefly look over a few aspects, namely timeouts for tests, or nested tests, which means inner tests for our test classes, and also how to create our own composed annotations.

In chapter 18, we will see how we can migrate from JUnit 4, in case we are using that version of the library in our project.

Just before I start, a few things to mention.

This tutorial will use Java as a programming language and IntelliJ as the editor for the code, as you've probably already guessed because of my previous tutorial on IntelliJ.

If you haven't taken that tutorial yet, please do so.

There will be shortcuts used that are explained in that tutorial, so don't hesitate to take a look at my tutorial on IntelliJ.

Another thing I would like to mention here is that JUnit 5 is a library that heavily uses annotations, so in many chapters we will be introducing brand new annotations.

Also, some of the features in the current version of JUnit 5 are experimental, so if you have any issues when you are running these features, take a look whether there is a bug already raised for them.

If not, don't hesitate to raise the bug yourself because experimental features mean that in this version, or in a version, that feature is considered experimental and feedback is expected from the community.

Based on that feedback, the feature will either be promoted to stable or it will be improved or dropped all together.

Let's start this journey and see what JUnit 5 can do for us in terms of helping us with our testing.

