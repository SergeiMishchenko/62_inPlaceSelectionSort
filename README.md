# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by a factor of three. This is because the 
amount of cycles of the reigning champ algorithm is
the size of the list.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked will grow by a factor of three. This is because the amount
of times the champ method is invoked is the size of the list.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by a factor of nine. The total time will increase product by the incrase
in time it takes to run the reigning champ algorithm times
the total ammount of times the reiginig champ algorithm is invoked, which
is nine.
[Justify, in about 2 sentences.]
