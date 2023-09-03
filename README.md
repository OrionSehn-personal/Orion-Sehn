<img width="215" alt="image" src="https://github.com/OrionSehn-personal/website/assets/46799775/bb437f36-b368-4d19-9d0e-91e418e1ada3">

## About Me
I'm a guy who likes to make bad jokes!

I am also interested in Computational Geometry, aperiodic tilings, pathing algorithms, and DevOps. I currently work for PCL construction as a Data Scientist. My current work focuses on doing graph visualization and path optimization, azure cloud parallelization (Azure Batch), and other fun stuff. 

This is a little place where I can make my projects available. 
<!-- > I'll likely remake this in a more professional format down the road. -->

## Contact Me
- Email: orion.sehn@gmail.com
- github: [https://github.com/OrionSehn-personal](https://github.com/OrionSehn-personal)

## Projects - Things I've made

### Anytime Dynamic A* - An Anytime Dynamic Planning Algorithm implemented for NetworkX - 2023
<img width = 525 alt="image" src="https://github.com/OrionSehn-personal/blog/assets/46799775/4ebb7b24-91d8-4a2b-a927-9e7b9fd43d7f">

> This algorithm returns a path from a start state to a goal state. The algorithm is able to return a suboptimal path in a short amount of time. The algorithm is able to iteratively improve the path over time by calling the compute_or_improve_path method. The algorithm is also able to cope with dynamic environments by calling the update_graph function, which updates the graph with new weights. The algorithm makes use of previous work done when there are changes to the graph.
> Based on the work completed in this paper:
>
> [1] Likhachev, Maxim, David I. Ferguson, Geoffrey J. Gordon, Anthony Stentz, and Sebastian Thrun. "Anytime dynamic A*: An anytime, replanning algorithm." In ICAPS, vol. 5, pp. 262-271. 2005.
>
> Source Code: [https://github.com/OrionSehn-personal/networkx/blob/ada_star/networkx/algorithms/shortest_paths/ada_star.py](https://github.com/OrionSehn-personal/networkx/blob/ada_star/networkx/algorithms/shortest_paths/ada_star.py)
> 
> Collaborators:
> - NetworkX - [https://networkx.org/](https://networkx.org/) 
> - Dan Schult - dschult@colgate.edu
> - Brian Gue - BMgue@pcl.com

### Aperiodic Jigsaw Puzzle Generation and Edge Uniqueness Optimization - 2022
<img width=300 alt="image" src="https://github.com/OrionSehn-personal/website/assets/46799775/f287fecb-72c0-42be-bf33-e529b87a999c">
<img width="430" alt="image" src="https://github.com/OrionSehn-personal/Orion-Sehn/assets/46799775/31604347-b5e7-4e01-8416-69503057d8c1">

> This is a study on generating puzzle piece edges as a set of Bezier Curves, parameterizing their shape as an 18 dimensional vector with each component between 0 and 1. The challenge was to maximize the uniqueness of each of these edges by choosing these components to be as different as possible from the rest of the puzzle piece edges. The algorithm is applied to generate puzzles of different types of tiling, square, triangular, and Penrose, although in theory, it could be applied to any set of lines. 
> 
> Website: [https://orionsehn-personal-aperiodicpuzzle-puzzlesite-yy40ro.streamlit.app/](https://orionsehn-personal-aperiodicpuzzle-puzzlesite-yy40ro.streamlit.app/)
> 
> Source Code: [https://github.com/OrionSehn-personal/AperiodicPuzzle](https://github.com/OrionSehn-personal/AperiodicPuzzle)
> 
> Collaborators: 
> - Chris Ramsey - ramseyc5@macewan.ca
> - Adam Humeniuk - ahumeniuk@mtroyal.ca



### Guide to Parallelizing Legacy Applications using Containerization and Azure Batch - 2022
<img width="400" alt="image" src="https://github.com/OrionSehn-personal/Orion-Sehn/assets/46799775/8fe8df83-2c87-4871-ba32-7c45c55719b4">

> A guide to using Microsoft's Azure Batch to parallelize an arbitrary executable, using Docker Containers. This is a cloud computing architecture which enables users to spin up many virtual machines to complete many small tasks over many computers thereby amassing far more computing power than any single device could manage.
> 
> Link: [https://orionsehn-personal.github.io/BatchGuide/](https://orionsehn-personal.github.io/BatchGuide/)
> 
> Collaborators:
> - Brian Gue - BMgue@pcl.com

### One-Dim Substitution Tiling Visualization and Diffraction - 2020
<img width="420" alt="image" src="https://github.com/OrionSehn-personal/blog/assets/46799775/beab5c55-adda-4eff-a263-988424274447">

<img width="520" alt="image" src="https://github.com/OrionSehn-personal/blog/assets/46799775/d91d11f6-9f6f-440f-bbed-4a0bfedbdf17">

> This is a tool used for visualizing one dimensional substitution tilings. The user can define a substitution, and its first few iterations will be displayed as a segment diagram. Also included is the diffraction intensity function and the diffraction pattern of the tiling. Additional key elements of the tiling is also such as the Perron-Frobenius eigenvector, and if the subsitution is pisot.
> 
> Website: [https://funmaster524-1-dimsubstitutionviewer-streamlit-sub-sx3uuu.streamlit.app/](https://funmaster524-1-dimsubstitutionviewer-streamlit-sub-sx3uuu.streamlit.app/)
> 
> Source Code: [https://github.com/OrionSehn-personal/1-dimSubstitutionViewer](https://github.com/OrionSehn-personal/1-dimSubstitutionViewer)
> 
> Collaborators: 
> - Nicolae Strungaru - strungarun@macewan.ca
> - Chris Ramsey - ramseyc5@macewan.ca
