# Sensor Statistics Task 

A command line program that calculates statistics from humidity sensor data.

![Scala version](https://img.shields.io/badge/scala-2.13.3-brightgreen)
![Test passing](https://img.shields.io/badge/test-passing-brightgreen)

## About

The project demonstrates how to handle multiple data sources containing a huge amount of data.
The same functionality was implemented using vanilla scala and
[Akka Streams](https://doc.akka.io/docs/akka/current/stream/index.html).
For both cases it is shown how to deal with data sources sequentially and in parallel.

There is also a demonstration of a purely functional approach using 
[Cats Effect](https://typelevel.org/cats-effect/). 

[Scala Test](https://www.scalatest.org/) library was used for testing.
The tests are written in FlatSpec style.

## Author

<a href="https://www.linkedin.com/in/oleg-oleshchuk/" target="_blank">Oleg Oleshchuk</a>

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- [MIT license](http://opensource.org/licenses/mit-license.php)
- Copyright 2020 © <a href="https://www.linkedin.com/in/oleg-oleshchuk/" target="_blank">Oleg Oleshchuk</a>.