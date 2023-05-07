Download Link: https://assignmentchef.com/product/solved-numerical-analysis-homework-2
<br>



<ul>

 <li>To get full credit, <em>you must write down sufficient intermediate steps</em>, only giving the final answer earns you no credit!</li>

 <li>Please make sure that your handwriting is recognizable, otherwise you only get partial credit for the recognizable part.</li>

</ul>

<ol>

 <li>For <em>f </em>∈ C<sup>2</sup>[<em>x</em><sub>0</sub><em>,x</em><sub>1</sub>] and <em>x </em>∈ (<em>x</em><sub>0</sub><em>,x</em><sub>1</sub>), linear interpolation of <em>f </em>at <em>x</em><sub>0 </sub>and <em>x</em><sub>1 </sub>yields</li>

</ol>

<em>.</em>

Consider the case

<ul>

 <li>Determine <em>ξ</em>(<em>x</em>) explicitly.</li>

 <li>For <em>x </em>∈ [<em>x</em><sub>0</sub><em>,x</em><sub>1</sub>], find max<em>ξ</em>(<em>x</em>), min<em>ξ</em>(<em>x</em>), and max<em>f</em><sup>00</sup>(<em>ξ</em>(<em>x</em>)).</li>

</ul>

<ol>

 <li>Let <sup>P</sup><em><sub>m</sub></em><sup>+ </sup>be the set of all polynomials of degree ≤ <em>m </em>that are non-negative on the real line,</li>

</ol>

P<sup>+</sup><em><sub>m </sub></em>= {<em>p </em>: <em>p </em>∈ P<em>m, </em>∀<em>x </em>∈ R<em>,p</em>(<em>x</em>) ≥ 0}<em>.</em>

Find such that <em>p</em>(<em>x<sub>i</sub></em>) = <em>f<sub>i </sub></em>for <em>i </em>= 0<em>,</em>1<em>,…,n </em>where <em>f<sub>i </sub></em>≥ 0 and <em>x<sub>i </sub></em>are distinct points on R.

<ul>

 <li>Consider <em>f</em>(<em>x</em>) = <em>e<sup>x</sup></em>.

  <ul>

   <li>Prove by induction that</li>

  </ul></li>

</ul>

<em>.</em>

<ul>

 <li>From Corollary 3.17 we know</li>

</ul>

<em>ξ </em>∈ (0<em>,n</em>) s.t.<em>.</em>

Determine <em>ξ </em>from the above two equations. Is <em>ξ </em>located to the left or to the right of the midpoint <em>n/</em>2?

<ol start="12">

 <li>Consider <em>f</em>(0) = 5, <em>f</em>(1) = 3, <em>f</em>(3) = 5, <em>f</em>(4) = 12.

  <ul>

   <li>Use the Newton formula to obtain <em>p</em><sub>3</sub>(<em>f</em>;<em>x</em>);</li>

   <li>The data suggest that <em>f </em>has a minimum in <em>x </em>∈ (1<em>,</em>3). Find an approximate value for the location <em>x</em><sub>min </sub>of the minimum. V. Consider <em>f</em>(<em>x</em>) = <em>x</em><sup>7</sup>.</li>

   <li>Compute <em>f</em>[0<em>,</em>1<em>,</em>1<em>,</em>1<em>,</em>2<em>,</em>2].</li>

   <li>We know that this divided difference is expressible in terms of the 5th derivative of <em>f </em>evaluated at some <em>ξ </em>∈ (0<em>,</em>2). Determine <em>ξ</em>.</li>

  </ul></li>

 <li><em>f </em>is a function on [0<em>,</em>3] for which one knows that <em>f</em>(0) = 1<em>,f</em>(1) = 2<em>,f</em><sup>0</sup>(1) = −1<em>,f</em>(3) = <em>f</em><sup>0</sup>(3) = 0<em>.</em>

  <ul>

   <li>Estimate <em>f</em>(2) using Hermite interpolation.</li>

   <li>Estimate the maximum possible error of the above answer if one knows, in addition, that <em>f </em>∈ C<sup>5</sup>[0<em>,</em>3] and |<em>f</em><sup>(5)</sup>(<em>x</em>)| ≤ <em>M </em>on [0<em>,</em>3]. Express the answer in terms of <em>M</em>.</li>

  </ul></li>

</ol>

<ul>

 <li>Define forward difference by</li>

</ul>

∆<em>f</em>(<em>x</em>) = <em>f</em>(<em>x </em>+ <em>h</em>) − <em>f</em>(<em>x</em>)<em>,</em>

∆<em><sup>k</sup></em><sup>+1</sup><em>f</em>(<em>x</em>) = ∆∆<em><sup>k</sup>f</em>(<em>x</em>) = ∆<em><sup>k</sup>f</em>(<em>x </em>+ <em>h</em>) − ∆<em><sup>k</sup>f</em>(<em>x</em>)

and backward difference by

∇<em>f</em>(<em>x</em>) = <em>f</em>(<em>x</em>) − <em>f</em>(<em>x </em>− <em>h</em>)<em>,</em>

∇<em><sup>k</sup></em><sup>+1</sup><em>f</em>(<em>x</em>) = ∇∇<em><sup>k</sup>f</em>(<em>x</em>) = ∇<em><sup>k</sup>f</em>(<em>x</em>) − ∇<em><sup>k</sup>f</em>(<em>x </em>− <em>h</em>)<em>.</em>

Prove

∆<em><sup>k</sup>f</em>(<em>x</em>) = <em>k</em>!<em>h<sup>k</sup>f</em>[<em>x</em><sub>0</sub><em>,x</em><sub>1</sub><em>,…,x<sub>k</sub></em>]<em>,</em>

∇<em><sup>k</sup>f</em>(<em>x</em>) = <em>k</em>!<em>h<sup>k</sup>f</em>[<em>x</em><sub>0</sub><em>,x</em><sub>−1</sub><em>,…,x</em><sub>−<em>k</em></sub>]<em>, </em>where <em>x<sub>j </sub></em>= <em>x </em>+ <em>jh</em>.

<ul>

 <li>∗ Assume <em>f </em>is differentiable at <em>x</em><sub>0</sub>. Prove</li>

</ul>

<em>.</em>

What about the partial derivative with respect to one of the other variables?

Problem II weighs 4 points, VIII weighs 5 points, and all other problems weigh 6 points each. The total point is thus 40. The last problem is for extra credit and you do not have to solve it. However, my graduate students who audit this class have to solve all problems.