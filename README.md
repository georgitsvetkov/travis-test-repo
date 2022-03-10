# travis-test-repo
This is a repo for travis test (pass). In this repo I'm going to build a simple scrips and use travis.yml to test if the script is completing successfully and getting the expected outcome.

- Create a script hello.sh and bye.sh, which prints hello and bye

`
hello.sh and bye.sh scripts can be found attached to this repo
`

- Create a script test_hello.sh and test_bye.sh that checks/tests, if the correct output is being printed from the initial hello.sh and bye.sh scripts, using travis.yml

`
test_hello.sh and test_bye.sh scripts can be found attached to this repo
`

- Create a .travis.yml file that will run against those scripts and apply the test at https://app.travis-ci.com/github/georgitsvetkov

`
.travis.yml can be found attached to this repo
`

- Create an account at https://app.travis-ci.com and link your GiT account with your Travis account. Instructions can be found on internet and/or app.travis-ci.com 

- Clone/download [git repo](https://github.com/georgitsvetkov/travis-test-repo/) containing all the files needed (hello.sh, test_hello.sh and .travis.yml) 

- Create new branch and ensure that the files above are present 

- Create pull request. Once pull request is being created, prior merging the pull request, you should see test running in GitHub and [Travis](https://app.travis-ci.com/github/georgitsvetkov/travis-test-repo) showing the results of the test, based on the test_hello.sh script. Upon successfull test, you should get positive results

-  Merge pull request and delete branch
