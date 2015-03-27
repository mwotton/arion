# Arion [![build status](https://travis-ci.org/karun012/arion.png)](https://travis-ci.org/karun012/arion) [![Available on Hackage](http://img.shields.io/hackage/v/arion.svg)



<img src="http://s1.hubimg.com/u/7984120_f260.jpg"
 alt="Arion Image" title="arion" align="right" height="320px"/>

> Homer said in Iliad

> ...there is no man that shall catch thee by a burst of speed, neither pass thee by,
> nay, not though in pursuit he were driving goodly Arion,
> the swift horse of Adrastus, that was of heavenly stock...
> Homer


**Arion helps you make red-green-refactor quick and efficient when working with hspec tests**

**It watches the file systems for change in source or test code and selectively runs hspec tests**



# Usage

```cabal
cabal update
cabal arion
arion <folder-to-watch> <folder with source files> <folder with test files>
  or
arion --help
```

# Demo
<img src="images/arion-demo.gif"
 alt="Arion Demo" title="Arion Demo" align="left"/>
