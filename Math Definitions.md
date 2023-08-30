# Commutativity
 x and y commute under $*$ if $x*y=y*x$  
 (anti-commutativity is when $x*y=-y*x$)
 ## Operators:
 * Addition $+$
 * Multiplication $*$
 * And $\land$
 * Or $\lor$
 * Biconditional $\iff$
# Associativity
$*$ is associative if $x*(y*z)=(x*y)*z=x*y*z$
 ## Operators:
 * Addition $+$
 * Multiplication $*$
 * And $\land$
 * Or $\lor$
 * Biconditional $\iff$
# Distributivity
$*$ is left-distributive over $+$ if $x*(y+z)=(x*y)+(x*z)$  
$*$ is right-distributive over $+$ if $(x+y)*z=(x*z)+(y*z)$  
(if $*$ is commutative then it is either both or neither.)
 ## Operators:
 * Multiplication $*$ over Addition $+$
 * And $\land$ over Or $\lor$
 * Or $\lor$ over And $\land$
# Geometric algebra
Vectors are a linear combinations of the basis vectors. (Here $e0,e1,...$)
## Geometric product $uv$
this is defined by one rule: $uv = -vu$ where $(u \neq v)$.
The squired length of a vector is given by the geometric product with itself.
A basis can then be declared by just defining the squires of the basis vectors.
$uv =$  
$(a*e_0+b*e_1+...)(c*e_0+d*e_1+...) =$  
$(a*e_0(c*e_0+d*e_1+...)+b*e_1(c*e_0+d*e_1+...)+...) =$  
$a*c*e_0e_0+a*d*e_0e_1+...+b*c*e_1e_0+b*d*e_1e_1+... =$  
$ac*e_0^2+bd*e_1^2+(ad-bc)*e_{01}+... =$
## Outer product $u \land v$
There are two other operators on vectors:  $\land$ and $*$ which follow this rule:
$uv = u \land v + u * v$  
$\land$ follows these rules:  
$u \land v = - v \land u$ where $u \neq v$  
$u \land u = 0$
## Inner product $u*v$
If two vectors are orthogonal their inner product will be zero.
If the inner product if taken of 2 vectors that are parallel, it will be their lengths multiplied.
## k-vectors
k vectors are vectors where its components consist of k basis vectors.  
$(e_0+e_1)$ is a 1-vector or a vector
$(e_{01}+e_{12})$ is a 2-vector or a bivector
the dual of a vector is the outer product of that vector and the pseudoscaler which is all the basis vectors multiplied together.
$(e_0+e_1)*e_{012} = (e_0^2*e_{12}-e_1^2*e_{02})$
$(e_{01}+e_{12})*e_{012} = -e_1^2*(e_{2}+e_{0})$  
Basis list:
* {0,1,1,1,...} represents the space multidimensional linear equations (lines of planes)
* {1,1,1,...} represent normal space
* {-1} are the complex numbers
* {1} are the split complex numbers
* {0} are the dual numbers
* {1,-1,-1,-1,...} represents space-time
## Rotors / Moters
idk