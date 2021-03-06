You can generate this README like so:

```
$ modoc compile --source ./examples/readme --output ./README.md
```

Compiling the [basic example](./examples/basic) will produce the following:

```
$ modoc compile --source ./examples/basic --output ./examples/BASIC.md
$ cat ./examples/BASIC.md
# A Modoc Tale

This is the introduction to the document, found below the title and before the Table of Contents.

## Table of Contents

- [Introduction](#introduction)
   - [Subsection A](#subsection-a)
   - [Subsection B](#subsection-b)
   - [Subsection C](#subsection-c)
- [Chapter One](#chapter-one)
   - [Subsection A](#subsection-a)
   - [Subsection B](#subsection-b)
   - [Subsection C](#subsection-c)
- [Chapter Two](#chapter-two)
   - [Subsection A](#subsection-a)
   - [Subsection B](#subsection-b)
   - [Subsection C](#subsection-c)

## Introduction

This is the contents of the Introduction chapter.

### Subsection A

This is Introduction, Subsection A.

### Subsection B

This is Introduction, Subsection B.

### Subsection C

This is Introduction, Subsection C.

## Chapter One

This is the contents of Chapter One.

### Subsection A

This is Chapter 1, Subsection A.

### Subsection B

This is Chapter 1, Subsection B.

### Subsection C

This is Chapter 1, Subsection C.

## Chapter Two

This is the contents of Chapter Two.

### Subsection A

This is Chapter 2, Subsection A.

### Subsection B

This is Chapter 2, Subsection B.

### Subsection C

This is Chapter 2, Subsection C.
```