# GIS Notes & Resources

Welcome to my GIS reference page. This is a simple hub for data sources, quick notes, and examples I want to keep handy.

---

## USA Shapefile Hierarchy 

USA Zipcodes (~500MB) - <a href="https://www2.census.gov/geo/tiger/TIGER2025/ZCTA520/tl_2025_us_zcta520.zip" target="_blank">US Census Dept</a>  

### Washington State Shapefile Hierarchy 

The Washington Geospacial Data site does not have a great search functionality. As an example, a search for <a href="https://geo.wa.gov/search?q=counties" target="_blank">counties</a> does not have the WA County Boundaries show up first in the list (although using 'county' will be correct, but not intuitive). This hierarchy links directly to desired information from broadest to most fine-grained shapefiles pertaining to Washington State. If needed you can go back and search for the exact entry below to view the shapefile/map (ie Search <a href="https://geo.wa.gov/search?q=WA%20County%20Boundaries" target="_blank">WA County Boundaries"</a> to find that exact entry)  

- WA State Boundary Mask - <a href="https://geo.wa.gov/maps/1406ebe4ea974f5894f954a9c0a9c3a8" target="_blank">Geo WA gov</a>  
  *This is the inverse of the WA State Boundary, useful to use as a selection to delete features outside of washington with about a 5 mile boundry to prevent features close to washington border being removed.  

- WA State Boundary (92kb) - <a href="https://geo.wa.gov/maps/a77ee02fab3e4793b274ec52b7a523d8" target="_blank">Geo WA gov</a>  
  
  - WA County Boundaries (1MB) - <a href="https://geo.wa.gov/maps/12712f465fc44fb58328c6e0255ca27e" target="_blank">Geo WA gov</a>  
	*Useful for Aggrigate Data  
	
    - City Boundaries (1MB) - <a href="https://geo.wa.gov/datasets/69fcb668dc8d49ea8010b6e33e42a13a_0" target="_blank">Geo WA gov</a>  
	  *Does not cover all of Washington if needed fall back to county for full state coverage  
	  
      - WA Zipcodes (8MB) - [Download ZIP](downloads/WA_State_tl_2025_us_zcta520.zip)  
	    Created using USA Zipcodes.  
	    NOTE: Zipcodes do change, don't cover 100% of the state, cover portions of out of state, and are approximate.  
	    *Useful for Service Areas, Logistics, Government Specific Zipcode Data  
	    	
        - Statewide Precincts (30MB) - <a href="https://geo.wa.gov/datasets/f5431071d8f74a7fb655bf0477ccfc2e_0" target="_blank">Geo WA gov</a>  
	  	  *Useful for Voting data  
	  		
          - WA Census Tracs (8MB) - <a href="https://geo.wa.gov/datasets/d4df13888a684280b745687b1f08a5f2_0" target="_blank">Geo WA gov</a>  
	        *Useful for Population Data, has a lot of attributes with historical population data  

          - WA Current Parcel Data (1GB) - <a href="https://wa-geoservices.maps.arcgis.com/home/item.html?id=0f4c2ca4b589499c8df7779a01bef002" target="_blank">WA GeoServices ArcGIS</a>  
		    *Parcels can be very fine grained, giving it's large size, for use for real estate or land use. Size of each parcel varies due to population/building density  