Noshland
========

a toy world for artificial life explorations

Noshland is a flatland with terrain, animals called smorgs, and plants called nosh.

Smorgs are seven-pointed star-like animals. Each star point has an internal spoke, which runs from the smorg's hub to the end of the point. Each spoke is divided into an inner spoke and an outer spoke. The inner spoke and outer spoke are always colinear, but each of them is an independent damped spring/muscle. The connection between a point's inner spoke and outer spoke is called a knee. Another damped spring/muscle, called a shin, runs straight from each knee to each adjacent knee. The shin's connection point to the knee is hinged so the shin's angle with the spoke changes freely.

A smorg has a nose on the end of each point, and an eye in the middle of each shin. It eats the fruit of a nosh, by absorbing nutrients from any nosh fruit it stays in contact with. It needs to eat the right amount -- neither undereating nor overeating is good. It can sense its current level of hunger/fullness. A smorg can see and smell nosh fruit and other smorgs. It can stay in contact with a nosh fruit either by standing in it or by holding it on an upward-facing shin.

A nosh is more like a tree. It gains nutrients from dead smorgs on the nearby ground. It does best at a certain level of nutrition, and becomes less productive or even dies from insufficient or excess nutrition.

From time to time, a nosh begins growing a nosh fruit at the end of a branch. The fruit grows until it breaks a limb, and then falls.
