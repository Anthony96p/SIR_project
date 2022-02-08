# SIR Euler's method - projectR
Classic SIR Model + vaccination + mortality


# Authors
Anthony PRAGASSAM & Aimen CHERIF

# Content

A simple mathematical description of the spread of a disease in a population is the so-called SIR model, which divides the (fixed) population of N individuals into three "compartments" which may vary as a function of time, t :
<br>

<b>S(t)</b>: are those susceptible but not yet infected with the disease
<br>
<b>I(t)</b> : is the number of infectious individuals
<br>
<b>R(t)</b> : are those individuals who have recovered from the disease and now have immunity to it.
<br>
The SIR model describes the change in the population of each of these compartments in terms of two parameters, β and γ. 
<br>
β describes the effective contact rate of the disease: an infected individual comes into contact with βN other individuals per unit time (of which the fraction that are susceptible to contracting the disease is S/N). γ is the mean recovery rate: that is, 1/γ is the mean period of time during which an infected individual can pass it on.
