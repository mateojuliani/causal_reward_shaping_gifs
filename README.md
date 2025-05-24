# causal_reward_shaping_gifs

## State 5 6 7 8 9 10 Removed 
In this test case, the hopper agent has no sense of its velocity measurements (both directional and angular)

Baseline: 
The baseline agent ends up learning a policy that is too aggressive, and consequently results in it falling over quickly.

![state_remove_1](stateremove5678910.gif)

Causal (Ours):
On the other hand, the causal agent learns a more conservative strategy, allowing it to hop for longer.
![causal_1](causal5678910.gif)

Non Causal:

![non_causal](non_causal_5678910.gif)

## State 1 Removed

Baseline: 

![state_remove_1](state_remove_1.gif)

Causal (Ours):

![causal_1](causal_1.gif)

Non-Causal:

![non_causal_1](non_causal_1.gif)


## State 7 Removed



Baseline: 

![state_remove_7](state_remove_7.gif)

Causal (Ours):

![causal_7](causal7.gif)

Non-Causal:

![non_causal_7](non_causal_7.gif)
