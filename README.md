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
will grow by a factor of three.
The reigning champ algorithm will be invoked triple the number of times, so the time required to run the algorithm would triple as well.
In other words, the reigning champ algorithm is linear, so the time also increases by a factor of 3.

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by a factor of three. 
In a ArrayList of size n, the reigning champ algorithm is invoked n times.
If the number of elements is tripled, then the reigning champ algorithm is invoked 3n times,
so the number of times the algorithm is invoked will be tripled.


0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by a factor of nine.
If the number of elements is tripled, the reigning champ alogorithm is invoked triple the number of times it is invoked originially. However, the selection sort invokes the reigning champ algorithm n times every time it goes through the for loop, so when the number of elements is tripled, the constructor will invoke the algorithm 3n times every 3n times. As a result, the time required for the selection sort is increased by a factor of nine.
In other words, the selection sort is quadratic, so the time increases by a factor of three squared.
