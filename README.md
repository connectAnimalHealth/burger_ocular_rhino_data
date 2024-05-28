# Dataset: Ocular biometry and pathology in captive and free-ranging southern white rhinoceros (*Ceratotherium simum simum*) and south-central black rhinoceros (*Diceros bicornis minor*) in South Africa

This is the data repository for the MMedVet research project of Dr Paul Burger: Ocular biometry and pathology in captive and free-ranging southern white rhinoceros (*Ceratotherium simum simum*) and south-central black rhinoceros (*Diceros bicornis minor*) in South Africa.

## Notes
Certain data has been removed due to its sensitive nature. These data items are listed below:
- Location
    - Each data point was linked to a general location in South Africa. Whilst the location was general it is due to the sensitive nature of rhino that any location idetifier was removed from individual data points.
All missing data is retained in the dataset and are indicated by *NA*

## Data dictionary
### Acronyms
| Acronym    | Description |
| -------- | ------- |
| OD  | oculus dexter (the right eye)    |
| OS |  oculus sinister (the left eye)    |
| OU |  oculus uterque (both eyes)     |

Note that all variables in the table below that have a dagger symbol were classified by OD, OS or OU (as applicable) as per above definitions. Where pathology did not exist the data are not retained as a variable specifcially - see all variables with the *path_* prefix.

| Variable    | Data type |Description|
| -------- | ------- | -------  |
| animalNumber  | integer    | serial allocation to each animal based on examination order|
| examDate | date    | date of examination|
| subspecies    | text    | sub-species of the animal|
|sex| text| male or female classification|
|age| text| adult, sub-adult or calf age classification|
|wild.or.captive| holding class| captive camp or wild as the location of origin of each animal|
|STT<sup>&sect;</sup>|numeric|Schirmer Tear Test result in mm/min|
|IOP<sup>&sect;</sup>|numeric|Intra-ocular pressure in mm of mercury (mmHg)|
|Flour<sup>&sect;</sup>|boolean|NEED THIS|
|axial.globe.length<sup>&sect;</sup>|numeric|NEED THIS|
|anterior.chamber.depth<sup>&sect;</sup>|numeric|NEED THIS|
|axial.lens.thickness<sup>&sect;</sup>|numeric|NEED THIS|
|posterior.segment.depth<sup>&sect;</sup>|numeric|NEED THIS|
|crystalline.lens.thickness<sup>&sect;</sup>|numeric|NEED THIS|
|R1.mm<sup>&sect;</sup>|numeric|NEED THIS|
|R1.D<sup>&sect;</sup>|numeric|NEED THIS|
|R2.mm<sup>&sect;</sup>|numeric|NEED THIS|
|R2.D<sup>&sect;</sup>|numeric|NEED THIS|
|R1.R2.avg.mm<sup>&sect;</sup>|numeric|Average reading for R1.mm and R2.mm above in mm|
|R1.R2.avg.D<sup>&sect;</sup>|numeric|Average reading for R1.D and R2.D above in NEED THIS|
|path_cataract<sup>&sect;</sup>|boolean|Presence of cataract|
|path_corneal scar<sup>&sect;</sup>|boolean|Presence of corneal scar|
|path_corneal ulcer<sup>&sect;</sup>|boolean|Presence of corneal ulcer|
|path_follicular conjunctivitis<sup>&sect;</sup>|boolean|Presence of follicular conjunctivitis|
|path_foreign body - corneal<sup>&sect;</sup>|boolean|Presence of corneal foreign body/ies|
|path_foreign body - intra-ocular<sup>&sect;</sup>|boolean|Presence of intraocular foreign body/ies|
|path_keratitis<sup>&sect;</sup>|boolean|Presence of keratitis|
|path_nuclear sclerosis<sup>&sect;</sup>|boolean|Presence of nuclear sclerosis|
|path_pigmentary keratitis<sup>&sect;</sup>|boolean|Presence of pigmentary keratitis|
|path_posterior synechiae<sup>&sect;</sup>|boolean|Presence of posterior synechiae|
|path_ppm<sup>&sect;</sup>|boolean|Presence of NEED THIS|



