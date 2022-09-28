# Deduction

In logic we can define a conlcussion from a set of premises. A premise would be a proposition in our case, or multiple propositions connected by a logical operator. For now we can just state that deductions are very similar with mathematical operations.

To have a better vision on our subject of discussion we can take an example. Let's take as propositions p, q and r.&#x20;

|                                   -                                  |                                   -                                   |  -  |
| :------------------------------------------------------------------: | :-------------------------------------------------------------------: | :-: |
|                                   p                                  | <img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line"> |  q  |
|                                   p                                  |                                                                       |     |
| <img src="../../.gitbook/assets/SOTHAT.png" alt="" data-size="line"> |                                   q                                   |     |

If this looks hard we can just take each line as a proposition and between each proposition we can put the logical operator <img src="../../.gitbook/assets/AND.png" alt="" data-size="line">plus between premises and the conclusion we would put the implication operator. The final result would look like this: ((p<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">q)<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">p)<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">q. We need to keep in mind that this final statement would need to be a tautology to be valid.

After this example we can see the uses of the operator so that (<img src="../../.gitbook/assets/SOTHAT.png" alt="" data-size="line">).

Sometimes doing a truth table is not the most efficient method, so another alternative would be to treat our deduction in another way.

Let's take another example more complex so that we can see the method:

Let's take the propositions p,q,r,s and t:

| -                                                                    | -                                                                     | - | -                                                                     |   |
| -------------------------------------------------------------------- | --------------------------------------------------------------------- | - | --------------------------------------------------------------------- | - |
| p                                                                    | <img src="../../.gitbook/assets/AND.png" alt="" data-size="line">     | r | <img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line"> | s |
| q                                                                    | <img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line"> | p |                                                                       |   |
| t                                                                    | <img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line"> | r |                                                                       |   |
| q                                                                    |                                                                       |   |                                                                       |   |
| t                                                                    |                                                                       |   |                                                                       |   |
| <img src="../../.gitbook/assets/SOTHAT.png" alt="" data-size="line"> | s                                                                     |   |                                                                       |   |

So first we know that <mark style="color:red;">t</mark> is true so that means <mark style="color:red;">r</mark> will be true, if not t<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">r will be false so <mark style="color:red;">r</mark> needs to be true. Another proposition that we already know that is true is <mark style="color:red;">q</mark>. From this assumption it will result that <mark style="color:red;">p</mark> is true, doing the same deduction as before. So until now we know that <mark style="color:red;">p</mark>, <mark style="color:red;">q</mark>, <mark style="color:red;">r</mark> and <mark style="color:red;">t</mark> are true. Now we can go to the first statement which states that (p<img src="../../.gitbook/assets/AND.png" alt="" data-size="line">r)<img src="../../.gitbook/assets/IMPLIES.png" alt="" data-size="line">s. From this statement we know that <mark style="color:red;">p</mark> and <mark style="color:red;">r</mark> are true so it will result <mark style="color:red;">s</mark> is true so our result will be <mark style="color:red;">s</mark>.

To prove a deduction is false we can simply find a counterexample. To disapprove the validity of an argument we should always provide a counterexample so that we can show the deduction do not hold.

