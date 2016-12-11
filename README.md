# ScalaxHack 2016

Topic and project suggestions for ScalaxHack 2016.

[![Gitter](https://badges.gitter.im/underscoreio/scalaxhack-2016.svg)](https://gitter.im/underscoreio/scalaxhack-2016?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

We'll arrange a schedule on the day based on what peoples' interests.
We'll aim to have a mix of hacking and short talks/workshops.
This is a collection of ideas and proposals.

## Projects to hack on

Have a project you'd like to bring to the hack day? 
Send us a PR to list it here! Here's an example:

### Example Person, Example Library

  http://github.com/example-person/example-library

  Include a quick description of the library 
  and what you'd like to work on at the hack day.
  Please keep descriptions short.
  Feel free to link to extra information.
  We suggest including a link to your issue tracker
  and highlighting simple issues for newcomers.

### Miles Sabin, Typelevel Scala Compiler

  http://github.com/typelevel/scala

  Compiler hacking is fun and not as scary as you might think.
  In this session we'll fork, clone, build, tweak, 
  and use the Typelevel Scala compiler 
  as an introduction to compiler hacking.

### Julien Truffaut, Monocle

  http://julien-truffaut.github.io/Monocle  
  
  Monocle is a lenses and optics library for Scala.

### Sam Halliday, Rory Graves, Dick Wall, ENSIME

  http://ensime.org is a libre software project bringing Scala and Java IDE-like features to your favourite text editor.
   
  Do you use ENSIME and want to improve it, or need a feature before you can move from IntelliJ? Please come along! 
   
  The [Contributing Guide](http://ensime.org/contributing) is a good place to start if you're a newcomer.
 
### Shimi Bandiel, Comonads Notation for Dotty

  I've partially prototyped a co-monads comprehension (cofor) in Dotty. 
  
  Come and help discuss, design and implement a convenient and helpful syntax for co-monads.
  
  (Based on the work of Dominic Orchard https://github.com/dorchard/codo-notation in Haskell).
  
### Julien Richard-Foy, scalajs-bundler

  https://github.com/scalacenter/scalajs-bundler/issues?q=is%3Aopen+is%3Aissue+label%3Ahackathon

  scalajs-bundler is an sbt plugin that fetches the JavaScript dependencies
  of your Scala.js project from the NPM registry and bundles them with your
  application into a single artifact executable by a Web browser.

  The above link highlights the issues that are approachable for newcomers.
  
### Guillaume Massé, Scala-Native
  
  [scala-native](https://github.com/scala-native/scala-native/issues?q=is%3Aopen+is%3Aissue+label%3Acomponent%3Ajavalib) is a new backend for the Scala compiler. It uses the LLVM compiler infrastructure to get your favorite language closer to bare metal. Similarly to Scala.js, your artifact and its dependencies have to be ported to Scala. To cross compile to Scala.js, Scala-Native and JVM we created [sbt-cross](https://github.com/scala-native/sbt-cross). We need your help to reimplement the JDK in Scala(-Native) and cross-compile core libraries.

### Robin Green, Project Seraphim

  [Project Seraphim](https://github.com/greenrd/project-seraphim/issues) is
  a new project written in Scala whose aim is to make it easier for
  all programmers (not just Scala programmers) to find out about pull
  requests that may be of interest to them. One technique it will use
  for doing this is checking whether a PR modifies lines that you last
  modified, but we plan to offer many other options. The project has
  only just started, so if you want to get in "at the ground floor" of
  an interesting and useful new open source Scala project, join us!

### Erik Osheim, Cats

  [cats](https://github.com/typelevel/cats/issues?q=is%3Aopen+is%3Aissue+label%3A%22low-hanging+fruit%22)
  is a library that provides abstractions for functional programming in Scala.

### Daniela Sfregola, Twitter4s

  [twitter4s](https://github.com/DanielaSfregola/twitter4s)
  is an asynchronous non-blocking Scala client for both the Twitter Rest and Streaming API.

### ADD YOUR PROJECTS HERE

## Proposals for talks/workshops/round-tables

Ideas for talks, round-tables, workshops, and interactive sessions.
Anywhere from 10 to 60 minutes in length.
Sessions will be voted on unconference-style,
so some suggestions may not be taken up on the day.

### Example Person, Example Workshop, about 30 minutes

  http://example.com/link-to-external-material-if-applicable

  A short description of the session format
  (talk, hands-on workshop, round-table, etc)
  and the topic of discussion.
  Please keep descriptions short.
  Feel free to link to extra information.
  Let people know if they need laptops and
  provide pointers to setup instructions if required.
 
### Dave Gurnell, Beginner's Shapeless Workshop, 60 minutes

  An easy introduction to shapeless, 
  working on a few of the examples from the
  [Shapelss Guide](http://github.com/underscoreio/shapeless-guide).
  Bring a laptop with Scala on it and 
  clone [this repo](http://github.com/underscoreio/shapeless-guide-code) to get set up.

### Renato Cavalcanti, Beginner's Fun.CQRS Workshop, 60 minutes
 
  In this workshop you get your hands dirty with [Fun.CQRS](https://github.com/strongtyped/fun-cqrs). 
  
  You will learn the basic principles of CQRS / ES and how to model a domain in terms of Commands and Events. We will explore some strategies that can be applied when designing aggregates (write-models) and views (read-models).
  
  Workshop material can be found [here](https://github.com/strongtyped/fun-cqrs-order-demo).

### Richard Dallaway, Beginner's Slick Workshop, 60 minutes

  An introduction to Slick using part of the content from last year's
  [Slick workshop](https://vimeo.com/148074461).
  Bring a laptop with Scala on it and 
  clone [this repo](http://github.com/underscoreio/essential-slick-code) to get set up.

### Daniela Sfregola, Cats Workshop, 60 minutes

  An overview of the most useful Data Types of Cats, with practical examples on how they can make your life easier and your code cleaner. Workshop material is [here](https://github.com/DanielaSfregola/cats-scalax-hack).

### ADD YOUR PROPOSALS HERE
