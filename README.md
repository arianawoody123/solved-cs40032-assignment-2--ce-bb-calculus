Download Link: https://assignmentchef.com/product/solved-cs40032-assignment-2-%ce%bb-calculus
<br>



<ol>

 <li>Reduce the following <em>λ</em>-expressions. Show every step of <em>α</em>-, <em>β</em>-, <em>η</em>– and <em>δ</em> <strong>[2 * 7 = 14]</strong>

  <ul>

   <li>(<em>λz. z</em>) (<em>λy. y y</em>) (<em>λx. x a</em>)</li>

   <li>(<em>λz. z</em>) (<em>λz. z z</em>) (<em>λz. z y</em>)</li>

   <li>(<em>λx. λy. x y y</em>) (<em>λa. a</em>) <em>b</em></li>

   <li>(<em>λx. λy. x y y</em>) (<em>λy. y</em>) <em>y</em></li>

   <li>(<em>λx. x x</em>) (<em>λy. y x</em>) <em>z</em></li>

   <li>(<em>λx. </em>(<em>λy. </em>(<em>x y</em>)) <em>y</em>) <em>z</em></li>

   <li>(((<em>λx. </em>(<em>λy. </em>(<em>x y</em>)) (<em>λy. y</em>)) <em>w</em>)</li>

  </ul></li>

 <li>Solve the following using Y combinator <strong>[2 + 4 = 6]</strong>

  <ul>

   <li>Write the recursive definition for <em>TriProduct </em>where <em>TriProduct</em>(<em>n</em>) can be defined as</li>

  </ul></li>

</ol>

<em>TriProduct</em>(<em>n</em>)        =      <em>n</em>*       (<em>TriProduct</em>(<em>n </em>− 1)           <em>if n &gt; </em>3

+        <em>TriProduct</em>(<em>n </em>− 2)


<em>TriProduct</em>(<em>n </em>− 3)),

=      5,                                                      <em>if n </em>= 3

=      2,                                                      <em>if n </em>= 2

=      1                                                       <em>if n </em>= 1

Using Y combinator, encode the above recursive definition of <em>TriProduct </em>as <em>λ</em>-expressions

<ul>

 <li>Reduce <em>TriProduct </em> Show every step of <em>β</em>– and <em>δ</em>– reductions. You may skip <em>α</em>-reduction steps with a mention of the step.</li>

</ul>