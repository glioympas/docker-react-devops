# Training

Experimenting/Testing/Trying some DevOps stuff for learning purposes. It a really interesting field that I try to develop some skils on it, on my free time.

Deploying a React app with Docker, Github, Travis CI & AWS Elastic Beanstalk.

How it works?

- A new feature is coming so a developer of the project opens a new  PR on Github

- Github communicates with Travis CI and execute the tests for that branch

- PR is accepted & merged to main

- Github communicates again with Travis CI, runs the tests & deploys to AWS

Very cool and realistic workflow, simple enough though. More complex things are coming.


Note: You see this failing because I deleted the Elastic Beanstalk instances from AWS since I do not want to get charged for no reason :P 
