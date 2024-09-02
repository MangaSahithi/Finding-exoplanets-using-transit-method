The search for exoplanets, planets orbiting around stars other than our Sun, has been a fascinating and rapidly evolving field in modern astronomy.
Among the various techniques employed to detect these celestial bodies, the transit method has proven to be one of the best approaches.
This method relies on the periodic dimming of a star's light as  an orbiting plaet passes in front of it, temporarily obscuring a fraction of star's visible surface.
The TESS and KEPLER space telescope have revolutionized our ability to detect and study exoplanets through the transit method.
This project focuses on the application of light curve analysis techniques to rich datasets provided by TESS and Kepler.
Light curves , which represent the brightness of the star overtime , hold the key to identifying periodic dips that may indicate the presence of exoplanets.
Once the data is downloaded ,Lightkurve can create an object  which provide easy access to various properties for processing and analyzing data .
when a transit signal is detected Lightkurve allow you to fold and flatten the lightcurve at detected period which is easy to visually inspect and confirm the signal.
At last we calculate periodogram then find Max peak period , apply Box Least Square method. Finally validation and visualizing results are done.
