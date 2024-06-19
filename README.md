# pha-ml

# PHA detection ML project

## Feature Description

### H (absolute magnitude)

An asteroid’s absolute magnitude is the visual magnitude an observer would record if the asteroid were placed 1 Astronomical Unit (au) away, and 1 au from the Sun and at a zero phase angle.

The magnitude of an asteroid at zero phase angle and at unit heliocentric and geocentric distances.

### Diameter (diameter)

Diameter of Asteroids

### Albedo (albedo)

Albedo is ratio of the light received by a body to the light reflected by that body. Albedo values range from 0 (pitch black) to 1 (perfect reflector).

Geometric albedo is the ratio of a body’s brightness at zero phase angle to the brightness of a perfectly diffusing disk with the same position and apparent size as the body.

Our Moon has a very low albedo (0.07), while Venus has a high albedo (0.60). The albedo combined with the absolute magnitude can help determine the size of an asteroid.

### Rotation Period (rot_per)

Rotation period in hour

### Eccentricity (e)

One half of the major axis of the elliptical orbit; also the mean distance from the Sun.

### Semi-major axis (a)

One half of the major axis of the elliptical orbit; also the mean distance (au) from the Sun.

### Perihelion Distance (q)

An orbit’s closest point to the Sun. (au)

### Inclination Angle (i)

Angle between the orbit plane and the ecliptic plane.

### Period (per)

The time it takes an orbiting body to make one complete revolution around the Sun.

### Mean Motion (n)

In orbital mechanics, mean motion (represented by n) is the angular speed required for a body to complete one orbit, assuming constant speed in a circular orbit which completes in the same time as the variable speed, elliptical orbit of the actual body.

### Logitude of the ascending node (om)

The longitude of the ascending node indicates the angle between a fixed point of celestial longitude called the vernal point (or Vernal Equinox; arbitrarily the sun's point on the first day of Spring, symbolized as ♈ ) to the point on the asteroid orbit where it crosses upward through the ecliptic plane.

### Argument of perihilion (w)

The third and final orientation angle is the angle between the ascending node and the point where the orbit is closest to the Sun (known as perihelion), as seen from the Sun. It is called the argument of perihelion, ω. Another useful angle, known as the longitude of perihelion, , is defined to be ω + Ω.

### Mean anomaly (ma)

The mean anomaly is the angle between lines drawn from the Sun to the perihelion B and to a point (not shown) moving in the orbit at a uniform rate corresponding to the period of revolution of the planet.

### Aphelion Distance (ad)

An orbit’s farthest point to the Sun. 

The aphelion distance is equal to the semi-major axis, plus the distance from the centre of the elipse to one of the foci. That distance, c, is equal to the product between the semi-major axis and the eccentricity. Just take a look at an ellipse, and you’ll see the reasoning behind this equation; the sun is in that focus, and you need the distance between the centre and the aphelion.

Simply add c to a, where a is the semi-major axis, and your result will be a(1+e), where e is your eccentricity. The numerical result is 0.46625 AU.

### Minimum orbit intersection distance (moid_ld)

It is defined as the distance between the closest points of the osculating orbits of two bodies. Of greatest interest is the risk of a collision with Earth. Earth MOID is often listed on comet and asteroid databases such as the JPL Small-Body Database. (lunar distance)

### Data Loading Link
* https://dagshub.com/s.hossain18/Asteroid_ML/raw/66fe08e9b0c24c0064b649f6c61615708c72c312/Data/dataset.csv (Old Data)
* https://dagshub.com/mirsakhawathossain/Asteroid_ML/raw/513ae1bcedd3c4adb056180d7630bc9e09d0626e/Data/sbdb_query_results.csv (New Data)

## Preprocessed Dataset
Here we have solved missing value problem
### Features
* https://dagshub.com/mirsakhawathossain/Asteroid_ML/raw/bb5a025d7f22e50d9a4974d64ef76875431de947/Data/final_data.csv
### Target
* https://dagshub.com/mirsakhawathossain/Asteroid_ML/raw/bb5a025d7f22e50d9a4974d64ef76875431de947/Data/pha_map.csv


### KNN Imputer for Missing Values
* https://www.analyticsvidhya.com/blog/2020/07/knnimputer-a-robust-way-to-impute-missing-values-using-scikit-learn/

### Complex Metrics Analysis Libraries
* https://github.com/topics/complexity-measures (List of Github repos)
* https://github.com/w4k2/problexity
* https://github.com/miriamspsantos/pycol
* https://github.com/lpfgarcia/ECoL

## Decision Boundary Plotting
* https://scikit-learn.org/stable/auto_examples/tree/plot_iris_dtc.html
* https://hackernoon.com/how-to-plot-a-decision-boundary-for-machine-learning-algorithms-in-python-3o1n3w07
* https://www.scikit-yb.org/en/latest/api/contrib/boundaries.html
* https://scikit-learn.org/stable/modules/generated/sklearn.inspection.DecisionBoundaryDisplay.html#sklearn.inspection.DecisionBoundaryDisplay
* https://scikit-learn.org/stable/auto_examples/svm/plot_svm_kernels.html#sphx-glr-auto-examples-svm-plot-svm-kernels-py