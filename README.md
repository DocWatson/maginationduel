Play Magi-Nation: Duel in the browser.  Forked from Jinteki.net's codebase and modified to fit.

## Live server

None yet.

## Development status

## Dependencies

* Node.js, Node Package Manager
* Leiningen (version 2+)
* MongoDB
* Coffeescript
* Bower

## Installation

Install Node.js dependencies:

```
$ npm install
```

Install JavaScript dependencies:

```
$ bower install
```

Launch MongoDB and fetch card data:

```
$ mongod
$ cd data
$ coffee fetch.coffee
```

Compile and watch client side Clojurescript files:

```
$ lein cljsbuild auto dev
```

Compile server side Clojure files:

```
$ lein uberjar
```

Launch game server:

```
$ java -jar target/netrunner-0.1.0-SNAPSHOT-standalone.jar
```

Launch the Node server:

```
$ coffee server.coffee
```
