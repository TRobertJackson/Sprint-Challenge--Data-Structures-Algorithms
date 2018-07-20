Add your answers to the Algorithms exercises here.

Ex 1)
  a) O(n^2) or O(n^3)?

  b) O(n)

  c) O(n)

  d) O(n^2)

  e) O(n^3)

  f) O(n)

  g) O(n)



Ex 2)

  a) def max_diff(num):
        x = num.index(max(num))
        y = num.index(min(num))
        z = (max([num[x] - min(num[:x]), max(num[y+1:]) - nu[y]]))
        return z

  b) Halve the height of the floor the egg is droppede from until a first instanc of unbrokn egg. Proceed in this way backwards between       original height and current until floor is found.

Ex 3)

  a) O(n), only objects greater than pivot are checked  (unsure)

  b) O(n), median is found up to elements/2
