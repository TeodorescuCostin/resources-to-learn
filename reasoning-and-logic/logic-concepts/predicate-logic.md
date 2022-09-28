# Predicate Logic

Compared with propositional logic, predicate logic is much more complex due to fact that let us to represent more generic proposition and logic statements. For example is propositional logic the proposition "The sky is blue" can be represented by the letter p and the proposition "Florian is cool" can be represented by letter q. If we are going to say " The sky is blue and Florian is cool" we will get something like p<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">q. This is very limited due to the fact that we can not say anything general about any of the propositions stated.

Predicates are a kind of propositions but they are actually incomplete, but they will become a proposition when they get attributed o an entity or to several entities. In the proposition "the sky is blue", the predicate is "is blue". I we do not attribute this will simply be a predicate but if we say "X is blue" this becomes a proposition. Now if we want to represent the proposition in logic we can say for example Blue(sky), which will be equivalent to "The sky is blue". Also we will se that in our journey we will see that we use shorter statements. Instead of using Blue(sky), we will just say B(s).&#x20;

The example stated wasn't that general, it would be much better to take an example that states a general proposition. Let's say that Q stands for out predicate and that x stands for our subject, so if  we know all of this information we can say Q(x). Usually the subject, in our case x, is also called entity. This happens because an entity is something general and not specific.

Some propositions can also have to predicates, in those cases we can simply say that every predicates has one logic value, like x and y. After our ground rules are clear we can use the predicate that is between them and say Predicate(x, y). In a more general case it look like P(x, y).



Now that we know how we should use predicates and subjects in propositions we can also create general statements with the help of the quantifiers. In logic we use quantifiers to show the complexity of our subject. For example we can have as a subject "x" after if we want to say "for all x" we can just simply say "<img src="../../.gitbook/assets/FORALL.png" alt="" data-size="line">x" which is the same thing. We also have the case where we would want to say "Exists at least one x" , but we can simply say "<img src="../../.gitbook/assets/EXISTS.png" alt="" data-size="line">x".&#x20;



In predicate logic we also have operators, so that we can connect the propositions to get another statement. So for example <img src="../../.gitbook/assets/EXISTS.png" alt="" data-size="line">x(Roses(x)<img src="../../.gitbook/assets/OR.png" alt="" data-size="line">Violets(x)) will also be valid due to the fact that respects all of our principles stated until now.

The proposition stated before would sound something like "Exists at least one x which is a rose or a violet.". We need to keep in mind that not every time the sentences will make sense.



Another exercise that we can meet in logic is Tarski's world. This is basically a graphical representation of multiple statements with which we can visualize how it would look. In Tarski's world it is possible to describe different situations.&#x20;

The best to explain this principle would be to take a general example:

In our example we will take the next statements:

* <img src="../../.gitbook/assets/FORALL.png" alt="" data-size="line">x(Square(x)<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line"><img src="../../.gitbook/assets/EXISTS.png" alt="" data-size="line">y( Circle(y)<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">LeftOf(x,y) )

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

This example can tranlate like "For all x that are squares, they are left of at least one circle"
