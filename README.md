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

Git pull request successfull test output:
```
All checks have passed
2 successful checks

Travis CI - Branch Successful in 15s — Build Passed

Travis CI - Pull Request Successful in 17s — Build Passed
```

Travis pull request successfull test output:
```
Worker information
6
0.14s
0.01s
0.00s
0.02s
system_info
7
Build system information
173
174
0.31s
2.28s
docker_mtu_and_registry_mirrors
resolvconf
git.checkout
175
0.42s
$ git clone --depth=50 https://github.com/georgitsvetkov/travis-test-repo.git georgitsvetkov/travis-test-repo
192
193
0.01s
$ bash -c 'echo $BASH_VERSION'
194
4.3.48(1)-release
195
196
0.00s
$ bash test_hello.sh
197
GOOD: test pass
198
The command "bash test_hello.sh" exited with 0.
199
0.00s
$ bash test_bye.sh
200
GOOD: test pass
201
The command "bash test_bye.sh" exited with 0.
202
203
204
Done. Your build exited with 0.
```

-  Merge pull request and delete branch
