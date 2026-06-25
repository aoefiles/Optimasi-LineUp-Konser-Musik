# \# 🎵 Prambanan Jazz Festival 2026 Lineup Optimization Using Genetic Algorithm

# 

# A Genetic Algorithm-based optimization model for generating the most effective artist lineup arrangement across a multi-day music festival.

# 

# \## Overview

# 

# Music festival organizers face the challenge of arranging artist performances in a sequence that maximizes audience engagement while balancing artist popularity, performance energy, and strategic headliner placement.

# 

# This project applies a Genetic Algorithm (GA) to optimize the lineup schedule of Prambanan Jazz Festival 2026. The model evaluates thousands of possible lineup combinations and recommends the arrangement with the highest fitness score.

# 

# \## Problem Statement

# 

# Designing a concert lineup is not simply arranging artists in random order.

# 

# Organizers must consider:

# 

# \- Audience retention throughout the event

# \- Artist popularity levels

# \- Performance energy transitions

# \- Strategic headliner positioning

# \- Multi-day festival scheduling

# 

# Manual lineup planning is often subjective and may overlook optimal combinations. Therefore, an optimization-based approach is used to identify the best-performing lineup configuration.

# 

# \## Optimization Approach

# 

# The project implements a Genetic Algorithm consisting of:

# 

# 1\. Population Initialization

# 2\. Fitness Evaluation

# 3\. Tournament Selection

# 4\. Crossover

# 5\. Mutation

# 6\. Elitism

# 7\. Termination Criteria

# 

# Each chromosome represents a possible artist sequence for a particular festival day.

# 

# \## 📊 Dataset

# 

# The optimization model uses artist data from the Prambanan Jazz Festival 2026 lineup, including:

# 

# | Feature | Description |

# |----------|-------------|

# | Artist Name | Performer Name |

# | Popularity Score | Normalized popularity metric |

# | Monthly Listeners | Spotify monthly listeners (May 2026) |

# | Energy | Performance energy level |

# | Tempo | Average song tempo |

# | Headliner Status | Headliner or Non-Headliner |

# | Festival Day | Day 1, Day 2, or Day 3 |

# 

# The dataset is cleaned, validated, transformed, and partitioned by festival day before optimization. :contentReference\[oaicite:0]{index=0}

# 

# \## ⚙️ Fitness Function

# 

# The optimization objective combines three key performance indicators:

# 

# | Component | Weight |

# |-----------|---------:|

# | Energy Flow Score | 1.0 |

# | Popularity Placement Score | 5.0 |

# | Headliner Constraint | 2.0 |

# 

# Fitness Formula:

# 

# ```text

# Fitness =

# (1.0 × Energy Flow Score)

# \+ (5.0 × Popularity Placement Score)

# \+ (2.0 × Headliner Constraint)

# ```

# 

# The weighting scheme prioritizes artist popularity while maintaining smooth audience energy transitions and ensuring proper headliner placement. :contentReference\[oaicite:1]{index=1}

# 

# \## 🎤 Optimization Objectives

# 

# The Genetic Algorithm aims to:

# 

# \- Maximize audience engagement

# \- Improve lineup flow consistency

# \- Place headliners strategically

# \- Generate the best artist sequence for each festival day

# \- Produce data-driven lineup recommendations

# 

# \## 📈 Results

# 

# The model successfully generated optimized lineup recommendations for all festival days.

# 

# | Festival Day | Best Fitness Score |

# |-------------|------------------:|

# | Day 1 | 241.67 |

# | Day 2 | 221.94 |

# | Day 3 | 167.48 |

# 

# The highest-fitness chromosome from each day is selected as the recommended lineup arrangement. :contentReference\[oaicite:2]{index=2}

# 

# \## Tech Stack

# 

# \- Python

# \- Pandas

# \- NumPy

# \- Matplotlib

# \- Jupyter Notebook

# \- Genetic Algorithm

# 

# \## Business Value

# 

# This project demonstrates how optimization techniques can support decision-making in event management by:

# 

# \- Reducing subjective scheduling decisions

# \- Improving audience experience

# \- Supporting data-driven event planning

# \- Optimizing artist sequencing at scale

# 

# The approach can be adapted for music festivals, conferences, sports events, and other scheduling-intensive applications.

# 

# \## Future Improvements

# 

# \- Genre compatibility scoring

# \- Multi-objective optimization

# \- Audience preference integration

# \- Stage allocation optimization

# \- Interactive scheduling dashboard

# 

# \## 👤 Author

# 

# \*\*Firyal Aufa\*\*

# 

