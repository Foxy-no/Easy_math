# Domain

## Definition

The domain of a function (usually written as an interval) represents all possible values for $x$ that return a real value for $f(x)$.

## Basically

If for some specific values of $x$ the function does not exist in $\mathbb{R}$, the domain is not all $\mathbb{R}$ but it's $\mathbb{R} -$ {all those values of $x$}.

<details>
  <summary>What do you mean by "the function does not exist"?</summary>

  You probably already know that you cannot calculate $\sqrt{-1}$ or of any negative number.
  And you know that you cannot devide by $0$. Domain is about this stuff.
  
  If, for example, $f(x) = \frac{1}{x}$.
  
  $f(1) = \frac{1}{1}$ -> $f(1) = 1$
  
  $f(0) = \frac{1}{0}$ -> IMPOSSIBLE
   - When $x = 1$ the function exists and returns a real number ($1$).
   - When $x = 0$ the function doesn't exist in $\mathbb{R}$.
  
</details>

## Practically

Relevant cases:
1. $g(x)$ as a divisor

   Domain: $g(x) ≠ 0$

   ---
   **NOT IN THE RIGHT PLACE (IT'S REFFERED TO F(X)=1/X NOT TO F(X)=1/g(x). NOW I'M GOING TO BED, CONSIDER THIS AS SOME KIND OF CHECKPOINT**
   Domain: $]-infinito;0[U]0;+infinito[
   
   (Some people use multiple parenthesys to write intervals, I prefer this way because I find it more clear and understandable.
   I will write them this way, but you can keep doing as you are used to, obviously)

   **ALL THIS PART TILL HERE IS IN THE WRONG PLACE. IT SHOULD BE ONLY REFEREED TO SONETHING/X. NOT TO SOMETHING/G(X), I GUESS YOU GOT IT.
END OF CHECKPOINT.**

   ---
   
2. $\sqrt[n]{g(x)}$ with $n \in \mathbb{N}$ and $n$ even

   Domain must include: $g(x) > 0$

<details>
  <summary>Tell me more about it"?</summary>

  If the function $f(x)$ contains $\sqrt{x}$ or $\sqrt{x - 1}$ or squareroot of anything that contain $x$ (we can call it $g(x)$), we have to consider that the function does not exist for any value of $x$ that makes the argument of the squareroot ($g(x)$) negative.
  And in the domain we will have to write for which real values of $x$ the function does exist.
  
  In the $\sqrt{x}$ example, the function doesn't exist for any negative value of $x$. So for any $x > 0$ the function exists
  In the $\sqrt{x - 1}$ example, the function does not exist whenever $x - 1 < 0$. So the function does exist when $x - 1 > 0$ This is a simple disequation you have to solve to find the domain (or part of it). The solution is simply: the function can exist for any $x > 1$
  And the process is always the same. If you have a squareroot of something that contains $x$, let's call it $g(x)$, you just have to say in the domain that the function exists only when $g(x) > 0$

  Obviously, this rule is true not only with $\sqrt[2]{g(x)}$, but also with $\sqrt[4]{g(x)}$ ; $\sqrt[6]{g(x)}$ and basically any root with an even number at apix.
  
</details>

3. $log_n(g(x))$ with $n \in \mathbb{R}$ and $n$ positive
