
# Jass Doc

The Jass Doc is an encyclopedia-like source for information about Jass natives.
The intended use is as a reference for understanding both the intended behavior
and the bugs present for wc3 natives and blizzard.j functions.

This goal of this project is not to document *every* function and native but
to add helpful comments for unclear functions, give notes about buggy functions
and inform about other misc information.

The jass natives are grouped into categories and split into files (e.g.
`unit.j` and `timer.j`). This project is structured like code so that it can be
compiled into one large document, but doing so is not necessary for making use
of this repository.

So far I have used `@param`, `@bug`, `@note`, `@pure`, `@async` and `@event` annotations.
Other possible annotations could be `@nosideeffect`.

Do note that the parser expects the annotations after the general description.

# Build

To build this project you need a somewhat recent GHC,
the haskell library megaparsec-7, gnu make and the sqlite3 cli binary.

