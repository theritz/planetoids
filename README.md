# Planetoids

In the notebook we'll read in all the asteroid data of the Minor Planet Center and do two things with it:

- see if we can categorise them in any recognisable and scientifically sound way
- plot them in a 3D matrix in relation to Earth
- use clustering to see if we can identify known planetoid 'families'

The code uses the file 'mpcorb_extended.json' from the working dir. The file itself you can find at the MPC site here https://www.minorplanetcenter.net/data.
If the file takes too long to load you can simply cut out data taking care not to mess up the json structure.

_This research has made use of data and/or services provided by the International Astronomical Union's Minor Planet Center._

See https://www.minorplanetcenter.net/ for more on what they do. There you can also find the dataset you need called 'mpcorb_extended.json.gz'. This record is updated daily.
The notebook isn't done but feel free to add to it for yourself, it's not rocket science after all...
