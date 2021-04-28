A distilation inspired classifier.

Creates classification stages (stacking) just like in a distilation setting.

higher/lower entropy predictions goes to next stage (estimator) while the others are predicted as is.

Kinda like a boosting algorithm, but the hard-to-classify examples are filtered out instead of having weights assigned to.

Another difference is that each inference is made by only one estimator (stage).

i'm messing arround and this project is strictly for fun.

god bless.
