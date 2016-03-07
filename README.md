# dismathportfolio-paulomiguelambion
dismathportfolio-paulomiguelambion created by Classroom for GitHub

#DISCRETE MATHEMATICS PORTFOLIO
##WEEK 1 (January 20, 2015 Wednesday)
  * Today we start this course called Discrete Mathematics (DISMATH). It is about mathematical reasoning, combinatory analysis, discrete structures, algorithmic thinking, applications and modeling.
  * I've learned that this course is understanding low level knowledge which is closer to the machine knowledge of understanding commands.
  * Proposition was also elaborated and I've learned that proposition is a declarative sentence that is either true or false, **but not both**. (K. Rosen)
  * I've also learned that it is tricky to understand whether a statement is a proposition, so to easily check the statement it is better to ask if the statement is answerable by true or false.
  * I've also learned that, paradoxical statements are eliminated in DISMATH.
  * 
  
  ##WEEK 2 Day 1 (January 25, 2016 Monday)

  * Today I've learned about Logical Connectives and Truth Tables.
  * We've discussed how to use Logical Operators and how to prove a logical expression with the help of the truth tables.

  | **LOGICAL SYMBOL** | **LOGICAL OPERATOR** | **SIMPLE TERM** | **FORMULA** |   **LOGICAL EQUATION**     |
  |:------------------:|:--------------------:|:-------------:|:-----------:|:----------------------------:|
  | ¬  |Negation|not|val(¬p)=1 - val(p)|¬p|
  |^|Conjunction|and|val (p ^ q) = min(val(p), val(q))|p^q|
  | v |Disjunction| or | val(p  v q) = max(val(p), val(q))|p v q|
  |⊕ |Exclusive Disjunction| xor | if val(p) not equal val(q) = 1 ,otherwise 0 | p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
  | → | Conditional | if then | if val(p) ≤ val(q) = 1, otherwise 0| p → q ≡  ¬p v q |
  |↔ | Biconditional | iff | if val(p) equals val(q) = 1, otherwise 0 | p ↔ q ≡ (p → q) ∧ (q → p) |

* I've learned that negation inverts a proposition.

|**p**|**q**|
|:-------:|:-------:|
|T|F|
|F|T|

TRUTH TABLE FOR CONJUNCTION

|**p**|**q**|**p^q**|
|:-------:|:-------:|:-------:|
|T|T|T|
|T|F|F|
|F|T|F|
|F|F|F|

TRUTH TABLE FOR DISJUNCTION

|**p**|**q**|**p vq**|
|:-------:|:-------:|:-------:|
|T|T|T|
|T|F|T|
|F|T|T|
|F|F|F|

TRUTH TABLE FOR EXCLUSIVE DISJUNCTION

|**p**|**q**|**p⊕ q**|
|:-------:|:-------:|:-------:|
|T|T|F|
|T|F|T|
|F|T|T|
|F|F|F|

TRUTH TABLE FOR CONDITIONAL

|**p**|**q**|**p→q**|
|:-------:|:-------:|:-------:|
|T|T|T|
|T|F|F|
|F|T|T|
|F|F|T|

TRUTH TABLE FOR BICONDITIONAL

|**p**|**q**|**p↔q**|
|:-------:|:-------:|:-------:|
|T|T|T|
|T|F|F|
|F|T|F|
|F|F|T|

##WEEK 2 Day 2 (January 27, 2016 Wednesday)

* Today we've discussed about Logic Laws and Logial Equivalences.
* I've learned about Identity LAw, Domination Law which states that Truth always dominates in disjunction (max) and False always dominates in Conjuction (min).
* Negation states that in *disjuction*, when a subject is paired by its negation then the result will always be **True** however, it is always **False** in *conjunction*.
* Indempotent Law says that when a statement is added or multiplied by itself, then the answer will always be itself.
* I've also learned that every logical laws except for ***De Morgan's Law and Absorption Law*** are all present in algebra.
* I've also learned that it is important to consider every laws to use or every steps to use in getting the correct result in evaluating or prooving of statements.

##WEEK 3 Day 1 (February 01, 2016 Monday)

* Today Today I've learned new terms like ***Coverse, counter example, inverse and contrapositive***.
* also, inverse is not equal to the implication however contrapositive is.

######COVERSE

|**p**|**q**|**p→q**|**q→p** (**CONVERSE**)|
|:-------:|:-------:|:-------:|:-------:|
|T|T|T|T|
|T|F|F*|F*|
|F|T|T|T|
|F|F|T|T|

  - (*) an example of counter example

######INVERSE

|**p**|**q**|**p→q**|**¬p → ¬q** (**INVERSE**)|
|:-------:|:-------:|:-------:|:-------:|
|T|T|T|T|
|T|F|F|F|
|F|T|T|T|
|F|F|T|T|

######CONTRAPOSITIVE

|**p**|**q**|**p→q**|**¬q → ¬p**(**CONTRAPOSITIVE**)|
|:-------:|:-------:|:-------:|:-------:|
|T|T|T|T|
|T|F|F|T|
|F|T|T|F|
|F|F|T|T|

* TAUTOLOGY means that in all condition the answer will always be **true**.
* we've also tackled about **UNIVERSAL and  EXISTENTIAL QUANTIFIER.
* Unversal Quatifier can only be true if and only if all the values of a variable in a particular domain is true.
* Existential Quantifier o the otherhand can be true if and only if at least one of the values of a variable in a particular domain is true.
* 

##WEEK 3 Day 2 (February 3, 2016 Wednesday)

* Last meeting we were assigned to read about Nested Quatifiers and I have learned that it is two quantifiers are said to be nested if one is within the scopes of the other.
* Als, we've discussed about Inference. I've learned that unlike nested quatifiers, it neither use a property nor a predicate but a premise in making conditions.
* We've also discussed about new terminologies such as **argument** which means a sequence of statements that end with a conclusion, **valid** that means the conclusion or final statement of the argument, must follow from the truth of the preceeding statements, or premise, of the argument (tatology), and **fallacy** which means a common form of incorrect reasoning.
* We've also discussed on how to  determine wheter an argument is valid and the conclusion is true.
* Lastly, we prove the table known as ***Rules of Inference*** table to be a valid argument and with true conclusion.

###WEEK 4 Day 1 (February 02, 2016 Wednesday)

*  Today we continue our discussion about Rules of Inference to Build Arguments.
*  We've identified the characteristic of a biconditional statement using the conditional statement.
*  We've also solved a connected arguments and solving it using inference, at first, the process is difficult to understand yet after understanding the process we have identified wheter the argument is valid or not using logical expression.
*  We have also proven that SUPERMAN DOES NOT EXIST.
*  Lastly we have tackled about ***proof***. We've practice proof using direct proof method.

##WEEK 5 Day 2 (February 17, 2016 Wednesday)

* Today We've continued our discussion about proof and today we've tackled about proof using contrapositive and proof by Equivalence or Biconditionals.
* I've learned that to use contrapositive proof, it is not just making the statement into it's negation. It is important to consider the complete argument and much esiear to find it's equivalent contradiction if the argument will be stated using logical equation.
* To prove an argument using contradiction, at least one of it's statement or rule will be violated so that the argument ill be proven to be true.

##WEEK 6 Day 1 (February 22, 2016 Monday)

* Today we've discussed about Mathematical induction in which is the last topic for the upcoming quiz 1.
* Induction is prooving an argument using the properties in which the argument is to be proven.
* It uses two steps of proving, the first is the Basis step in which we prove that the sequence proposition is valid to be proven and next step is called Inductive Step.
* Recursive or Inductive Definition on the the other hand follows the same idea as the first mentioned, the only difference is the second step in which is calle recursive step.


##WEEK 7 Day 1 (February 29, 2016 Monday)

* Today We have studied about Set Theories.
* We've discuused and recall the terms and concepts from algebra such as: union, intersection, set difference and symmetric difference.
* Below is the table for the theories and their corresponding mathematical equations.

|**Theory**|**Representation**|**Description**|**Mathematical Equation**|**Example**|
|:-------:|:-------:|:-------:|:-------:|:-------:|
|UNION|A ∪ B|objects that belong to set A or set B|A ∪ B = {x | (x∈A) v (x∈B)}|A3,7,9,14,28}|
|INTERSECTION|A ∩ B|objects that belong to set A or set B|A ∩ B = {x | (x∈A) ^ (x∈B)}|
|SET DIFFERENCE|A - B or A \ B|objects that belong to A and not to B	|A - B = {x | (x∈A) ^ (x∉B)}|
|SYMMETRIC DIFFERENCE|A∆B|objects that belong to A or B but not to their intersection	|A ∆ B = {x | ((x∈A) ^ (x∉B)) v ((x∈B) ^ (x∉A))}

##WEEK 7 Day 2 (March 02, 2016 Wednesday)
 
 * Today We have discussed about Sets.
 * We differentiate the difference among domain, co-domain and range.
 * It is quite tricky to understand for it can be be used in so many ways. The usual tricky questions of the professor is really helpful to understand deeply the topic yet reading is really needed to cope-up with the failed grade last quiz.
 * Also, we have studied the one to one, onto and one to one correspondent and how they differ from each other.


##WEEK 8 Day 1 ( March 07, 2016 Monday)

  * Today we have discussed about the tricky and challeging algorithm. I have learned that algorithm is dettailed sensitive in which you are creating an argument through codes. As of now we covered up the searching algorithm and finding the max value in a search. Reading is essential to learn this hard topic but I think practice is much more needed. On the other hand, we are expected to submit the app project next meeting and so far, the process of making it is fun and full of neew knowledge.
