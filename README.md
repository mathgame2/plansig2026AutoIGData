# plansig2026AutoIGData

Each folder contains the discriminating instances found for each model. 

Each instance will have a folder containing: input files for the two solvers, the terminal output of AutoIG that includes the commands used to invoke the solvers, the generator instance parameters, and the instance parameter file.

There is a cvs file per model that lists the instances and the time taken for each solver to solve the instance.

## generator model overviews

The simple model parameterises # of rows, # of columns, and # of bots of an instance. All other factors are fixed.

The minimum distance model parameterises the minimum distance between the start and end locations of bots. This value is a percentage of the longest distance possible, which is opposite ends of the map.

The corridor model adds to the min distance model by parameterising the corridor size between shelves.

## paper

The paper can be found here: https://docs.google.com/uc?export=download&id=10RlAUxQohItHNaAuj3V-_9DcxiKlWJ3P.
