# Predator-Prey
- Implements a Predator-Prey, Activator-Inhibitor System with an iterated function. (NOTE: it is reasonable to work with real values (type double)).
- User has to find a set of starting conditions for x(0) and y(0) and a set of parameters a, b, c, d, e, f that will yield an almost stable oscillation.
- Equation for temporal development of predator(y) and prey(x) with no interaction between them(i.e absence of predation)
  - x(i + 1) = x(i) + a ∗ x(i) + b ∗ y(i) + e ∗ x(i) ∗ x(i)
  - y(i + 1) = y(i) + c ∗ x(i) + d ∗ y(i) + f ∗ y(i) ∗ y(i)
- Equation for temporal development of predator(y) and prey(x) with interaction between them(i.e presence of predation) 
  - x(i + 1) = x(i) + a ∗ x(i) + b ∗ y(i) + e ∗ x(i) ∗ x(i) + g ∗ x(i) ∗ y(i)
  - y(i + 1) = y(i) + c ∗ x(i) + d ∗ y(i) + f ∗ y(i) ∗ y(i) + h ∗ x(i) ∗ y(i)

