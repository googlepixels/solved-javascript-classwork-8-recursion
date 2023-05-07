Download Link: https://assignmentchef.com/product/solved-javascript-classwork-8-recursion
<br>
Recursion




<ol>

 <li>Write a recursive function to determine whether all digits of the number are odd or not.</li>

</ol>




<table width="576">

 <tbody>

  <tr>

   <td width="288"><strong>Input</strong></td>

   <td width="119"> </td>

   <td width="170"><strong>Output</strong></td>

  </tr>

  <tr>

   <td width="288">4211133</td>

   <td width="119">false</td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">7791</td>

   <td width="119">true</td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">5</td>

   <td width="119">true</td>

   <td width="170"> </td>

  </tr>

 </tbody>

</table>







<ol start="2">

 <li>Given an array of numbers. Write a recursive function to find its minimal positive element. (if such element does not exist, return -1)․</li>

</ol>




<table width="576">

 <tbody>

  <tr>

   <td width="288"><strong>Input </strong></td>

   <td width="45"> </td>

   <td width="73"> </td>

   <td width="170"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="288">[56, -9, 87, -23, 0, -105, 55, 1]</td>

   <td width="45">0</td>

   <td width="73"> </td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">[45, -9, 15, 5, -78]</td>

   <td width="45">5</td>

   <td width="73"> </td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">[-5, -9, -111, -1000, -7]</td>

   <td width="45">-1</td>

   <td width="73"> </td>

   <td width="170"> </td>

  </tr>

 </tbody>

</table>







<ol start="3">

 <li>Given an array of numbers which is almost sorted in ascending order. Find the index where sorting order is violated.</li>

</ol>




<table width="576">

 <tbody>

  <tr>

   <td width="288"><strong>Input</strong></td>

   <td width="119"> </td>

   <td width="170"><strong>Output</strong></td>

  </tr>

  <tr>

   <td width="288">[2, 12, 15, 48, 64]</td>

   <td width="119">-1</td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">[-9, -4, -4, 3, 12, 4, 5]</td>

   <td width="119">5</td>

   <td width="170"> </td>

  </tr>

 </tbody>

</table>







<ol start="4">

 <li>Given an array. Write a recursive function that removes the first element and returns the given array. (without using ​<em>shift()</em>​)</li>

</ol>




<table width="576">

 <tbody>

  <tr>

   <td width="288"><strong>Input </strong></td>

   <td width="119"> </td>

   <td width="170"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="288">[6, 78, ‘n’, 0, 1]</td>

   <td width="119">[78, ‘n’, 0, 1]</td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">[5]</td>

   <td colspan="2" width="288">[]</td>

  </tr>

  <tr>

   <td width="288">[]</td>

   <td colspan="2" width="288">[]</td>

  </tr>

 </tbody>

</table>







<ol start="5">

 <li>Given an array of nested arrays. Write a recursive function that flattens it. (Hint create function that concats arrays).</li>

</ol>




<table width="576">

 <tbody>

  <tr>

   <td width="288"><strong>Input </strong></td>

   <td width="288"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="288">[1, [3, 4, [1, 2]], 10]</td>

   <td width="288">[1, 3, 4, 1, 2, 10]</td>

  </tr>

  <tr>

   <td width="288"> [14, [1, [[[3, []]], 1], 0]</td>

   <td width="288">[14, 1, 3, 1, 0]</td>

  </tr>

 </tbody>

</table>










<ol start="6">

 <li>Given an array and a number N. ​ ​Write a recursive function that rotates an array N places to the left. (​<em>Hint</em>​: to add element to the beginning use ​<em>unshift()</em>​)</li>

</ol>




<table width="577">

 <tbody>

  <tr>

   <td width="289">[‘a’, ‘b’, ‘c’, ‘d’, ‘e’, ‘f’, ‘g’, ‘h’] 3</td>

   <td width="288">[‘d’, ‘e’, ‘f’, ‘g’, ‘h’, ‘a’, ‘b’, ‘c’]</td>

  </tr>

  <tr>

   <td width="289">[‘a’, ‘b’, ‘c’, ‘d’, ‘e’, ‘f’, ‘g’, ‘h’] -2</td>

   <td width="288">[‘g’, ‘h’, ‘a’, ‘b’, ‘c’, ‘d’, ‘e’, ‘f’] <strong> </strong></td>

  </tr>

 </tbody>

</table>













<ol start="7">

 <li>Given a number. Write a function that calculates its sum of the digits and if that sum has more than 1 digit find the sum of digits of that number. Repeat that process if needed and return the result.</li>

</ol>







<table width="576">

 <tbody>

  <tr>

   <td width="288"><strong>Input </strong></td>

   <td width="119"> </td>

   <td width="170"><strong>Output </strong></td>

  </tr>

  <tr>

   <td width="288">14</td>

   <td width="119">5</td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">29</td>

   <td width="119">2</td>

   <td width="170"> </td>

  </tr>

  <tr>

   <td width="288">999999999999</td>

   <td width="119">9</td>

   <td width="170"> </td>

  </tr>

 </tbody>

</table>







<ol start="8">

 <li>Implement merge sort</li>

</ol>