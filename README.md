# Goal : The local stability of the 4-node star system(electricity producer is the centre) implemneting Decentralized smart grid system concept.

# Variable Information
11 predictive attributes, 1 non-predictive(p1), 2 goal fields:

tau[x]: reaction time of participant (real from the range [0.5,10]s). Tau1 - the value for electricity producer.
p[x]: nominal power consumed(negative)/produced(positive)(real). For consumers from the range [-0.5,-2]s^-2; p1 = abs(p2 + p3 + p4)
g[x]: coefficient (gamma) proportional to price elasticity (real from the range [0.05,1]s^-1). g1 - the value for electricity producer.
stab: the maximal real part of the characteristic equation root (if positive - the system is linearly unstable)(real)
stabf: the stability label of the system (categorical: stable/unstable)

# Models used(Classification)
* Random Forest Classifier
* Logistic regression
* Decison Tree classifier
* SVC model
* XGB Classifier
