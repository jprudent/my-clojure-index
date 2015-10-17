# My-clojure-index
A bunch of links gravitating around Clojure

## General documentation
- Clojure [cheat sheet](http://clojure.org/cheatsheet) presents the core documentation in a single well organized page.
- [Grimmoire](http://conj.io/) is like the cheat sheet but with tooltips and a nice search field.
- [clojure-doc.org](http://clojure-doc.org/) collects basic documentation on the language
- [Brave Clojure](http://www.braveclojure.com/) Online book with first class content !

## Community
- [clojure ml](https://groups.google.com/forum/#!forum/clojure) Clojure official mailing list 
- [clojure-fr ml](https://groups.google.com/forum/#!forum/clojure-fr) Pour la communauté française.
- There is also clojure related chatrooms on [slack](https://clojurians.slack.com). I suggest to join both #clojure and #clojurescript. I find it very instructive to read it !

## Workflow
- [vinyasa](https://github.com/zcaudate/vinyasa) is a lein library that leverage the repl to do crazy thing : inject on the fly new dependencies, control lein, hot reload of java classes (but you will loose the state), injection of ns in another, introspection, ...
- [Ultra](https://github.com/venantius/ultra) provide color to the lein repl AND a much more readable test output
- [lein-test-refresh](https://github.com/jakemcc/lein-test-refresh) fire the tests each time it is modified

## Macros
- [reader and macro basics](http://clojure-doc.org/articles/language/macros.html)

## Namespaces
- A [review](http://blog.8thlight.com/colin-jones/2010/12/05/clojure-libs-and-namespaces-require-use-import-and-ns.html) of `require`, `use`, etc. 

## [core.async](https://github.com/clojure/core.async)
- A detailed walkthrough [publish/subscribe](https://yobriefca.se/blog/2014/06/04/publish-and-subscribe-with-core-dot-asyncs-pub-and-sub/)

## [friend](https://github.com/cemerick/friend)
Friend is a library on top of ring that handles security aspects of webapps
- A [guide](http://adambard.com/blog/easy-auth-with-friend) to do custom authentification
- A [collection of examples](https://github.com/cemerick/friend-demo) that shows how to use _friend_

## Behaviour Driven Design
- A step by step [walkthrough](https://github.com/gphilipp/bdd-guide-clojure) Cucumber, Lein and Cursive.

## Libraries
- [Clojure Toolbox](http://www.clojure-toolbox.com/) is a great repository of well known libraries.

### Datastructure manipulation
- [Balagan](https://github.com/clojurewerkz/balagan) _Not tested yet_
- [Specter](https://github.com/nathanmarz/specter) _Not tested yet_
