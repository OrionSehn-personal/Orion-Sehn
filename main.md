# Orion Sehn
<img width="215" alt="image" src="https://github.com/OrionSehn-personal/website/assets/46799775/bb437f36-b368-4d19-9d0e-91e418e1ada3">

## About Me
I'm a guy who likes to make bad jokes!

I am also interested in Computational Geometry, aperiodic tilings, pathing algorithms, and DevOps. I currently work for PCL construction as a Data Scientist. My current work focuses on doing graph visualization and path optimization, azure cloud parallelization (Azure Batch), and other fun stuff. 

This is a little place where I can make my projects available. 
<!-- > I'll likely remake this in a more professional format down the road. -->

## Contact Me
- Email: orion.sehn@gmail.com
- github: https://github.com/OrionSehn-personal

## Projects - Things I've made

### Anytime Dynamic A* - An Anytime Dynamic Planning Algorithm implemented for NetworkX - 2022
<img width="550" alt="image" src="https://github.com/OrionSehn-personal/blog/assets/46799775/4ebb7b24-91d8-4a2b-a927-9e7b9fd43d7f">

> This algorithm returns a path from a start state to a goal state. The algorithm is able to return a suboptimal path in a short amount of time. The algorithm is able to iteratively improve the path over time by calling the compute_or_improve_path method. The algorithm is also able to cope with dynamic environments by calling the update_graph function, which updates the graph with new weights. The algorithm makes use of previous work done when there are changes to the graph.
> Based on the work completed in this paper:

> [1] Likhachev, Maxim, David I. Ferguson, Geoffrey J. Gordon, Anthony Stentz, and Sebastian Thrun. "Anytime dynamic A*: An anytime, replanning algorithm." In ICAPS, vol. 5, pp. 262-271. 2005.
> 
> Collaborators: 
> 

### Aperiodic Jigsaw Puzzle Generation and Edge Uniqueness Optimization - 2022
<img width="350" alt="image" src="https://github.com/OrionSehn-personal/website/assets/46799775/f287fecb-72c0-42be-bf33-e529b87a999c">
  
> This is a study on generating puzzle piece edges as a set of Bezier Curves, parameterizing their shape as an 18 dimensional vector with each component between 0 and 1. The challenge was to maximize the uniqueness of each of these edges by choosing these components to be as different as possible from the rest of the puzzle piece edges. The algorithm is applied to generate puzzles of different types of tiling, square, triangular, and Penrose, although in theory, it could be applied to any set of lines. 
> 
> Website: https://orionsehn-personal-aperiodicpuzzle-puzzlesite-yy40ro.streamlit.app/
> 
> Source Code: https://github.com/OrionSehn-personal/AperiodicPuzzle
> 
> Collaborators: 
> - Chris Ramsey - ramseyc5@macewan.ca
> - Adam Humeniuk - ahumeniuk@mtroyal.ca


### Guide to Parallelizing Legacy Applications using Containerization and Azure Batch - 2021
<img width="450" alt="image" src="https://github.com/OrionSehn-personal/blog/assets/46799775/4f1f7c13-a854-4018-afcc-8f0e966888e8">

>
> A guide to using Microsoft's Azure Batch to parallelize an arbitrary executable, using Docker Containers.
> 
> Link: https://orionsehn-personal.github.io/BatchGuide/
> 
> Collaborators: Bmgue@pcl.com

### One-Dim Substitution Tiling Visualization and Diffraction - 2020
<img width="450" alt="image" src="https://github.com/OrionSehn-personal/blog/assets/46799775/beab5c55-adda-4eff-a263-988424274447">

<img width="450" alt="image" src="https://github.com/OrionSehn-personal/blog/assets/46799775/d91d11f6-9f6f-440f-bbed-4a0bfedbdf17">

> This is a tool used for visualizing one dimensional substitution tilings. The user can define a substitution, and its first few iterations will be displayed as a segment diagram. Also included is the diffraction intensity function and the diffraction pattern of the tiling. Additional key elements of the tiling is also such as the Perron-Frobenius eigenvector, and if the subsitution is pisot.
> 
> Website: https://funmaster524-1-dimsubstitutionviewer-streamlit-sub-sx3uuu.streamlit.app/
> 
> Source Code: https://github.com/OrionSehn-personal/1-dimSubstitutionViewer
> 
> Collaborators: 
> - Nicolae Strungaru - strungarun@macewan.ca
> - Chris Ramsey - ramseyc5@macewan.ca
