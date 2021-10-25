# entity-gym

Prototype for an abstraction over reinforcement learning environments based around representing observations as lists of structured objects.
The interface is defined in [entity_gym/environment.py](https://github.com/cswinter/entity-gym/blob/main/entity_gym/environment.py).
A number of simple example environments can be found in [entity_gym/envs](https://github.com/cswinter/entity-gym/tree/main/entity_gym/envs).
The example environments can be run with `python entity_gym/main.py --env=MoveToOrigin|CherryPick|PickMatchingBalls|Minefield`.