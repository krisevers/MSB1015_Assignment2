# MSB1015 Assignment 2 : Predicting boiling point based on chemical descriptors using PLS regression
This project is linked to Assignment 2 of the course MSB1015 Scientific Programming at the Maastricht University. The goal of this assignment and thus of this project is to write a working R markdown file with which a user is able to perform PLS regression on chemical information about alkane molecules to predict their boiling points.

## Introduction
Information about the boiling point of alkane molecules is requested by running a SPARQL query on the Wikidata database. Alkanes are molecules with only single bonds. It is straightforward to see a relationship between the number of carbon atoms a molecule has and the boiling point. The determination is more complicated than that though. Molecules with the same number of atoms can have different structures. A branched alkane has a different boiling point than a unbranched alkane with the same number of carbon atoms. In this assignment the Partial Least Squares method is used to determine what the best predictor(s) is/are for the measure of boiling point.

## Installation

## Running the code
To run the code the user should be aware of the dependencies and the requirements for reproducibility. The following points are repeated within the code file to make sure the user is aware of the them:

Dependencies:
- Make sure that all required packages are installed correctly before running through the dependent sections.
- Make sure a version of Java is installed that is compatible with the rJava package.

Reproducibility:
- Make sure that 134 rows of molecules are returned from the query request.
- Make sure the random seed is set to 5.

If the user is aware of these points the code can be savely executed section by section. If the user runs into problems she/he can contact the first author of this project.

## Authors
Kris Evers

Supervision: Egon Willighagen

## References
[1] Nilakantan, R. and Nunn, D.S. and Greenblatt, L. and Walker, G. and Haraki, K. and Mobilio, D., A family of ring system-based structural fragments for use in structure-activity studies: database mining and recursive partitioning., Journal of chemical information and modeling, 2006, 46:1069-1077

[2] Wiener, Harry, Structural Determination of Paraffin Boiling Points, Journal of the American Chemical Society, 1947

[3] MSB1015 Scientific Programming, coordinator: Egon Willighagen (https://www.maastrichtuniversity.nl/meta/369448/scientific-programming)
