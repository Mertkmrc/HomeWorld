Text Based Game with Deep Reinforcement Learning Application.

HomeWorld

The actions taken by the player are multi-word natural language commands such as eat apple or go east . In this project we limit ourselves to consider commands consisting of one action (e.g., eat ) and one argument object (e.g. apple ).

The world consists of four rooms- a living room, a bed room, a kitchen and a garden with connecting pathways (illustrated in figure below). Transitions between the rooms are deterministic. Each room contains a representative object that the player can interact with. For instance, the living room has a TV that the player can watch , and the kitchen has an apple that the player can eat. Each room has several descriptions, invoked randomly on each visit by the player.

At the beginning of each episode, the player is placed at a random room and provided with a randomly selected quest. An example of a quest given to the player in text is You are hungry now. To complete this quest, the player has to navigate through the house to reach the kitchen and eat the apple (i.e., type in command eat apple). In this game, the room is hidden from the player, who only receives a description of the underlying room.
