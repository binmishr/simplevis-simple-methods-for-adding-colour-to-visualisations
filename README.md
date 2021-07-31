# simplevis-simple-methods-for-adding-colour-to-visualisations


Overview

We discussed how simplevis provides simple families of functions for when the user is colouring or facetting by a variable or both or neither. If you haven’t read that post, please read that one before this one. In the current post, we will discus the simplified and consistent method for colouring that simplevis has adopted.

In simplevis, users adhere to the following rules for adjusting colour:

    Always define the colours to use via the pal argument (short for palette)
    If colouring by a variable, use a *_col() or *_col_facet() function, and define the col_var
    For gg_sf_col*() and gg_point_col*() functions where the col_var is numeric, also define the col_method of bin or quantile, and the col_cuts to use.

library(simplevis)
library(dplyr)
library(palmerpenguins)

The codeset and images are encapsulated in the .pdf file and attached in this repository to refer.

