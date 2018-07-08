# Scalaz library Giter8 template

This Giter8 template is intended to make Scalaz libraries authors' life easier. You may use this template to create new projects under the Scalaz 8 umbrella.

You may create a new project using this template by issuing the following command: 

```
sbt new scalaz/scalaz-library.g8
```

It will ask for a few parameters, namely the name of your project and a short description, and will produce a new sbt project with all the common stuff (code style, documentation, publication settings) configured to the Scalaz standards, so that you can focus on delivering awesome FP software. 

Under the hood, it will mainly enable the [scalaz-sbt](https://github.com/scalaz/scalaz-sbt) plugin for you, and add the necessary directory structure.

Happy hacking!
