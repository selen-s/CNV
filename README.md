## CNV (Celestial Navigation, Position Estimation using EqF on Sphere S2)

This repository contains directories and files used in the creation of the CNV_mid.ipynb notebook. 

CNV is a software prototype that, given inputs in J2000 epoch time (seconds) and right ascension / declination coordinates of a stellar object at zenith, returns an estimate of the user's latitude and longitude on Earth. 

This project is based on the Equivariant Filter (EqF) paper by van Goor, Hamel, and Mahony.

The main functional notebook is CNV_mid.ipynb; other notebooks with CNV titles are drafts. The directories CNV_csvs, CNV_videos, and star_images contain CSVs with gravity and gyroscope data, videos of stars, and images of stars, respectively. In the current edition of CNV, the star videos and images are not used. 

Several Python libraries are required to run this software:
numpy\\
os\\
subprocess
sys
pathlib
tetra3
PIL
glob
pandas
astropy.coordinates
astropy.units

2026 Selen Serdar
