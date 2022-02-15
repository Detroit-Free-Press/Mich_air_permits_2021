# Michigan air permits: 2021

The Free Press is making air permit data available for the first time to improve access and to help build on our work examining air pollution in communities with long-standing racial and socioeconomic disparities.

These are the air permit files behind the story [Sacrifice Zones](https://www.freep.com/in-depth/news/local/michigan/2021/12/30/michigan-environmental-justice-pollution-permitting-egle-epa/8888962002/url). Specifically, Michigan air permits approved in 2021 and active as of Dec. 19, 2021. A total of 309 permits were approved in 2021 and still active at the end of the year.

The Michigan Department of Environment, Great Lakes and Energy does not provide geographic coordinates for sites with air permits. The state does [publish a list of active, approved permits](https://www.deq.state.mi.us/aps/downloads/permits/finpticon/Active%20PTIs%20by%20SRN.pdf) that includes information such as company name, permit number, approval date and site address. Building on this information permits were geocoded using the site address and by matching state registration numbers to a [U.S. EPA facility database](https://www.epa.gov/frs/epa-state-combined-csv-download-files). A handful of sites were placed on the map manually using the United States Public Land Survey System.

_This information was made possible in part by a Kozik Environmental Justice Reporting Grant funded by the National Press Foundation and the National Press Club Journalism Institute._

## Data dictionary
* X: x coordinate
* Y: y coordinate
* count: The number of air permits approved and active as of Dec. 19, 2021 at this location.
* company_or: Company name
* adress_ori: Address
* city_1: City
* county: County
* zip: ZIP Code
* ptinum: Air permit to install number
* approved: Permit approval date
* rop: [Renewable Operating Permit Site](https://www.michigan.gov/egle/0,9429,7-135-3310_70487_6975-389493--,00.html) (1=yes, 0=no)
* srn: State registration number
* naicscode: [North American Industry Classification System](https://www.census.gov/naics/) code
* naicstitle: North American Industry Classification System description
* notes: Notes from EGLE air permit source document
* addressgeo: Site address used for geocoding
* year: Year approved
* srnunique: Field added to differentiate when the same state registration number was used at two different sites
* ROPNAME: Company name as listed on EGLE's Renewable Operating Permit Site list

## Reusing the data
The company's Terms of Service apply. By using the data, you accept and agree to follow the [Terms of Service](https://cm.freep.com/terms/).
Reselling the data is forbidden. Any use of these data in published works requires attribution to the Detroit Free Press. 

## Notes
Some companies may have multiple permits at different sites. Three active air pollution permits approved in 2021 were not mapped due to incomplete address data. NAICS code for facilities, where available, are included based on facility information from the U.S. EPA. Permit files can be found on[ DocumentCloud](https://www.documentcloud.org/projects/air-pollution-permits-2021-206020/). The file name for each permit corresponds to the field ptinum.

Demographic data used for analysis and presentation are downloaded directly from the U.S. Census Bureau. Specifically, [race and ethnicity data by census block](https://data.census.gov/cedsci/table?q=P2&g=0400000US26%241000000&tid=DECENNIALPL2020.P2) and block group in Michigan are 2020 decennial census data. And [poverty data](https://data.census.gov/cedsci/table?text=poverty&g=0400000US26%241500000&d=ACS%205-Year%20Estimates%20Detailed%20Tables&tid=ACSDT5Y2019.B17021) are the latest 5-year American Community Survey (ACS) estimates, 2019.

## Contact and questions?
Feel free to send an e-mail to Kristi Tanner at ktanner@freepress.com. 
Also, consider buying a [digital subscription](https://cm.freep.com/specialoffer). Without your support projects like this would not be possible.

