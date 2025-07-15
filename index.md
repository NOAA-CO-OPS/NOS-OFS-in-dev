---

#
layout: home
title: Upcoming NOS OFS
---

NOS is partnering with model developers to develop and implement into operations new operational forecast systems (OFS) that will expand domain coverage of NOS OFS and replace legacy OFS. 

The following OFS will be transitioned into operations at NOS in the coming years:
* The **Northeast Coastal Operational Forecast System (NECOFS)**, developed in partnership with University of Massachusetts at Dartmouth, NERACOOS, University of New Hampshire, Woods Hole Oceanographic Institution, and the Gulf of Maine Research Institute.
* The **Southeast Coastal Operational Forecast System (SECOFS)**, developed in partnership with the Virginia Institute of Marine Sciences and SECOORA.
* The **East Coast OFS (ECOFS)**, developed in partnership with Rutgers University, Fathom Science LLC, University of California Santa Cruz, and MARACOOS.
* The upgraded **Lake Ontario OFS (LOOFS)**, developed in partnership with the Great Lakes Environmental Research Laboratory and the Cooperative Institute for Great Lakes Research.

The map below delineates the domains of these upcoming OFS:
![OFS map](https://raw.githubusercontent.com/lucila-h-b/lucila-h-b.github.io/refs/heads/main/images/OFSCoverage.png "Map of existing and future OFS coverage")

## NECOFS
The NECOFS domain extends from Bald Head Island, North Carolina northeastward to Nova Scotia, Canada. This model will expand domain coverage of the Northeast coast, resolving major oceanographic processes and providing coastal predictions in areas not currently covered by NOS OFS, such as Narragansett Bay, Long Island Sound, and Pamlico Sound.

The primary goal of this development effort is to replace the [New York and New Jersey OFS (NYOFS)](https://tidesandcurrents.noaa.gov/ofs/nyofs/nyofs.html), which was implemented into operations at NOS in early 2003 without any subsequent updates. NYOFS is a three-dimenstional barotropic model based on the Princeton Ocean Model, which is no longer maintained as an NOS OFS core model. NECOFS is based on the Finite Volume Coastal Ocean Model (FVCOM), which is one of NOS' preferred community-supported ocean models operated under the standardized [Coastal Ocean Modeling Framework](https://tidesandcurrents.noaa.gov/publications/NOAA_Technical_Report_NOS_COOPS_069.pdf) at NOAA's Weather and Climate Operational Supercomputing System.NECOFS will also potentially replace the existing [Chesapeake Bay OFS (CBOFS)](https://tidesandcurrents.noaa.gov/ofs/cbofs/cbofs.html), the [Delaware Bay OFS (DBOFS)](https://tidesandcurrents.noaa.gov/ofs/dbofs/dbofs.html), and the [Gulf of Maine OFS (GOMOFS)](https://tidesandcurrents.noaa.gov/ofs/gomofs/gomofs.html).
 
The fundamental requirement is to provide a short term (3-5 days), hourly, high resolution forecast of hydrodynamic variables for the coastal region of the Northeast U.S, four times per day. The predicted parameters include *sea level, currents, sea temperature, and sea salinity*. Key stakeholders have indicated that they need accurate forecasts of surface water temperature and surface currents. Consequently, this system will include:
* Skillful predictions that are informed by data assimilation of water level and temperature;
* An unstructured mesh with a horizontal resolution between 83m and 41 km, and 45 vertical layers; and
* Incorporation of 77 river and channel features from the National Water Model.

Before the model is implemented into operations, NOS will conduct semi-operational realtime runs to evaluate its skill and stability. As part of the evaluation, users will have the opportunity to see developmental output and graphics and provide feedback.

![NECOFS mesh](https://raw.githubusercontent.com/lucila-h-b/lucila-h-b.github.io/refs/heads/main/images/NECOFS-mesh.png "Map of unstructured, FVCOM-based NECOFS mesh")

*The above image shows the unstructured mesh used for NECOFS, with high resolution areas around the coast and in the nearshore*

**If interested in providing feedback or have any questions, contact [co-ops.userservices@noaa.gov](co-ops.userservices@noaa.gov)**








