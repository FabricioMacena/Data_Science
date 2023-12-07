# Real Estate Sales - Connecticut
The dataset can be found at [data.ct.gov](https://data.ct.gov/Housing-and-Development/Real-Estate-Sales-2001-2020-GL/5mzw-sjtu)

## Context
> The Connecticut Office of Policy and Management maintains a list of all home sales with a sales price of $2,000 or more that occur between October 1 and September 30 of each year in the state of Connecticut. For each sale record, the file includes: location, property address, date of sale, type of property (residential, apartment, commercial, industrial or vacant land), sale price and property valuation.

> Data are collected in accordance with Connecticut General Statutes, section 10-261a and 10-261b: https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261a and https://www.cga.ct.gov/current/pub/chap_172.htm#sec_10-261b.

> Annual real estate sales are reported by grand list year (October 1 through September 30 each year). For instance, sales from 2018 GL are from 10/01/2018 through 9/30/2019.

## Content

- listyear: Year the property was listed for sale

- daterecorded: Date the sale was recorded locally

- town: Town name

- adress: Home address

- assessedvalue: Value of the property used for local tax assesment

- saleamount: Amount the property was sold for

- salesratio: Ratio of the sale price to the assessed value

- propertytype: Type of property including: Residential, Commercial, Industrial, Apartments, Vacant, etc

- residentialtype: Indicates whether property is single or multifamily residential

- remarks: Remarks from the assessor

- geo_coordinates: Lat / lon coordinates

- opm_remarks: Remarks from OPM

- nonusecode: Non usable sale code typically means the sale price is not reliable for use in the determination of a property value.

### Description of the codes in the 'nonusecode' column:

| Code | Category    | Description  |
|--------|------------|---------------|
| 01     | FAMILY Sale    | Sale between members of the same family.   |
| 02     | LOVE AND AFFECTION   | Sale in which "Love and affection" are part of the sales price. Stated in the deed.    |
| 03     | INTER CORPORATION    | Sales between a corporation and stockholder, subsidiary, affiliate, or another corporation.  |
| 04     | CORRECTING DEED    | Transfers of convenience; for example, sales for correcting defects in the title, creating a survivorship, etc.   |
| 05     | DEED DATE     | The date the deed was signed or the date of the agreement is more than six months prior to the October 1st assessment date. |
| 06     | PORTION OF PROPERTY    | Sales conveying only a portion of the property assessed as a unit, e.g., a split.   |
| 07     | CHANGE IN PROPERTY   | Sales of property substantially improved or changed subsequent to the assessment date.    |
| 08     | PART INTEREST  | Sales of an undivided or part interest in real property. For Co-ops, use this code.   |
| 09     | TAX SALE  |
| 10     | A WILL   | Conveyances made in accordance with an article of the decedent’s will. 
| 11     | COURT ORDER   | Judicial sale that is a sale from a court order.|
| 12     | NON BUILDABLE LOT  | Sale of a non-buildable lot to an abutting owner.|
| 13     | BANKRUPCY  | Sale in bankruptcy proceeding, receivership or assignment for the benefit of creditors, dissolutions, and liquidation sales.|
| 14     | FORECLOSURE     | Sale of a foreclosed property.  |
| 15     | GOVERNMENT AGENCY  | Sale to or from a government agency (local, state or federal).|
| 16     | CHARITABLE GROUP   | Sale to or from a charitable, educational, benevolent or religious organization.|
| 17     | TWO TOWNS  | Sale of a parcel of real property assessed or located in more than one town or state.|
| 18     | IN LIEU OF FORECLOSURE   | Transfer to banks, insurance companies, savings and loan associations, mortgage companies, or any other lien holder, when the transfer is made in lieu of a foreclosure.|
| 19     | EASEMENT  | Sales, such as to or from public utility companies, electric, telephone, pipeline companies or individuals (Right of way).|
| 20     | CEMETERY  | Sale of cemetery lot.   |
| 21     | PERSONAL PROPERTY EXCHANGE  | Sale of real property in exchange for any asset other than cash, such as other real estate, stocks, or bonds.    |
| 22     | MONEY AND PERSONAL PROPERTY | Sale of real property, which includes household furniture, machinery, fixtures, equipment, inventories or goodwill, when the cash value of such items is indeterminable. (Note: This category does not apply to appliances or ‘built-in’ units, which are normally included in the sale. For example, stove, dishwasher, wall-to-wall carpeting, etc.)|
| 23     | ZONING    | Sale of property, the value of which has been materially influenced by zoning changes effected since the last assessment date.|
| 24     | PLOTTAGE   | Combining two or more sites under a single ownership when each is separately considered.                          |
| 25     | OTHER REASONS   | Ratio is either way too high or way too low. Sale, which for some reason other than those categories enumerated above, is deemed not to be a transaction between a willing buyer (not compelled to buy) and/or a willing seller (not compelled to sell). Explain under REMARKS.|
| 26     | REHABILITATION DEFERRED     | (Section 12-65c to 12-65f C.G.S)   |
| 27     | CRUMBLING FOUNDATION ASSESSMENT REDUCTION | To be used only when the property being sold has an assessment reduction due to a crumbling foundation issue.     |
| 28     | USE ASSESSMENT  | Code 600 Sale of a property which is under a use assessment (farm, forest, open space: Section 12-107a-f). |
| 29     | NO CONSIDERATION    |
| 30     | AUCTION   | Sales of property at a public or private auction.  |