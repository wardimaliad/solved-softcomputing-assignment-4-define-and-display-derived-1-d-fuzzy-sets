Download Link: https://assignmentchef.com/product/solved-softcomputing-assignment-4-define-and-display-derived-1-d-fuzzy-sets
<br>
Define and Display Derived 1-D Fuzzy Sets.

<ul>

 <li>Copy the last assignment and rename the solution folder name to xxxAss04Solution, following the steps: (a) copy all artifacts to a new folder, rename the folder name to indicate Ass04, (b) change the name of *.sln file to indicate Ass04, (c) change the project name from Ass03 to Ass04 in solution explorer. (d) rename the old namespace name and change default namespace name from xxAss03 to xxAss04.</li>

 <li>Analyze the data structures of the one-dimensional fuzzy sets and fuzzy sets that are resulted from various operations (unary, binary operators, T-norm, S-norm operations) on given fuzzy sets.</li>

 <li>Exercise object-oriented techniques to design related C# classes for those fuzzy sets that are generated from various operations. The binary operators include the traditional intersection, union, and subtraction operators. Unary operators include negation, value<em>–</em>cut, value-scale operators and linguistic hedges operators such as Very (Concentration), More or less (Dilation), Extremely, Intensification, Diminisher, …, etc.</li>

 <li>For constructing an operated fuzzy set, the operator must be specified by the user. Therefore, you need to define a family of classes for these operators. For example, defining classes of a UnaryFuzzySetOperator and a BinaryFuzzySetOpertor. Notice that an enhanced operator might have parameters specified; e.g., operators proposed by the scholars and experts.</li>

 <li>It is suggested to create class families for unary and binary operators first, which are similar to the FuzzySet class family. Then, classes UnaryOperatedFuzzySet and BinaryOperatedFyzzeSet are defined as derived classes inheriting the generic FuzzySet class. Within these classes, references to the original fuzzy set(s) and operator should be defined and initialized in the constructor. Since a fuzzy set might be referenced by another fuzzy set, <strong>events</strong> of parameter changed should be defined in FuzzySet class.</li>

 <li>In your main form class, prepare UIs for the user to select created fuzzy sets first from the TreeView that lists the hierarchical structure of the universes and fuzzy sets or from Chart control directly. Labels can be used to store two selected functions subject to a binary operation. Then user is able to select unary/binary operators to create a derived fuzzy set generated from the selected sets.</li>

 <li>An advanced topic is the operator overloading for algebraic operations on FuzzySets. For example, operators &amp;&amp;, ||, ! can be overloaded for Intersect, Union, Negate operators on fuzzy sets.</li>

</ul>

Sample UI