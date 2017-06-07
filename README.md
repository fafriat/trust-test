| | |
|----------|---------------------------------------------------------------------|
| **TravisCI** 	| [![Build Status](https://travis-ci.org/fafriat/trust-test.svg?branch=master)](https://travis-ci.org/fafriat/trust-test)|
| **AppVeyor**  | [![Build Status](https://ci.appveyor.com/api/projects/status/3blmu96fr1v5jjbt/branch/master?svg=true)](https://ci.appveyor.com/project/fafriat/trust-test/branch/master)|


# How I build my rust project for 21 different targets in less than 15 minutes for linux, Mac and Windows...

Write once, Run Everywhere... with native build

I created a simple project using cargo:

cargo new trust-test --bin

I pushed the project to my github here : https://github.com/fafriat/trust-test

I used the files (ci folder + travis +AppVeyor) from the excellent project: https://github.com/japaric/trust
You just need to follow the trust project readme and need free account to Travis or AppVeyor, I used my github account to get an account in seconds.
Then I activated my project in AppVeyor and Travis.

Then as explained, I created a deploy key from github and encrypted it in AppVeyor and put it in the configuration files as explained.

When pushing to github the build is starting... (as I understood you can only catch a push of a Tag).


