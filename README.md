# ABTOF - A Behavioral Theory of the Firm in JavaScript

In 1963, Richard M. Cyert and James G. March from the Carnegie Institute of Technology (now Carnegie Mellon
University) published a book, in which they describe their behavioral theory of the firm.
The exact citation is:

> Cyert, Richard M. and March, James G., A Behavioral Theory of the Firm, Englewood Cliffs, NJ,
> Prentice-Hall, 1963.

Therein, Cyert and March describe their theory of decision making in business organizations. They combine
microeconomic theory with a study of the internal processes of a company concerning the formation of goals,
expectations, and the implementation of choices. The behavioral theory of the firm made a great impact and
has become important for much more recent research in organization theory and management (see
[ABTOF](https://en.wikipedia.org/wiki/A_Behavioral_Theory_of_the_Firm")).

The book luckily also contains a complete listing of a computer program written in the very old programming
language 20-GATE (Generalized Algebraic Translator, Extended) for the
[Bendix G-20](https://en.wikipedia.org/wiki/Bendix_G-20) mainframe, as well as a sample printout of a
program run. According to the source code, the program is from June 23, 1962. It implements the theoretical
concepts and performs a simulation of two firms in a duopoly model over 50 time periods.

This is the attempt of a "perfect" translation of the original 20-GATE program to JavaScript. The 20-GATE
code was hand-translated statement by statement to a semantically equivalent JavaScript program. Special
care was taken to have as much as possible a 1:1 relationship between the original
and the translated code and to exactly reproduce the original control flow (with quite some GOTO
statements).

The original program took a set of punched cards as its input data and produced a long printout of data for
50 time periods. The JavaScript version also generates this printout, but I added also a simple line graph
feature to view the development of a selected variable and the possibility to generate and download a "csv"
file of all the output data, so that you can analyze it in a spreadsheet, statistics package, or in your own
self-written programs.

Try out the simulation in your browser here: [Simulation of A Behavioral Theory of the Firm](http://members.aon.at/nkehrer/abtof/ABTOF.html)

Read more about it at [Norbert's Emulators](http://members.aon.at/nkehrer).

Have fun!

Norbert