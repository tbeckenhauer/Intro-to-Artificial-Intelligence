Problem Set 2

1. Quiz Bayes Rule

Given the Bayes Network

(A) -> (B)

P(A) = 0.5
P(B|A) = 0.2
P(B|-A) = 0.8

Calculate P(A|B)

Solution
P(A|B) = ( P(B|A) * P(A) ) / P(B)                 - Bayes Rule
       = ( P(B|A) * P(A) ) / ( ( P(B|A) * P(A) ) + ( P(B|-A) * P(-A) ) ) - Total Probability
       = (  0.2   *  0.5 ) / (    0.2   *  0.5   +     0.8   *  0.5  )
       = 0.2

2. Quiz Simple Bayes Net

P(A|X1, X2, -X3)
= (P(A) * P(X1|A)* P(X2|A) * P(-X3|A)) / ( (P(A) * P(X1|A)* P(X2|A) * P(-X3|A)) + (P(-A) * P(X1|-A)* P(X2|-A) * P(-X3|-A)) )

= (0.5*0.2*0.2*0.8)/((0.5*0.2*0.2*0.8)+(0.5*0.8*0.8*0.4))

= 0.1111
