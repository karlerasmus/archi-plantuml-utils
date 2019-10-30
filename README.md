# Archimate utilities for plantuml

## Installation

Include the library file at the top of your diagram

```
!include https://raw.githubusercontent.com/karlerasmus/archi-plantuml-utils/legend.iuml
```

## Basic Usage

Simple call function archiLegend to include a legend of the Archimate notation

```
archiLegend()
```

## Advanced Usage

It is possible to limit the perspectives shown in the legend.

Specify:
+ A: for the Application Layer
+ B: for the Business Layer
+ T: for the Technology Layer
+ M: for the Motivation Layer
+ S: for the Strategy Layer
+ Or combinations thereof

Example
For only the Business Layer

```
archiLegend("B")
```
