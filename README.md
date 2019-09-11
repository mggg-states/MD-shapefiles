# Maryland Election Shapefiles 
This shapefile was obtained from the Maryland Department of Planning website and processed by members of the Metric Geometry and Gerrymandering Group (MGGG).

## Sources
The Maryland precinct shapefile was obtained from the [Maryland Department of Planning's Redistricting website](https://planning.maryland.gov/Redistricting/Pages/2010/precinct.aspx). Election data come from the [Maryland State Board of Elections](https://elections.maryland.gov/elections/2018/election_data/index.html).

## Processing
Statewide election returns from the Board of Elections were cleaned by MGGG staff in order to join them to the precinct shapefile. Ceratin precincts in the shapefile and in the results were merged in order to reconcile discrepencies. Demographic data was aggregated from the block level using [MGGG’s proration software](https://github.com/mggg/maup). Congressional and state legislative district IDs were assigned to precincts also using this package.

## Metadata
* `NAME`: Precinct name
* `CNG02`: 2002 Congressional district ID
* `COUNTY`: County FIPS Code
* `LEG02`: 2002 State Legislative district ID
* `VTD`: Precinct ID
* `MCD`: Minor Civil Division ID
* `STATE`: State FIPS code
* `VTD_1`: County and Precinct ID
* `PLACE`: Census Designated Place ID
* `UNADJPOP`: Total unadjusted population  
* `ADJ_POP`: Total population, adjusted in accordance with the ["No Represenation Without Population Act"](https://planning.maryland.gov/Redistricting/Documents/2010data/GreenReport_web.pdf)
* `ADJ_WHITE`: Adjusted white alone population
* `ADJ_BLACK`: Adjusted Black alone population
* `ADJ_AMIN`: Adjusted American Indian and Alaska Native alone population
* `ADJ_ASIAN`: Adjusted Asian alone population
* `ADJ_NHPI`: Adjusted Native Hawaiian and Pacific Islander alone population
* `ADJ_2MORE`: Adjusted population of two or more races
* `UNADJHISP`: Unadjusted Hispanic population of any race
* `ADJ_VAP`: Adjusted voting age population
* `ADJ_WVAP`: Adjusted white alone voting age population
* `ADJ_BVAP`: Adjusted Black alone voting age population
* `ADJAMINVAP`: Adjusted American Indian and Alaska Native alone voting age population
* `ADJASNVAP`: Adjusted Asian alone voting age population
* `ADJNHPIVAP`: Adjusted Native Hawaiian and Pacific Islander alone voting age population
* `ADJOTHVAP`: Adjusted voting age population of other race
* `OCCUPIED`: Number of occupied houseing units
* `UNOCCUPIED`: Number of unoccupied housing units
* `TOTPOP`: Total population from 2010 Decennial Census
* `NH_WHITE`: White, non-hispanic, population from 2010 Decennial Census
* `NH_BLACK`: Black, non-hispanic, population from 2010 Decennial Census
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population from 2010 Decennial Census
* `NH_ASIAN`: Asian, non-hispanic, population from 2010 Decennial Census
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population from 2010 Decennial Census
* `NH_OTHER`: Other race, non-hispanic, population from 2010 Decennial Census
* `NH_2MORE`: Two or more races, non-hispanic, population from 2010 Decennial Census
* `HISP`: Hispanic population from 2010 Decennial Census
* `H_WHITE`: White, hispanic, population from 2010 Decennial Census
* `H_BLACK`: Black, hispanic, population from 2010 Decennial Census
* `H_AMIN`: American Indian and Alaska Native, hispanic, population from 2010 Decennial Census
* `H_ASIAN`: Asian, hispanic, population from 2010 Decennial Census
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population from 2010 Decennial Census
* `H_OTHER`: Other race, hispanic, population from 2010 Decennial Census
* `H_2MORE`: Two or more races, hispanic, population from 2010 Decennial Census
* `VAP`: Total voting age population from 2010 Decennial Census
* `HVAP`: Hispanic voting age population from 2010 Decennial Census
* `WVAP`: White, non-hispanic, voting age population from 2010 Decennial Census
* `BVAP`: Black, non-hispanic, voting age population from 2010 Decennial Census
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population from 2010 Decennial Census
* `ASIANVAP`: Asian, non-hispanic, voting age population from 2010 Decennial Census
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population from 2010 Decennial Census
* `OTHERVAP`: Other race, non-hispanic, voting age population from 2010 Decennial Census
* `2MOREVAP`: Two or more races, non-hispanic, voting age population from 2010 Decennial Census
* `PRES12R`: Number of votes for 2012 Republican presidential candidate
* `PRES12D`: Number of votes for 2012 Democratic presidential candidate
* `SEN12R`: Number of votes for 2012 Republican senate candidate
* `SEN12D`: Number of votes for 2012 Democratic senate candidate
* `SEN12U`: Number of votes for 2012 Unaffiliated senate candidate
* `SEN12L`: Number of votes for 2012 Libertarian senate candidate
* `USH12R`: Number of votes for 2012 Republican US House candidate
* `USH12D`: Number of votes for 2012 Democratic US House candidate
* `GOV14R`: Number of votes for 2014 Republican gubernatorial candidate
* `GOV14D`: Number of votes for 2014 Democratic gubernatorial candidate
* `AG14R`: Number of votes for 2014 Republican attorney general candidate
* `AG14D`: Number of votes for 2014 Democratic attorney general candidate
* `AG14L`: Number of votes for 2014 Libertarian attorney general candidate
* `COMP14R`: Number of votes for 2014 Republican comptroller candidate
* `COMP14D`: Number of votes for 2014 Democratic comptroller candidate
* `USH14R`: Number of votes for 2014 Republican US House candidate
* `USH14D`: Number of votes for 2014 Democratic US House candidate
* `SSEN14R`: Number of votes for 2014 Republican state senate candidate
* `SSEN14D`: Number of votes for 2014 Democratic state senate candidate
* `SSEN14U`: Number of votes for 2014 Unaffiliated state senate candidate
* `PRES16R`: Number of votes for 2016 Republican presidential candidate
* `PRES16D`: Number of votes for 2016 Democratic presidential candidate
* `PRES16L`: Number of votes for 2016 Libertarian presidential candidate
* `PRES16G`: Number of votes for 2016 Green Party presidential candidate
* `SEN16R`: Number of votes for 2016 Republican senate candidate
* `SEN16D`: Number of votes for 2016 Democratic senate candidate
* `SEN16G`: Number of votes for 2016 Green Party senate candidate
* `USH16R`: Number of votes for 2016 Republican US House candidate
* `USH16D`: Number of votes for 2016 Democratic US House candidate
* `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
* `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
* `SEN18R`: Number of votes for 2018 Republican senate candidate
* `SEN18D`: Number of votes for 2018 Democratic senate candidate
* `USH18R`: Number of votes for 2018 Republican US House candidate
* `USH18D`: Number of votes for 2018 Democratic US House candidate
* `AG18R`: Number of votes for 2018 Republican attorney general candidate
* `AG18D`: Number of votes for 2014 Democratic attorney general candidate
* `COMP18R`: Number of votes for 2018 Republican comptroller candidate
* `COMP18D`: Number of votes for 2018 Democratic comptroller candidate
* `SSEN18R`: Number of votes for 2018 Republican state senate candidate
* `SSEN18D`: Number of votes for 2018 Democratic state senate candidate
* `SSEN18G`: Number of votes for 2018 Green Party state senate candidate
* `SSEN18L`: Number of votes for 2018 Libertarian state senate candidate
* `SSEN18U`: Number of votes for 2018 Unaffiliated state senate candidate
* `CD`: Congressional district ID from 2011 enacted plan
* `HDIST`: House of Delegates district ID
* `SENDIST`: State Senate district ID

## Projection
This shapefile uses a NAD83 Maryland projection (EPSG: 26985).

## Rating
We give these shapefiles an A rating. All data was obtained from the state government and was processed by MGGG staff.
