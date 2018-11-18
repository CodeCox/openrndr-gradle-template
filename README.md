# OPENRNDR Gradle template

A bare-bones template for writing [OPENRNDR](http://openrndr.org) programs. Contains Gradle project files and a minimal program example.

It demonstrates the _OO_ and _FP_ coding _styles_ - choose one of the two source files depending on your approach.

## Intellij IDE

* Click the `run` widget next to `main()` in the left margin/gutter of the source file. 

## Gradle tasks

 * `run` runs the template program (with the correct JVM arguments)
 * `jar` creates an überjar that contains the program and all its dependencies

## Executable Jar
The _jar_ file contains both the _OO_ and _FP_ template examples. 
However, typically you would only have either one of these in your _project_ and _jar_ file. 

Command line instructions line for this example:

* For TemplateProgram.kt
```
java -jar myjar.jar
 
 OR
 
java -cp myjar.jar TemplateProgramKt
```

* For TemplateProgramFP.kt
```
java -cp myjar.jar TemplateProgramFPKt
```

## On MacOS
add `-XstartOnFirstThread` to JVM arguments (at Run/Edit Configurations/VM Options if you're using IntelliJ Idea)

