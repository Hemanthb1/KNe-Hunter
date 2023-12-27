# KNe-Hunter
### This repo contains the code for multimessenger alert crossmatching i.e, LIGO alerts and ZTF alert stream. It performs spatial queries for ZTF events within the LIGO GW skymaps. Specifically, it fetches the events within 5 days of the timeframe of the GW event. Utilizes the lightcurve classifier infrastructure at ALeRCE, events will be filtered based on stamp classification, rise time and location of the event. It uses 'delight' to assign host galaxy location, which will be further crossmatched with NED, SIMBAD, and local galaxies catalog HECATE.

<img src="/home/mayhem/skymap.jpg" alt="Alt text" title="crossmatched events">
