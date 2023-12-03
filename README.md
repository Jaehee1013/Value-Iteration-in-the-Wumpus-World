# Value-Iteration-in-the-Wumpus-World
In this problem, we focus on applying Markov Decision Processes (MDPs) and the Value Iteration algorithm to the Wumpus World scenario. The objective is to implement two functions, MDP_value_iteration() and MDP_policy(), for a 4x4 grid Wumpus World. The goal is to control the agent within this environment and achieve specific objectives.

There are three settings for each of the following parameter combinations of temperature 𝑇, epochs 𝑒, and decay ratio 𝑑 to observe and analyze the outcome over the change in temperature.

To analyze the algorithm's behavior under different settings, the program is ran for each of the specified parameter combinations, then outputs utilities and policy.

Setting I: 𝛾 = 0.3, 𝜂 = 0.1, 𝑒 = 10000

Setting II: 𝛾 = 0.6, 𝜂 = 0.1, 𝑒 = 10000

Setting III: 𝛾 = 0.9, 𝜂 = 0.1, 𝑒 = 10000

The following is the observed utilities and policies for each setting

Setting I: 
Utilities and Policy for the Given Wumpus World:
-0.38 → | 0.23 → | 2.76 → | 13.24 → |

-0.52 → | -0.35 → | 0.32 ↑ | 2.86 ↑ |

-0.57 ↑ | -0.66 ↑ | -4.95 ↑ | 0.13 ↑ |

-0.56 ← | -10.17 ← | -5.16 → | -0.41 → |

Setting II: 
Utilities and Policy for the Given Wumpus World:
1.91 → | 4.55 → | 9.86 → | 20.58 → |

0.78 → | 2.30 → | 5.06 ↑ | 10.37 ↑ |

-0.03 ↑ | 0.53 ↑ | -2.30 ↑ | 4.68 ↑ |

-0.25 ↓ | -9.58 ↓ | -5.05 → | 1.61 ↑ |

Setting III: 
Utilities and Policy for the Given Wumpus World:
40.16 → | 46.89 → | 55.51 → | 66.63 → |

36.41 → | 42.24 → | 48.96 → | 57.02 ↑ |

31.90 → | 36.19 ↑ | 37.77 ↑ | 48.32 ↑ |

33.90 ↓ | 24.61 ↓ | 27.96 ↑ | 40.46 ↑ |
