About
-----
RivGraph is a python package that provides tools for converting a binary mask of a channel network into a graph (i.e. a set of connected links and nodes). One major component of RivGraph is its ability to automatically set flow directions in each link of the network. It also computes morphologic metrics (lengths, widths, branching angles, etc.) and topologic metrics. RivGraph also contains a smattering of other tools and features, including some functions for helping clean and prepare your binary mask.

As of 5/26/2020, we are working on buttoning down RivGraph, including documentation, examples, and packaging. Please check back soon, and feel free to interact by opening an issue or emailing j........k@gmail.com. Now is a good time to add feature requests!

Installing
-----
RivGraph v0.2 is hosted on the anaconda channel [jschwenk](https://anaconda.org/jschwenk/rivgraph). We recommend installing into a fresh conda environment to minimize the risk of dependency clashes.
    test

Use RivGraph by creating either a delta or a river class, then applying the associated methods. As there is no documentation as of now, you will have to play with it and dig through the code a bit to understand how to use it. The rivgraph.py file contains these classes, as well as their methods, and should be a great starting place.

8/6/2019 - RivGraph is being prepared for "official release." The code is up-to-date, but has not been cleaned, commented, or sufficiently documented. There is currently [one example](https://github.com/jonschwenk/RivGraph/blob/master/examples/delta_example.py.ipynb) that should get you started; more are underway. 

3/29/2020 - Task list
- [x] [Delta example](https://github.com/jonschwenk/RivGraph/blob/master/examples/delta_example.py.ipynb)
- [ ] Braided river example
- [ ] How to prepare masks for inputs
- [ ] Where to get masks
- [ ] How to draw shorelines
- [ ] How to fix flow directions
- [ ] Function documentation
- [ ] Unit testing - in progress (5/11/2020)
- [ ] Function for removing artificial nodes
- [x] Conda Packaging - Update 5/25/2020: see anaconda.org/jschwenk/rivgraph

For examples of what RivGraph does, see this AGU poster: https://www.researchgate.net/publication/329845073_Automatic_Extraction_of_Channel_Network_Topology_RivGraph

For description of the flow directionality algorithms, see this paper: https://www.earth-surf-dynam.net/8/87/2020/esurf-8-87-2020.html.

If you have questions, contact me at j.....k@gmail.com

RivGraph has been assigned number C19049 by the Feynman Center for Innovation.
