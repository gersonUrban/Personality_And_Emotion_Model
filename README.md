# Personality_And_Emotion_Model
This folder contains
  - An experiment table, that contens results of a sample of simulations
  - A MP_table, that indicates how personality influences in emotions
  - A UML of source code, demonstrating the source code construction for model generation
  - The graduation thesis text, where the model was proposed
  - And the source code as a java project
  
The source code contains 8 classes, being:
  - Ocean, where the necessary structure for the personality model is created
  - Occ, where the necessary structure for the emotion model is created
  - OCEANxOCC, where the MP are set
  - Mercadoria (merchandise), where the merchandise quantity is set
  - ModeloTroca (ChangeModel), here are created the functions that make possible to make exchanges between agents
  - Agente (Agent), Where agents are defined, initialized with their personalities and who will feel emotions and will suffer changes in personality weights
  - Emoções (Emotions), here is chosen an emotion for the agent
  - AtualizaOcean (UpdatesOCEAN), here is update the personality weights for the agent
  
  And the Main (MAS_OCC_OCEAN), where the parameters are set, such as number of executions, maximum number of days, quantity of agents, biological agent personality and environmental parameters.
