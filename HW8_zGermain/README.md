![Plot of Asteroids](https://github.com/ZachGermain/DSPS_zgermain/blob/master/HW8_zGermain/eaAlbedoAst.png)

This figure is a plot of asteroids in the inner, main, and outer asteroid belts as defined by the JPL Small Database Search Engine and the entirety lies between the orbits of Mars and Jupiter. In the plot they are marked to lie between the red ticks on the horizontal axis. From left to right, the inner belt is defined as the asteroids with a semi-major axis(a) less than 2.0 astronomical units and having a perihelion greater than 1.666 AU; the Main Belt asteroids are those with 2.0<a<3.2 AU; the outer being those with 3.2<a<4.6 AU. There are orange ticks marking the integral resonances of asteroid to Jupiter orbital periods. These are, left to right: 2.06 AU with a 4:1 resonance, 2.5 AU and 3:1, 2.82 AU and 5:2, and the 2:1 resonance at 3.28 AU. These integral resonances are called Kirkwood Gaps in which the resonances lead to unstable orbits so the asteroids are "pushed out" of orbits that have these orbital periods. 

The data is taken from [The JPL Small Body Database](https://ssd.jpl.nasa.gov/sbdb_query.cgi#x). In order to get the same data, choose Asteroids from Object Kind, from Orbit Class choose Inner Belt Asteroid, Main-Belt Asteroid, and Outer Belt Asteroid; from Limit by object characteristics choose a (au), a-sigma (au), e, albedo, and e-sigma to be defined; from Object Field choose object ID and albedo have it sort as ascending; from Orbital and Parameter Fields choose a (au), a-sigma (au), e, and e-sigma; and choose the Table Format as CSV.


# FBB
Good plot, interesting data choice

This kind of plot that has high density regions may benefit from this style plot https://www.astroml.org/book_figures/chapter1/fig_S82_scatter_contour.html
