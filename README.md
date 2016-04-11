ml_c4.5
----

A Dockerfile setting up executables for both C4.5 and C5.0 Machine Learning algorithms (by [John Ross Quinlan][1]) for hands-on experience.

Upon build, source code is downloaded from [RuleQuest Research][2], then a patch is applied to the no more maintained C4.5 code (to have at least no fatal errors on compile).
Please refer to [RuleQuest Research][2] for C4.5 and C5.0 use restriction and code licensing.


Run the container
-----------------
The container is meant for interactive use:

     docker run -it mbariani/ml_c4.5


[1]: https://en.wikipedia.org/wiki/Ross_Quinlan
[2]: http://www.rulequest.com

