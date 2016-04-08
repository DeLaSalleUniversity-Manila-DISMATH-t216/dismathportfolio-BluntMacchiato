# dismathportfolio-BluntMacchiato
dismathportfolio-****** created by Classroom for GitHub

11413131 Businos, Michael Anthony T. DISMATH-EL

#WEEK 1:
- I was introduced to Discrete Mathematics and its significance in engineering and the current information society.		
- The Syllabus was explained for me to know what is to be expected in the course.		
- Thinking critically and logically is the goal of the course.
- The logical puzzle of knights and knaves was presented to better show what is to come.
- Basic terms like proof, proposition, axioms, logical deduction.
	- propositions are declarative statements that has the truth value of either true or false but not both.
	- proof is a valid argument that established the truth of a theorem.
	- axioms are statements that we assume to be true.
- There are many types of truths such as Legal truth, Scientific truth, but Discrete mathematics only deals with Mathematical truth
- I learned logical symbols for negation, conjunction, disjunction, exclusive disjunction, implication and biconditional.
- I was taught about the logical tool truth table and its uses.
	- a truth table is a table that displays the truth value of a proposition.
	- and the number of rows for the truth table is 2^n; n being the number of varialbes.
- Logical Connectives and their respective truth tables.


| Logical Symbol | Logical Operator |	Shorthand | Logical Expression |
| ------------- |:-------------:| -----:| -----:|
|*¬* | Negation | not |¬p|
|*∧* | Conjunction | and |p ∧ q|
|*∨* | Disjunction  | or |p v q|
|*⊕ * | Exclusive or  | xor |p ⊕ q ≡ (¬p ∧ q) v (p ∧ ¬q)|
|*→* | Conditional  | if, then |p → q ≡ ¬p v q|
|*↔* | Biconditional  | iff |p ↔ q ≡ (p → q) ∧ (q → p)|

#Week 2:
- **Propositional Logic**
	- deals with proposition as a whole
	- as p → q 
		- Inverse ≡ ¬p → ¬q
		- Converse ≡ q → p
		- Contrapositive ≡ ¬q → ¬p  

- Another Logical tool that can be used to prove propositions are **logical equivalences**.


|Name |	Equivalence|
| -----:| :-----|
|Identity laws |<ul><li> p ∧ T ≡ p	<li> p v F ≡ p</ul>|
|Domination laws |<ul><li> p v T ≡ T <li>p ∧ F ≡ F</ul>|
|Negation laws |<ul><li> p v ¬p ≡ T <li> p ∧ ¬p ≡ F</ul>|
|Double negation law	|<ul><li> ¬(¬p) ≡ p</ul>|
|Idempotent laws	|<ul><li>	p v p ≡ p	<li> p ∧ p ≡ p</ul>|
|Commutative laws |<ul><li>	p v q ≡ q v p <li> p ∧ q ≡ q ∧ p</ul>|
|Associative laws	|<ul><li>	(p v q) v r ≡ p v (q v r)	<li>(p ∧ q) ∧ r ≡ p ∧ (q ∧ r)</ul>|
|Distributive laws	|<ul><li>	p v (q ∧ r) ≡ (p v q) ∧ (p v r)	<li> p ∧(q v r) ≡ (p ∧ q) v (p ∧ r)</ul>|
|De Morgan's laws	|	<ul><li> ¬(p ∧ q) ≡ ¬p v ¬q	<li> ¬(p v q) ≡ ¬p ∧ ¬q</ul>|
|Absorption laws	| <ul><li> p v (p ∧ q) ≡ p	<li> p ∧ (p v q) ≡ p</ul>|


- **Predicate Logic**
	- concern in internal structure in terms of subject and predicate.
- **Quantifiers**
	- Quantifiers has two kinds: Universal and Existensial.
	- Universal (∀x) - "for all" meaing it should be true to all values.
	- Existensial (∃x) - "there exists", meaning it is true to atleast one value. 
- Supes does not exist 
	- ***icry***

#Week 3:

- Important terms such as argument, valid, fallacy, tautology		
	- argument is a sequence of statement that ends with a conclusion.
	- valid means that the conclusion of the argument must follow from the truth of the premises of the argument.
	- fallacy is an invalid argument
	- tautology is a statement that is always true
- Another way of proving propostions are by using the **rules of inference**.


|Type|	Rule of Inference	|Tautology|
| -----:| -----:|----------:|
|Modus Ponens	|p, p → q ∴ q	|[p ∧ (p → q)] → q|
|Modus Tollens|	¬q, p → q ∴ ¬p|	[¬q ∧ (p → q)] → ¬p|
|Hypothetical Syllogism	|p → q, q → r ∴ p → r	|[(p → q) ∧ (q → r)] → (p → r)|
|Disjunctive Syllogism|	p ∨ q, ¬p ∴ q	|[(p ∨ q) ∧ ¬p] → q|
|Addition	|p ∴ p ∨ q|	p → p ∨ q|
|Simplification|	p ∧ q ∴ p	|(p ∧ q) → p|
|Conjunction|	p, q ∴ p ∧ q|	[(p) ∧ (q)] → (p ∧ q)|
|Resolution|	p ∨ q, ¬p ∨ r ∴ q ∨ r	|[(p ∨ q) ∧ (¬p ∨ r)] → q ∨ r|

- Logical tools so far:
	- Truth Table
	- Logical Equivalences
	- Quantifiyers
	- Rules of Inference

#Week 4:
**Methods of Proof**	

|Method of Proof|Steps|
|:-----|:-------|
|Direct Proof (p → q)|<ol type="1"><li> Assume p is true. <li> Show that q is true (based on 1).	</ol>	|
|Proof by Contraposition (¬q → ¬p)|<ol type="1"><li> Assume ¬q is true. <li> Show that ¬p is true(based on 1).</ol>|		
|Proof by Contradiction|<ol type="1"><li>	Assume ¬p is true. <li> Show that 1. ends up in a contradiction.</ol>	|
|Vacuous Proof (¬p → (p → q))| 1. Show that p is false, because (p → q) must be true when p is false.|
|Trivial Proof (q → (p → q))|	1. how that q is true, it follows that (p → q) must also be true.		|


#Week 5:
- **Mathematical Induction** has two steps:
	- Basis Step
	- Inductive Step create a equation for finding its value
- **Recursive Algorithms**:
	- recursive algorithm solves a problem by reducing it to an instance of the same problem with smaller input.

- **Program Correctness**
	- proof that shows that the program will always give the correct output for every possible input.
	- Proof of correctness of programs through the use of mathematical induction.
	- It is said to be correct if it produces the correct output for every possible input.
	- This is proven if the program:
		1. Show that the correct answer is obtained.
		2. Show that the program always terminates. 
- **Partial Correctness**
	- Two propositions are used to specify what it means for a program to produce the correct output:
	- Initial Assertion gives the properties that the input values must have
	- Final Assertion gives the properties that the output of the program should have, if the program did what it was told
	- Partial Correctness can be proved by Hoare Triple and by Rules of Inference.
- **Hoare Triple**
	- p{s}q 	A Hoare triple has three parts, a precondition P, a program statement or series of statements S, and a postcondition Q. 
	- The meaning is "if P is true before S is executed, and if the execution of S terminates, then Q is true afterwards". 
- **Rules of Inference**
	- Conditional Statements
- **Power Series**
- Introduction to Set Theory
#Week 6:
- **Set Theory**
	- set is an unordered list of distinct objects
	- sets can be represented by Set Builder Notation {x | some property that x satisfies}
	- Empty Set { } = ∅ means no elements
- **Subsets ⊆**
	- A set S is a subset of a set T (denotes S ⊆ T) if all elements of S are also elements of T
- **Cardinality |S|**
	- TThe term cardinality refers to the number of cardinal (basic) members in a set. 
	- Cardinality can be finite (a non-negative integer) or infinite.
- **Functions**
	- Different types  of functions
		1. One-to-One (Injective) it never maps distinct elements of its domain to the same element of its codomain.
		2. Onto (Surjective) funtions have equal range & co-domain.
		3. One-to-One Onto (Bijective) is both one - to - one and onto.
- 

#Week 7:		
No Classes
#Week 8:
- **Algorithm**
	- A set of rules followed by the computer
	- Pseudocode is an informal high-level description of the operating principle of a computer program or other algorithm.
	- It uses the structural conventions of a programming language, but is intended for human reading rather than machine reading.
	- Valide INput and output
	- sample:
```	
	PROCEDURE max(a1, a2, ... an: Z)  
	max = a1  
	    for i = 2 to n	  
		if max < aj then max = aj  
	{Output: max is the largest element}
```

#Week 9:
- **Types of Algorithm Discussed**
	- **Searching Algorithms** 
	 	- Problem of locating an algorithm in an ordered list
		- **Linear Search** 
		 	- finding a particular value in a list that checks each element in sequence until the desired element is found
		- **Binary Search** 
			- comparing the middle values of a list then repeated until the desired output is found.
	- **Sorting Algorithms** 
	 	- Problem of assorting elements into increasing order
		- **Bubble Sort** 
			- compares the first two elements then interchanging them if they are in the incorrect order.
		- **Insertion Sort** 
			- compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.
	- **Greedy Algorithm** 
	 	- Algorithms that make what seems to be the "best" choice at each step. 
		- Selects the best choice at each step, instead of considering all sequences of steps that may lead to optimal solution

#Week 10:

- **Introduction to Growth of Functions**
- **Big-O Notation**
	- Let f and g be functions from R-R; f(x) is O(g(x)) 
	- if there are constants C and k such that: |f(x)| ≤ C|g(x)| whenever x > k.
	- Example: f(x)=x^2 + 2x + 1; O(x^2); k=1, C=4
- **Big-Omega and Big-Theta Notation**
	- Big-O Notation does not provide a lowerbound for the size of f(x). 
	- Big-Omega (Big-Ω) - Lower bound 
	- Big-Theta (Big-Θ) - Both upper and lower bound
- **Algorithm Time Complexity **
	- usually expressed in terms of operations used by the algorithm when the input has a particular size.
- **Division and Modulo Operator**
#Week 11:
No Classes
#Week 12:
- **Graph Theory**
- **Introduction to Graph Theory**
- G=(V,E)It is a structure that consists of Vertices or nodes and Edges or connections.
- **Definitions**
	- Degree of a node is the number of edges incident with it but loops are counted twice.
	- Subgraph - A graph whose vertices and edges are subsets of another graph.
	- Path is created when walking from node to node along the edges.
	- Pendant is a node with only one degree.
	- Isolated a node with no connections
	- Isomorphic Graphs are graphs that have equal nodes, and have the same connection.
- **Handshaking Theorem**: 2e = Sum[deg(v)] where e is the total number of edges in the graph.
- **Euler's Circuit and Path**
	- Euler's Circuit is a (closed) walk wherein it covers all edges exactly once and goes back to the vertex where it started.
	- exists whenever every vertex in the graph has even degree.
	- while Euler Path is a (open) walk where all edges are covered once. 
	- exists whenever there are exactly two vertices with odd degree.
- **Euler's Formula**: r = e - v + 2, where r is the number of regions formed by a graph.
	- Euler's Formula can be manipulated to produce Euler's characteristic: x = r - |e| + |v| = 2
- **Hamilton Circuit and Path**
	- Hamilton Circuit a (closed) walk where all nodes are covered once and returns to the origin node.
	- Hamilton path an open walk where all nodes are covered and does not return to the origin node.
- **Matrices of Graph** - 1 for adjacent; 0 for non-adjacent
	- Adjacency Matrix - to put a graph into a table by identifying connections of an edge between vertices.
	- Incidence Matrix - table between edges and vertices
- **Planar Graph**
	- Planar graph is a graph where no edges intersect.
- **Homeomorphic Graphs**
	- Elementary Subdivision - Everything is planar graph
- **Kuratowskis Theorem **
	- states that a graph is non-planar if and only if it contains a subgraph homeomorphic to K(3,3) and K(5).
#Week 13:
- **Graph Coloring**
	- assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color
	- Four Color Theorem is the chromatic number of a planar graph is no greater than four
- **Trees**
	- connected undirected graph with no simple circuits
	- data structure that emulates a heirarchical tree structure with a set of linked notes used to construct efficient algorithms for locating an item in a set
	- Forest - multiple trees
	- Rooted Tree - a tree in which one vertex has been designated as the root and every edge
	- leaves - nodes that do not have children
	- ancestors - nodes on top
	- descendants - children/grandchildren
	- Subtree
	- M-ary tree - if every internal vertex has no more than m children an m-ary tree with m = 2 is called a binary tree
- **Modeling Computation**
	- Language and Grammars
		- Grammars - used to generate the words of a language and to determine whether a word is in a language
		- Compiler - reads a program written in a source language and translate it into an equivalent program in a target language.
		- Formal Language - automatic translation of one language to another well defined set of rules
- **Alphabet & String**
	- common way to talk about words, numbers, etc.
- **Automata Theory**
	- Law of computation
	- Finite Automata - simplest model of automata 
		- initial state
		- final/acceptance state
		- dead/stuck state
		- transition
- **Lexical Analysis**
	- process where the stream of characters making up the source program into a sequence of "words" that make up the source code.
- **Finite State Machine**
	- finite-state automaton M = (S, I, O, f, g, s0) 
		- S: Finite set of states
		- I: Finite input alphabet
		- O: Finite output alphabet
		- f: Transition function
		- g: Output function
		- s0: Initial state 
		- 
THANKYOU!
