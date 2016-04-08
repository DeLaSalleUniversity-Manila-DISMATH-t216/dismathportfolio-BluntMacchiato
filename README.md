# dismathportfolio-BluntMacchiato
dismathportfolio-****** created by Classroom for GitHub

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
	- Inductive Step
- **Recursive Algorithms**:
	- recursive algorithm solves a problem by reducing it to an instance of the same problem with smaller input.

# **#imtrying**
#Week 5:
#Week 5:
#Week 5:
#Week 5:
#Week 5:
