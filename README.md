# Harbr QA Challenge #

The goal of this challenge is to assess that, given a pre-developed application composed by a front-end UI and back-end API, you:
- can create a test environment using the relevant tools, such as Git, npm and node.js;
- are a detail-oriented Test Engineer that can go through feature specifications, and manually check if the app is acting accordingly;
- can automate API level tests using a programming language and/or test framework or library, such as Mocha, Cypress, RestAssured, etc.; and
- can automate UI level tests using a programming language and/or test framework or library, such as TestCafe, Cypress, Selenium, Puppeteer, PlayWright, etc.

Read the application's requirements from the **Requirements.md** file on the root of the git repository.

## Considerations ##
- The task outputs will have to be published in a public git repository. You are free to use any resources you want to research.
- The task is intended to take no longer than 2-3 hours. Do not spend more than this time.
- The automation tasks (2 and 3) are aimed at showcasing your programming and test automation skills. You are free to use any programming language you want, but as we want to make sure you'll be able to use or learn (fast) the tech stacks we use. At Harbr we use JS for our Frontends and Python for our Backend, so using either of them is an extra.
- If you need to take any assumptions please note them as part of your answers.
- Feel free to edit the code of the Customer App web application, if it was to improve your tests.

## Task 1: Test Environment Setup ##

Estimated time: 20 minutes

It is very important for a Test Engineer to be able to create a test environment following the instructions written by the developers. Therefore, you'll have to take the following steps:

1) Clone the repository;
2) Follow the **TestEnvironment.md** instructions to build and start the Customer App web application that you will be responsible to test;
3) After the app is running, fill the name field in the first screen, hit Submit and take a screenshot of the page showing your name and the current date; and 
4) Create a new public git repository, and commit and push the screenshot to its root.

## Task 2: Create an automated API level test scenario ##

Estimated time: 1 hour

Unfortunately, software applications are not perfect neither are the engineers that build them, so as you could see some of the API specs were not followed. To avoid having to manually run all the tests again after each new app version is to be released a good strategy is to create automated tests that could be run quickly and with little effort.

Please complete the following:
1) Build a script/program (using any language/framework/library you want) that runs an API test;
2) Create a Readme file telling us what your test case is, the expected outcome, and how to run it; and
3) Commit and push everything to a folder called **api-test** on the public repository you've created on **Task 1**.

## Task 3: Create an automated UI level test scenario ##

Estimated time: 1 hour

Not only do backend engineers make mistakes, but the frontend layer is also responsible for checking business rules and presenting the correct information to the user. Therefore we also need to have ways to automatically check it.

Please complete the following:
1) Build a script/program (using any language/framework/library that you want) that runs an automated UI test;
2) Create a Readme file telling us what your test case is, the expected outcome, and how to run it; and
3) Commit and push those to a folder called **ui-test** on the public repository you created on **Task 1**.

### Once complete, you can choose to share your repo with us as you prefer, send us your public repo URL, keep your repo private and share with us using gitfront.io or zip up your files and use a file transfer service such as wetransfer.com ###
