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
def of o, |f(n)|<= o|g(n)|means for all postive constant ε>= 0, there will have a natural number N |f(n)|<= ε|g(n)|, for all n >= a natural number N

def of O, f(n) belong O(g(n)),If there exists a positive constant c>0 and a natural number n0，|f(n)|<= c|g(n)|

pick a costant c that c >= 0, c = 1, when there is a N, for all n >= N

|f(n)|<= 1|g(n)| = |g(n)|

c and n0 satisfy the definition of O，|f(n)|<= c|g(n)|，so |f(n)| ∈ c|g(n)|

By using the o definition and choosing a specific ε/c, the conditions required by the O definition can be met.
