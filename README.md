# Bayes_Rule
This programming excercise displays how to program bayes rule given three inputs.

Bayes' rule can be described as a way to improve a prior belief by incorporating observed data, related to this belief (like test data or sensor measurements). The rule is written as:
$$P(A|B) = \frac{P(B|A)\cdot P(A)} {P(B)}$$

Where A is the event and B is some observed, related data.

In this next quiz, given only three probabilities: p_A, p_B_given_A, and p_notB_given_notA, which can be written in notation as:
$$P(A), P(B|A)$$

$$P(\neg B|\neg A)$$

You will be asked to write a function to calculate the posterior probability $$P(A|B)$$
