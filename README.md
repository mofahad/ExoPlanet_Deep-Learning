# ExoPlanet_Deep-Learning

The data describe the change in flux (light intensity) of several thousand stars. Each star has a binary label of 2 or 1. 2 indicated that that the star is confirmed to have at least one exoplanet in orbit; some observations are in fact multi-planet systems.

As you can imagine, planets themselves do not emit light, but the stars that they orbit do. If said star is watched over several months or years, there may be a regular 'dimming' of the flux (the light intensity). This is evidence that there may be an orbiting body around the star; such a star could be considered to be a 'candidate' system. Further study of our candidate system, for example by a satellite that captures light at a different wavelength, could solidify the belief that the candidate can in fact be 'confirmed'.

![alt text](https://github.com/mofahad/ExoPlanet_Deep-Learning/blob/master/heic1603b.jpg?raw=true)




# Description

Trainset:

 * 5087 rows or observations.
 * 3198 columns or features.
 * Column 1 is the label vector. Columns 2 - 3198 are the flux values over time.
 * **37** confirmed exoplanet-stars and 5050 non-exoplanet-stars.

Testset:

 * 570 rows or observations.
 * 3198 columns or features.
 * Column 1 is the label vector. Columns 2 - 3198 are the flux values over time.
 * **5** confirmed exoplanet-stars and 565 non-exoplanet-stars.
