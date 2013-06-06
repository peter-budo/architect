architect
=========

**THE Architect** to get your initial Android project structure up with speed of "light"

What I want to achieve
========================
1. At the moment project would have to be forked to get access to Architect build.gradle (maybe in future there will be way to say 'fetch from URL and execute' or maybe execute remote build.gradle)
2. Execute
````
gradle OPTION -Plocation=$HOME/GITHUB -Pname=PROJECT_NAME -Ppackage=COM.MYPACKAGE.NAME -Pversion=0.0.1-SNAPSHOT
````

3. This should execute build.gradle for given `OPTION` project or library
4. Create new directory in location `$HOME/GITHUB` with name `PROJECT_NAME`
5. Copy folder structure under given `OPTION` sample
6. Create package structure inside `src` directory and move initial java files there
7. Substitute temporary space holders in files, example package in AndroidManifest.xml
