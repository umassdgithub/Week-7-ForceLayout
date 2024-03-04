# Week-7 Network Visualization and ForceLayout

### Data Processing with NetworkX
NetworkX is a Python Library which provides a wide verity of tools for conversion of the data into
networks, manipulation, analysis or overview of them.

Here is a Colab link which in few quick steps shows, how you can convert a Pandas Dataframe 
into a networkX object, and then export it to a json file, so that you can load it using 
D3JS: 
<a href="https://colab.research.google.com/drive/11MWCWy1dcYUAE4nqZUxPGLKyaVtoNDlM">Colab Python Code</a>


### forceSimulation Examples

#### Step by Step forceSimulation
Check the examples in the step by step forceSimulation for the explanation and use each one of the forceLayout components.
- Step 1: Tick counter
- Step 2: Collide force
- Step 3: Center
- Step 4: forceX and forceY
- Step 5: Manybody
- Step 6: Links
- Distribution Generator

#### Examples

 1. Example 7.1: Sample data using d3.range() function
    1. x: d3.forceX()
    2. y: d3.forceY()
    3. collide: d3.forceCollide()
    
 2. Example 7.2: Nodes and Links in Strongly Connected Network 
    1. link: d3.forceLink()
    2. charge: d3.forceManyBody()
    3. collide: d3.forceCollide()
    
 3. Example 7.3: Making a function to load network using
    1. link: d3.forceLink()
    2. charge: d3.forceManyBody()
    3. collide: d3.forceCollide()
4. Example 7.4: Applying strength and distance
5. Example 7.5: Applying zoom interaction
6. Example 7.6: Pan and Zoom
7. Example 7.7: Grouping and Mouse interaction (hide and show groups)

<img src="img/Exampl_8.7.gif" width="400px">

8. Example 7.8:
   1. Matrix View of the Migration between U.S. States
   2. User Interaction  

<img src="img/Example_8.8.gif" width="400px">


For more examples:<br>
<a href="https://github.com/d3/d3-force">
https://github.com/d3/d3-force
</a>
<br>
<b>Great Source to test each one of the forces in d3 forceSimulation 
<a href="https://bl.ocks.org/steveharoz/8c3e2524079a8c440df60c1ab72b5d03">d3-force testing ground</a>
<br>
<a href="https://observablehq.com/@d3/force-directed-graph?collection=@d3/charts">
https://observablehq.com/@d3/force-directed-graph?collection=@d3/charts
</a>
<br>
https://www.d3indepth.com/force-layout/
