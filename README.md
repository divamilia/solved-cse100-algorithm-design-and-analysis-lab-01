Download Link: https://assignmentchef.com/product/solved-cse100-algorithm-design-and-analysis-lab-01
<br>
<strong>Linear Search</strong>

<strong>Description </strong>In this assignment you are requested to implement linear search algorithm for finding an item in an array:

<strong>Require: </strong><em>a</em>: array of elements, of type <em>T</em>

<strong>Require: </strong><em>a<sub>s</sub></em>: element to find, of type <em>T</em>

1: <em>N </em>← <em>length</em>(<em>a</em>)

2: <strong>for </strong><em>i </em>← 1 to <em>N </em><strong>do</strong>

3:               <strong>if </strong><em>a<sub>i </sub></em>= <em>a<sub>s </sub></em><strong>then</strong>

4:                <strong>return </strong><em>i</em>

5:           <strong>end if</strong>

6: <strong>end for</strong>

7: <strong>return </strong>-1

<strong>Input structure </strong>The sequences and the element to search are integers (i.e. you can safely store them into int variables). Each case starts with a number which is the number of integers in the sequence. The following number is the element to search. Then the elements of the sequence follow, one per line.

<strong>Output structure </strong>Algorithm must return −1 if <em>a<sub>s </sub></em>is not in the sequence, or its position (i.e. array index) if it is contained. You can assume that all the numbers in the sequence are distinct.