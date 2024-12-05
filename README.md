# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

///
def of o: f(n)∈o(g(n)) <-> for all c > 0, ∃n0, for all n >= n0: f(n) < cg(n)

def of O: f(n)∈O(g(n)) <-> for all c > 0, ∃n0, for all n >= n0: f(n) < cg(n)-> ∃c > 0, ∃n0, for all n >= n0: f(n) < cg(n)

o requires any normal number to be true, and O requires at least one normal number to be true

The conditions of o satisfy the conditions of O. If f(n) belongs to o, it must also belong to O

so  f(n)∈o(g(n)) -> f(n)∈O(g(n))
