# Machine Learning-project
here i created a machine learning model by using svm algorithm frm scikit learn and pandas which predict the orbital path of asteroid considering some input data about the orbit
the data file is in csv form

#### Here is the snap shot of ml model which is hosted in django

![image](https://github.com/UmraFathima/Ml-project/assets/154687173/775e06a9-3006-417d-add7-b433090e9bfe)

Here is about the dataset which i used to create a machine learning model

Asteroid Orbital Path

Asteroids, sometimes called minor planets, are rocky remnants left over from the early formation of our solar system about 4.6 billion years ago.
 
Most asteroids are irregularly shaped, though a few are nearly spherical, and they are often pitted or cratered. As they revolve around the Sun in elliptical orbits, the asteroids also rotate, sometimes quite erratically, tumbling as they go.
 
The orbits of asteroids can be changed by Jupiter's massive gravity – and by occasional close encounters with Mars or other objects.These encounters can knock asteroids out of the main belt, and hurl them into space in all directions across the orbits of the other planets. Stray asteroids and asteroid fragments have slammed into Earth and the other planets in the past, playing a major role in altering the geological history of the planets and in the evolution of life on Earth.
 
My Task was to build a Machine Learning model that identifies the orbital path of an Asteroid.

Dataset Description
 
The dataset presents a basic Multi Class Classification problem. One has to classify the orbit of the Asteroid into one of the following types:-
• Atira
• Aten
• Apollo
• Amor
• Object with perihelion distance < 1.665 AU
• Hungaria
• MBA
• Phocaea
• Hilda
• Jupiter Trojan
• Distant Object
Name - name of the asteroid.
Number - Permanent designation of the asteroid
Principal_desig - Principal provisional designation (if it exists)
Other_desigs - Other provisional designations (if they exist)
H - Absolute magnitude
G - Slope parameter
Epoch - Epoch of the orbit (Julian Date)
a - Semimajor axis, a (AU)
e - Orbital eccentricity, e
i - Inclination to the ecliptic, J2000.0 (degrees)
Node - Longitude of the ascending node, ☊, J2000.0 (degrees)
Peri - Argument of perihelion, ω, J2000.0 (degrees)
M - Mean anomaly, M, at the epoch (degrees)
n -----float----- Mean daily motion, n (degrees/day)
U -----string -----Uncertainty parameter, U
Ref -----string -----Reference
Num_obs----- integer -----Number of observations
Num_opps -----integer -----Number of oppositions
Arc_years -----string----- Only present for multi-opposition orbits (year of first observation – year of last observation)
Arc_length----- integer----- Only present for 1-opposition orbits (days)
rms -----float----- r.m.s. residual
Perturbers -----string----- Coarse indicator of perturbers used in orbit computation
Perturbers_2 -----string -----Precise indicator of perturbers used in orbit computation
Last_obs -----string----- Date of last observation included in orbit solution (YYYY-MM-DD format)
Hex_flags----- string -----4-hexdigit flags
Computer----- string----- Name of orbit computer (be it a person or machine)
NEO_flag------ integer -----Value = 1 if flag raised, otherwise keyword is absent
One_km_NEO_flag------ integer----- Value = 1 if flag raised, otherwise keyword is absent
PHA_flag----- integer -----Value = 1 if flag raised, otherwise keyword is absent
One opposition
object
flag----- integer----- Value = 1 if flag raised, otherwise keyword is absent
Critical list numbered object_flag -----integer -----Value = 1 if flag raised, otherwise keyword is absent
Perihelion_dist----- float----- Perihelion distance (AU)
Aphelion_dist----- float---- Aphelion distance (AU)
Semilatus_rectum -----float -----Semilatus rectum distance (AU)
Orbital_period---- float----- Orbital period (years)
Synodic_period----- float----- Synodic period (years)

snapshot of predicting the object 

![Screenshot 2023-12-10 151155](https://github.com/UmraFathima/Ml-project/assets/154687173/589c0136-2e39-4fb1-a39f-1e352a9a8ab2)
