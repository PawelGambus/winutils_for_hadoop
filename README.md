# winutils.exe for Hadoop and Spark

This repository contains winutils.exe which needs to be compiled manually on windows machines.

I compiled the file to fix the problem after installing Spark locally on a Windows machine. Executing ``./bin/run-example SparkPi``  led to the following warninng:

``WARN Shell: Did not find winutils.exe``

Some repositories provide compiled versions of winutils.exe, but neither provided the version I needed at the time of compilation:
<https://github.com/steveloughran/winutils>

<https://github.com/cdarlint/winutils>

To resolve the problem and compile the necessary files I used the following sources:
<https://cwiki.apache.org/confluence/display/HADOOP2/WindowsProblems>

<https://pivotalbi.com/build-your-own-winutils-for-spark/>
