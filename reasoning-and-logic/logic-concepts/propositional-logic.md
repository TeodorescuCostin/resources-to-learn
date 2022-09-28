# Propositional Logic

Among the fundamental elements of thought, and therefore of logic, are proposition. Propositions helps us to translate the problems from natural language (English) to more specific circuits that can be implemented in our digital systems.

A proposition is a statement that can have truth values. It is either true o false. Some examples that do not enter in this category are questions or commands. This happens because propositions need to be true or false.

Some examples of good propositions are:

* 2 + 2 = 4  ( value: True )
* The sky is blue. ( value: True )
* Unicorns exist. ( value: False )

Some examples of bad propositions are:

* How are you? ( this is a question )
* Get me a drink. ( this is a command )

In English propositions are expressed as sentences. A simple sentence would look like "Amsterdam is a city." where this simple sentence has a subject and a predicate. The sentence is saying something about its subject, "Amsterdam". That something is called a predicate in our case. The predicate is the phrase "is a city".&#x20;

After we have a good understanding about the propositions and how they work we can start using quantifiers. Some examples of quantifiers are: "all", "some" and "no".

Some examples of propositions that use quantifiers are:

* All cities have a school.
* Some cities have a gym.
* No cities have an industrial factory.

Logical deduction usually deals with quantified statements.

### Propositions

Propositional logic is one of the easiest, but also has limited expressive power. Although it is limited it is enough to satisfy our needs.&#x20;

Since this is mathematics we will use lower case letters to represent our propositions. In most of the cases we will use <mark style="color:red;">p</mark>, <mark style="color:red;">q</mark> and <mark style="color:red;">r</mark> this three are going to be our main propositional variables. In most of our cases we will take the propositions as general values, they can take the value true or false, and it will be introduced like: "Let <mark style="color:red;">p</mark> be a proposition".  For more complex cases where we will have compound propositions we will use capital letters so that we know the difference.

The propositions are going to be connected with logical operators, also refered as logical connectives. A logical operator can be applied to one or to multiple propositions to produce a new one. In English, logical operators are represented by words such as:

* AND
* OR
* NOT
* etc.

An example of a proposition that contains two other propositions connected by one logical operator is:

* I eat pasta and Mary sings a song.

This proposition is formed in natural language, and if we break it up we can see that it is formed by two other propositions "I eat pasta" plus "Mary sings a song" where the logical operator is "and".

Let <mark style="color:red;">p</mark> and <mark style="color:red;">q</mark> be propositions. The logical connectors  "and", "or" and "not" are going to be represented like this:

* p<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">q
  * The "and" connector is true when both propositions are true.
* p<img src="../../.gitbook/assets/OR.png" alt="" data-size="line">q
  * The "or" connector is true when one of the propositions is true.
* <img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">p
  * The "not" connector is true when the proposition <mark style="color:red;">p</mark> is false.

The operators <img src="../../.gitbook/assets/AND.png" alt="" data-size="line">, <img src="../../.gitbook/assets/OR.png" alt="" data-size="line">and <img src="../../.gitbook/assets/NOT.png" alt="" data-size="line"> are referred as <mark style="color:red;">conjunction</mark>, <mark style="color:red;">disjunction</mark> and <mark style="color:red;">negation</mark>.



In logic operators can be used in more complicated expressions, such as p<img src="../../.gitbook/assets/AND.png" alt="" data-size="line"><img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">q<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">p<img src="../../.gitbook/assets/OR.png" alt="" data-size="line">r.

Just like in mathematics, parentheses can be used in compound expressions to indicate the order in which the operators are to be evaluated. In logic this concept is also called WFF (Well Formed Formula). In the absence of parentheses, the order of evaluation is determined by precedence rules. For the logical operators presented until now the order is the next one:

* <img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">has the highest value
* <img src="../../.gitbook/assets/AND.png" alt="" data-size="line">
* <img src="../../.gitbook/assets/OR.png" alt="" data-size="line">

This means that in the absence of parentheses the operators are going to be evaluated in this order. If there aren't any operators of one kind we can simply jump to next operator.



In logic as in mathematics we can encounter the term equivalence, here it refers to the result of the proposition(s). For example in some cases multiple propositions or compound propositions can be equivalent. Here how it wold look:&#x20;

* <img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">(p<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">q)<img src="../../.gitbook/assets/EQUIVALENT.png" alt="" data-size="line"><img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">p<img src="../../.gitbook/assets/OR.png" alt="" data-size="line"><img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">q

&#x20;The <img src="../../.gitbook/assets/EQUIVALENT.png" alt="" data-size="line">represents the word equivalent so that we can say two propositions are equivalent. In our example the statement is true due to the fact that we just introduced the negation in parentheses.

One way to discover if two propositions are equivalent is through  a truth table. A truth table is a table where we take all the possible values for our propositions and we apply the logical operators until we get to the final operator.

The most efficient way to find how many rows does your truth table has is to count the number of propositions and after that to put it as a power of 2. This is because we only have two options for every propostion (true or false). In logic we will represent truth values through binary numbers. We will represent the truth value as 1 and the false value as 0. Let's say we will take 3 propositions in our compound formula and that will mean our truth table will have $$2^3 = 8$$ rows.

Let's take an example of a truth table:

This truth table will be made for the next compound proposition p<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">q which will be equivalent to the letter x, so p<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">q<img src="../../.gitbook/assets/EQUIVALENT.png" alt="" data-size="line"> x .

| p | q | x |
| - | - | - |
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

Usually we say that two propositions are equivalent if the truth table return the same values. So for any proposition that we are not sure if it is equivalent with other proposition we can do the truth table.

Besides the logical operators presented until now we also have other operators like "conditional operator", "biconditional operator" and "exclusive or operator".

To have a better understanding about this operators we can do their truth tables:

* For conditional operator ( p<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">q )the truth table looks like this:

| p | q | p -> q |
| - | - | ------ |
| 0 | 0 | 1      |
| 0 | 1 | 1      |
| 1 | 0 | 0      |
| 1 | 1 | 1      |

The conditional operator is basically implication (actually this is the other way you can name the conditional oerator). Overall the single case when the truth table gives the value false is when proposition one is true but proposition two is false.

* For biconditional operator ( p<img src="../../.gitbook/assets/BICONDITIONAL.png" alt="" data-size="line">q )the truth table looks like this:

| p | q | p <-> q |
| - | - | ------- |
| 0 | 0 | 1       |
| 0 | 1 | 0       |
| 1 | 0 | 0       |
| 1 | 1 | 1       |

The biconditional operator is true in only true cases, basically only when both values have the same truth. So only when both are true or when both are false.

* For exclusive or operator ( p<img src="../../.gitbook/assets/XOR.png" alt="" data-size="line">q )the truth table looks like this:

| p | q | p (+) q |
| - | - | ------- |
| 0 | 0 | 0       |
| 0 | 1 | 1       |
| 1 | 0 | 1       |
| 1 | 1 | 0       |

The exclusive or operator (also named as xor) is true only one of the propositions is true but if both are true it will have the value false because it is exclusive, not as it is the operator or where it doesn't matter if both values are true.

Let's make a summary about the operators that wear in our subject of discussion:

* Negation (not operator with the symbol <img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">)
  * This logical operator has propoerty that reverses the value of the proposition
* Conjunction (and operator with the symbol <img src="../../.gitbook/assets/AND.png" alt="" data-size="line">)
  * This logical operator accepts only two true propositions so that it returns true otherwise is false
* Disjunction (or operator with the symbol <img src="../../.gitbook/assets/OR.png" alt="" data-size="line">)
  * This logical operator accepts two value where at least one of them needs to be true
* Conditional (implies operator with the symbol <img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">)
  * This logical operator is also "if p then q" in natural language (English)
* Biconditional (with the symbol <img src="../../.gitbook/assets/BICONDITIONAL.png" alt="" data-size="line">)
  * This logical operator is also "p if and only if q" in natural language (English)
* Exclusive Or (xor operator with the symbol <img src="../../.gitbook/assets/XOR.png" alt="" data-size="line">)
  * This logical operator is also "p or q, but not both" in natural language (English)



There are other forms of implication, for example the implication <img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">q<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line"><img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">p is called contrapositive. Every implication is locally equivalent to its contrapositive.

Another form of implication is the converse, which is actually q<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">p. This implication is called the converse form of the equation p<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">q.

The last form is called the inverse, this implication looks like <img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">p<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line"><img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">q.

The biconditional operator is closely related to the conditional operator. Actually this operator is equivalent to (p<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">q)<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">(q<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">p). So overall we can conclude that  (p<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">q)<img src="../../.gitbook/assets/EQUIVALENT.png" alt="" data-size="line">(p<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">q)<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">(q<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">p).

Concluding the part that contains logical operators I would say that most of the operators can be substituted by only two operators, for example most of the operators can be substituted by {<img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">, <img src="../../.gitbook/assets/AND.png" alt="" data-size="line">} or by this set {<img src="../../.gitbook/assets/NOT.png" alt="" data-size="line">, <img src="../../.gitbook/assets/OR.png" alt="" data-size="line">}. Both of the set mentioned are called functionally complete due to the fact that they can express al of the other operations.

#### Definition

A set of logical operator can be called functionally complete only if all the formulas from the formula set can be rewritten with those.

&#x20;

In a truth table we can also encounter some different behaviours. For example we can see that our truth table has only ones ( 1 ) or only zeros ( 0 ) or neither. For each case we have a specific name. For example if our truth table has ony ones we will call that a tautology. Other case would be if our final table has only zeros, because that would be called a contradiction, and in this case also the name is very self explanatory. The final case is when we have a normal table that contains both truth and false values. In this case its name is contingency. Basically a contingency in neither a tautology or a contradiction.



