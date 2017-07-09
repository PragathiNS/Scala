# Scala
Coursera Course learning and assignments

System Requirements: 
1. JDK
2. SBT
3. Scala IDE, ItelliJ IDEA

Linux
Install SBT - Scala Build Tool

Windows


To start scala REPL in the sbt console, type:
1. In Command Prompt, 
  > sbt
  > console //To start scala


General Object hierarchy:
- scala.Any base type of all types. Has methods hashCode and toString that can be overridden

- scala.AnyVal base type of all primitive types. (scala.Double, scala.Float, etc.)

- scala.AnyRef base type of all reference types. (alias of java.lang.Object, supertype of java.lang.String, scala.List, any user-defined class)

- scala.Null is a subtype of any scala.AnyRef (null is the only instance of type Null), and scala.Nothing is a subtype of any other type without any instance.

In Scala, the main or entry point method is defined in an object. An object can be made executable by either adding extending the type App or by adding a method def main(args: Array[String]).
  > object HelloWorld extends App {
      println("Hello, World!")
    }

OR
  > object HelloWorld {
      def main(args: Array[String]) {
        println("Hello, World!")
      }
    }
