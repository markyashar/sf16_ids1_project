# sf16_ids1_project
Data Science Project: Exploratory and Regression Analysis and Visualization of the Open Exoplanet Catalogue

In the notebook "exoplanet_exploration1.ipynb" I explore the Open Exoplanet Catalogue dataset using numpy, pandas, matplotlib, seaborn, scikit-learn and other python libraries. A description of this dataset can be found at https://www.kaggle.com/mrisdal/open-exoplanet-catalogue and https://github.com/OpenExoplanetCatalogue/open_exoplanet_catalogue. This is a database of all discovered extra-solar planets in csv format. The filename of the dataset is "oec.csv". It includes the characteristics of all discovered exoplanets (as well as planets in our own solar system). Data fields (columns) include planet and host star attributes, discovery methods, and date of discovery, such as:

PeriodDays: The orbital period (how long it takes the planet to orbit its host star once), measured in days, of the planet around the host star or binary (double) star system.

PlanetaryMassJpt: The mass of the planet in Jupiter masses, where 1 Jupiter mass is 1.8991766e+27 kg.

RadiusJpt: The physical radius of the planet in Jupiter radii where 1 Jupiter radius is 69911000 m.

SurfaceTempK: The surface temperature of the planet (units: Kelvins).

SemiMajorAxisAU: The semi-major axis of a planet (essentially the average distance between the planet and the host star, but a more precise and detailed description here: https://en.wikipedia.org/wiki/Semi-major_and_semi-minor_axes) in Astronomical Units (AU), which is roughly the average distance between the Earth and Sun (149597870700 meters, or about 150 million kilometers (https://en.wikipedia.org/wiki/Astronomical_unit).

Eccentricity: The orbital eccentricity of the planet around its host star. The orbital eccentricity of an astronomical object is a parameter that determines the amount by which its orbit around another body deviates from a perfect circle. A value of 0 is a circular orbit, values between 0 and 1 form an elliptical orbit, 1 is a parabolic escape orbit, and greater than 1 is a hyperbola (https://en.wikipedia.org/wiki/Orbital_eccentricity).

HostStarMassSlrMass: The mass of the host star in solar masses, where 1 solar mass is 1.9891e+30 kg

HostStarRadiusSlrRad: The physical radius of the host star in solar radii, where 1 solar radius is 6.96e+08 m.

HostStarMetallicity: The stellar metallicity of the host star, which is fraction of mass of the host star that is not in hydrogen or helium (see https://en.wikipedia.org/wiki/Metallicity).

HostStarTempK: The equilibrium temperature of the host star in Kelvins.

HostStarAgeGyr: The age of the host star in giga-years.

DistFromSunParsec: The distance of the planet from the sun in units of parsecs, where a parsec is equal to about 3.26 light-years (31 trillion kilometers or 19 trillion miles) in length (see https://en.wikipedia.org/wiki/Parsec).
