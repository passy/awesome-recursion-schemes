# Awesome Recursion Schemes [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curation of useful resources for learning about and using recursion schemes.

Recursion schemes are simple, composable combinators, that automate the process of traversing and recursing through nested data structures.


## Contents

- [Introductions](#introductions)
- [Articles](#articles)
- [Papers](#papers)
- [Presentations](#presentations)
- [Cheat Sheets](#cheat-sheets)
- [Podcasts](#podcasts)
- [Implementations](#implementations)


## Introductions

- [Awesome Recursion Schemes](https://github.com/passy/awesome-recursion-schemes) - A curation of useful resources for learning about and using recursion schemes.
- [Practical Recursion Schemes](https://jtobin.io/practical-recursion-schemes) -
  Introduction to pattern functors, fix points, anamorphisms, catamorphisms,
  paramorphisms and hylomorphisms, requiring very little prior knowledge.
- [An Introduction to Recursion Schemes](http://blog.sumtypeofway.com/an-introduction-to-recursion-schemes/) -
  Three-part series in which you discover recursion schemes from scratch and
  implement a small subset of Edward Kmett's library.
- [Understanding Algebras](https://www.schoolofhaskell.com/user/bartosz/understanding-algebras) -
  Bartosz Milewski explains F-algebras and shows how to use them in the context of
  catamorphisms.
- [Recursion Schemes in JavaScript and Flow](https://medium.com/@JosephJnk/recursion-schemes-in-javascript-and-flow-with-static-land-recursision-schemes-97cf10599fb7) -
  Series introducing recursion schemes and related concepts in JavaScript,
  aimed at developers with a minimal functional programming background.

## Articles

- [Recursion Schemes: A Field Guide (Redux)](http://comonad.com/reader/2009/recursion-schemes/) -
  List of various recursion schemes with code samples.
- [Catamorphisms](https://wiki.haskell.org/Catamorphisms) - Definition on the Haskell Wiki.
- [Catamorphisms](https://www.schoolofhaskell.com/user/edwardk/recursion-schemes/catamorphisms) -
  Short definition with code on School of Haskell by Edward Kmett.
- [Rotating Squares](https://jtobin.io/rotating-squares) - Using a hylomorphism to rotate a quadtree by Jared Tobin.
- [Recursion Schemes, Part V: Hello, Hylomorphisms](http://blog.sumtypeofway.com/recursion-schemes-part-v/)
- [Promorphisms, Pre and Post](https://jtobin.io/promorphisms-pre-post) - Pratical examples of pre- and postpromorphisms by Jared Tobin.
- [Time Traveling Recursion Schemes](https://jtobin.io/time-traveling-recursion) - Exploring histo and futu by example by Jared Tobin.
- [Recursion Schemes, Part IV: Time is of the Essence](http://blog.sumtypeofway.com/recursion-schemes-part-iv-time-is-of-the-essence/) - Practical article about histomorphism and the futumorphism.
- [Cheat Sheet](https://github.com/sellout/recursion-scheme-talk/blob/master/cheat%20sheet.pdf) - Map of various recursion schemes and their duals.
- [Correcting the Visitor pattern](http://logji.blogspot.co.uk/2012/02/correcting-visitor-pattern.html) - Showing that the Visitor pattern implements an f-algebra for use with a catamorphism (in Java).
- [Recursion Schemes in Scala](https://free.cofree.io/2017/11/13/recursion/) - Introduces the fixpoint combinator, anamorphism, catamorphism, hylomorphism, paramorphism, apomorphism, histomorphism, dynamorphism and futumorphism.

### Hylomorphisms in the Wild

Articles by Bartosz Milewski about solving small, practical problems by applying a hylomorphism.

- [Stalking a Hylomorphism in the Wild](https://bartoszmilewski.com/2017/12/29/stalking-a-hylomorphism-in-the-wild/) - Advent of Code 2017, Domino challenge
- [Open Seasons on Hylomorphisms](https://bartoszmilewski.com/2018/12/20/open-season-on-hylomorphisms/) - Advent of Code 2018, String comparison challenge

## Papers

- [Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire, 1991, Meijer et al.](http://maartenfokkinga.github.io/utwente/mmf91m.pdf) -
  The original paper most of this is based on.
- [A Duality of Sorts, 2013, Hinze et al.](http://www.cs.ox.ac.uk/ralf.hinze/publications/Sorting.pdf) -
  Shows that many basic sorting algorithms exist as a pair, and that these pairs
  arise naturally out of the duality between folds and unfolds.
- [Sorting with Bialgebras and Distributive Laws, 2012, Hinze et al.](http://www.cs.ox.ac.uk/people/daniel.james/sorting/sorting.pdf) -
  Shows how paramorphisms and apomorphisms can be used for more efficient
  implementations of sorting algorithms.
- [Scrap your boilerplate: a practical design pattern for generic programming, 2003, SPJ et al.](http://research.microsoft.com/en-us/um/people/simonpj/Papers/hmap/hmap.ps) -
  Design pattern for writing programs that traverse data structures built from rich mutually-recursive data types.

## Presentations

- [Slidedecks by Tim Philip Williams](http://www.timphilipwilliams.com/slides.html) -
  "Recursion Schemes by Example" and "Exotic Tools for Exotic Trades" provide
  concise definitions as well as practical examples of many recursion schemes.
- [Unifying Structured Recursion Schemes](https://www.youtube.com/watch?v=9EGYSb9vov8) -
  12 min presentation by Ralf Hinze, Nicolas Wu, and Jeremy Gibbons.
- [Recursion Schemes](https://www.youtube.com/watch?v=Zw9KeP3OzpU) -
  Presented by Tim Williams at the London Haskell meetup.
- [F-algebras or: How I Learned to Stop Worrying and Love the Type System](https://www.youtube.com/watch?v=PK4SOaAGVfg) -
  Presented by Anthony Burzillo at the NYC Haskell User's Group.
- [A Gentle Introduction to Recursion Schemes](https://www.youtube.com/watch?v=i5A2Amfcir8) -
  Presented by Jean Remi Desjardins at Lambdaconf 2016.
- [recursion-scheme-talk](https://github.com/sellout/recursion-scheme-talk) - Collection of slide decks about recursion schemes.
- [Bracer: Transforming Real-World Languages with Coproducts and Recursion Schemes](https://www.youtube.com/watch?v=5Kr7IykGMzU) - High-level talk about structuring programs with coproducts and recursion schemes by Patrick Thomson.
- [Recursion: Where Functional Programming Hits Bottom](https://www.youtube.com/watch?v=24UoRaoKLjM) - Introduction to recursive fix point data structures and recursion schemes in Haskell and Scala by Greg Pfeil.
- [Programming with algebras](https://www.youtube.com/watch?v=-98fR9VmLbQ) - Bartosz Milewski's article in talk form, presented at LambdaCon.
- [Peeling the Banana: Recursion Schemes from First Principles](https://www.youtube.com/watch?v=XZ9nPZbaYfE&t=3s) - Zainab Ali's Introductory talk presented at LambdaWorld.

## Cheat Sheets

- [The Hitchhiker's Guide to Morphisms](https://ipfs.io/ipfs/QmTppu1VDAQWsdiyVSZX6qb8PErdpwzNP2oKfEhcgaBvWR/guide-to-morphisms.pdf) - Overview of different morphisms including a printable PDF.

## Podcasts

- [Magic Read Along](http://www.magicreadalong.com/) - Casual discussions about
  category theory that often bring up recursion schemes, including [episode
  33](http://www.magicreadalong.com/episode/33) which talks about Histomorphisms
  and Futumorphisms.
- [Scala Love](https://scala.love/) - Podcast about Scala that brings up
  recursion schemes in [the second episode](https://scala.love/happy-valentin/).
- [The Haskell Cast](https://www.haskellcast.com/) - Recursion schemes come up in
  [Episode 13 with John Wiegley](https://www.haskellcast.com/episode/013-john-wiegley-on-categories-and-compilers).

## Implementations

- [recursion-schemes](https://github.com/ekmett/recursion-schemes/) for
  Haskell - The canonical implementation by Edward Kmett.
- [Matryoshka](https://github.com/slamdata/matryoshka) for Scala using Scalaz -
  Generalized folds, unfolds, and traversals for fixed point data structures.
- [andyscott/droste](https://github.com/andyscott/droste) for Scala using Cats -
  Generalized folds, unfolds, and traversals for fixed point data structures.
- [recursion\_schemes](https://github.com/vmchale/recursion_schemes/) for
  Idris, based off Edward Kmett's Haskell library.
- [purescript-matryoshka](https://github.com/slamdata/purescript-matryoshka) for PureScript -
  Work-in-process port of matryoshka.
- [recursion](https://github.com/vmchale/recursion) for ATS - Demonstration of
  recursion schemes in ATS.
- [dada](https://github.com/sellout/dada) for Dhall - a library for recursion
  schemes in Dhall.
- [static-land-recursion-schemes](https://github.com/JosephJNK/static-land-recursion-schemes) for JavaScript/Flow -
  Schemes for data structures written in the style of [flow-static-land](https://github.com/gcanti/flow-static-land).
- [Katalyst](https://github.com/aedans/Katalyst) for Kotlin - a re-envisioning based off Matryoshka using lightweight higher kinded polymorphism.
- [Groupoid Infinity](http://groupoid.space/mltt/inductive/) [recursion schemes](https://github.com/groupoid/infinity/blob/master/priv/recursion.ctt) for [cubicaltt](https://github.com/mortberg/cubicaltt) - a cubical version of recursion schemes.

## License

This content is licensed
under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
