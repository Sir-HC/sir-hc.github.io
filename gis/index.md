# GIS Notes & Resources

Welcome to my GIS reference page. This is a simple hub for data sources, quick notes, and examples I want to keep handy.

---

## USA Shapefile Hierarchy 

USA Zipcodes (~500MB) - [US Census Dept](https://www2.census.gov/geo/tiger/TIGER2025/ZCTA520/tl_2025_us_zcta520.zip)

### Washington State Shapefile Hierarchy 
- WA State Boundary Mask - [Geo WA gov](https://geo.wa.gov/maps/1406ebe4ea974f5894f954a9c0a9c3a8)
  *This is the inverse of the WA State Boundary, useful to use as a selection to delete features outside of washington with about a 5 mile boundry to prevent features close to washington.

- WA State Boundary (92kb) - [Geo WA gov](https://geo.wa.gov/maps/a77ee02fab3e4793b274ec52b7a523d8)
  
  - WA County Boundaries (1MB) - [Geo WA gov](https://geo.wa.gov/maps/12712f465fc44fb58328c6e0255ca27e)
	*Useful for Aggrigate Data
    
    - WA Zipcodes (8MB) - [Download ZIP](downloads/WA_State_tl_2025_us_zcta520.zip) Created using USA Zipcodes. 
	  NOTE: Zipcodes do change, don't cover 100% of the state, cover portions of out of state, and are approximate.
	  *Useful for Service Areas, Logistics, Government Specific Zipcode Data
	  	
      - Statewide Precincts (30MB) - [Geo WA gov](https://geo.wa.gov/datasets/f5431071d8f74a7fb655bf0477ccfc2e_0/)
		*Useful for Voting data
			
        - WA Census Tracs (8MB) - [Geo WA gov](https://geo.wa.gov/datasets/d4df13888a684280b745687b1f08a5f2_0/)
	      *Useful for Population Data
