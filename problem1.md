
<p> Project Euler Problem 1 </p> 
We are given the following problem: 
<br>
<p> If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. </p>
<p> Find the sum of all the multiples of 3 or 5 below 1000. </p>


$$ 
a = \left \lfloor \frac{n}{3} \right \rfloor
$$

$$
b = \left \lfloor \frac{n}{5} \right \rfloor \\
$$ 

$$
 t = \left \lfloor \frac{n}{15} \right \rfloor
$$


$$
u = \sum_{i=1}^{a} 3i ~ ~ ~ ~ ~ ~
v = \sum_{i=1}^{b} 5i ~ ~ ~ ~ ~ ~
w = \sum_{i=1}^{t} 15i \\
$$








