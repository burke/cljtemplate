Getting Started:

1) Edit build.xml and set your project name and first source file. 
   When you add more packages later, you can just add extra <arg/>s

2) In /libs, there are symlinks to clojure.jar and clojure-contrib.jar.
   These probably aren't valid on your system, so throw your own copies in.

2) Write code! It should go into src/clj/com/example/demo.clj,
   adjusted for your own package name. Make sure that if you want the jar
   to be executable, at least the main namespace does (:gen-class).

3) Run "ant" to compile your source and build a jarfile.
