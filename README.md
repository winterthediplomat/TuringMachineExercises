This repository contains solutions to several exercises proposed at the competition
of Turing Machines, hosted in Pisa by the local university.

A lot of solutions are not commented or not understandable or not efficient, but they're only one of the possible solutions: you can open a issue to ask about algorithm or reason about an implementative detail, or even to note me some bugs! Meanwhile, I'll comment them.
If you don't like a solution, fork this project to build your own algorithm and let me know!

# Repository structure

The repository has the following structure:

## algorithms

It contains a list of algorithms that can be used in every problem you need them.
They are designed to be understandable, easily customizable and quite fast (wrt tape length and others parameters).
If you have a better idea, or found something better in the literature, let me know!

## solutions

It contains a list of folders, that are referred to editions of the competition.
The folder matchXX has some solutions, exYY, that solves the problem YY proposed in the XX edition of the competition.
You can see text of the exercises (in Italian, I'll write the translation into the solution file) at [the Testi Gara / Competition Questions archive page (webarchive link)](https://web.archive.org/web/20120630214432/http://mdt.di.unipi.it:80/TestiGara/IndiceTesti.aspx) and go to XXth item.

# How can I try the scripts?

Solutions are designed to run into the Turing Machine Simulator developed by Information Tecnology Department at Pisa University. You can try a reimplementation at https://www.turingsimulator.net/

# Syntax

This simulator uses the following syntax:
```
(actual_state, read_char, next_state, written_char, direction)
```

You can know more (in Italian) at [MiniCorso / Crash Course (webarchive link)](https://web.archive.org/web/20120630214341/http://mdt.di.unipi.it:80/Documentazione/MiniCorso.aspx) and [Estensioni 2006 al simulatore / 2006 Simulator Extensions (webarchive)](https://web.archive.org/web/20120630214326/http://mdt.di.unipi.it:80/Documentazione/Estensioni2006.aspx)
