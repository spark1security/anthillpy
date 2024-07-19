# anthillpy
Hollow package to be used as an example on how to extend [n0s1](https://spark1.us/n0s1)

Full details about n0s1 at: https://github.com/spark1security/n0s1


## How to expand n0s1
Use the [anthill]( https://github.com/spark1security/n0s1/tree/anthill) branch from [n0s1](https://github.com/spark1security/n0s1/tree/anthill) repo as a starting point.
```commandline
git clone git@github.com:spark1security/n0s1.git
git checkout anthill
```
Search for all occurrences of anthill in the source code and replace by your new platform (e.g. Slack, Asana, Jira, etc)

The [n0s1/controllers/anthill_controller.py](https://github.com/spark1security/n0s1/blob/anthill/src/n0s1/controllers/anthill_controller.py) can be used as a template for your new extension.

 This package is included to n0s1's [requirements.txt](https://github.com/spark1security/n0s1/blob/anthill/requirements.txt#L7). Make sure to also replace the denpendecy "anthillpy" by the actual SDK you will be using.
