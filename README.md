# NASA-Asteroids-Classification

<h3> Data fields</h3>

Here's a brief version of columns in the Dataframe.

* **neo_reference_id** :  Near-Earth Objects(NEO) reference id for an Asteroid
* **name** :  Name of the Asteroid
* **absolute_magnitude_h** : Absolute Magnitude - A measure of the asteroid's luminosity (in H) (the brightness of an asteroid if it is 1 astronomical unit away from both the Sun and the observer, and the angle between the Sun, asteroid, and Earth is 0 degrees) 
* **est_dia_min/est_dia_max(in km, m, miles, feet)** : Minimum or maximum estimated diameter of the the Asteroid in respective units.(Since asteroids have irregular shapes, their diameters can only be estimated. These estimates are calculated using its absolute magnitude and geometric albedo.)
* **close_approach_date** : Date of closest Earth approach.
* **epoch_date_close_approach** : Date of closest Earth approach in epoch time.
*  **relative_velocity (km/s, km/h, miles/h)** : Asteroid's velocity relative to earth.
* **miss_distance(astronomical, lunar, km, miles)** : Distance by which the asteroid misses Earth.
* **orbiting_body** :
* **orbit_id** : ID of the JPL NEA orbit used in this analysis.
* **orbit_determination_date** : Date at which the asteroid's orbit was determined.
* **orbit_uncertainty** : Measure of uncertainty in each determined NEO orbit.
* **minimum_orbit_intersection** : Distance between the closest points of the osculating orbits of Earth and the asteroid.
* **jupiter_tisserand_invariant** : Used to differentiate between asteroids and Jupiter-family comets.
* **epoch_osculation** : The instant of time at which the asteroid position and velocity vectors are specified.
* **eccentricity** : A value which specifies by how much the asteroid's orbit deviates from a perfect circle.
* **semi_major_axis** : Longest radius of an elliptical orbit; measure of the asteroid's average distance from the Sun.
* **inclination** : Measures the tilt of the asteroid's orbit around the Sun.
* **ascending_node_longitude** : Angle from a specified reference direction, called the origin of longitude, to the direction of the ascending node.
* **orbital_period** : time taken for asteroid to complete one orbit around the sun.
* **perihelion_distance** : An asteroid orbit’s closest point to the Sun.
* **perihelion_argument** : Angle in the orbit plane between the ascending node and the perihelion point.
* **aphelion_distance** : An asteroid orbit’s farthest point to the Sun.
* **perihelion_time** : Length of time of asteroid's passage through the perihelion stage.
* **mean_anomaly** : The product of an orbiting body's mean motion and time past perihelion passage.
* **mean_motion** : The angular speed required for a body to make one orbit around an ideal ellipse with a specific semi-major axis.
* **equinox** : An astronomical standard to measure against.
* **hazardous** : Is the asteroid hazardous? or not?
