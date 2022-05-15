# Monsters
A netlogo model that simulates a war between humans and monsters with different strategies

## How To Use
To run this model, you just have to import it into netlogo and run it.

## What does it do?
This model has three different agents: students, soldiers and monsters. 
Each agent has a different behaviour and the idea is to see who wins in a Humans vs Monsters battle depending on different factors like:
  - number of agents
  - behaviour of monsters (clustering or solo hunt)
You can only control the behaviour of monsters, the behaviour of soldiers and humans are predefined.
Students walk randomly and runaway when a monsters is in their vision radius or get closer to soldiers when they are also in the vision radius.
Soldiers walk randomly until a monster is in tehir reach radius. In that case, the hunt starts and they keep fighting until one of them dies.
