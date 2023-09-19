## Data Dictionary
for Linguistics GA Capstone

#### Calculated Fields
- **Percent at Risk** - count of languages at risk/count of total languages within families

#### Glottolog
- **Name** - Language/Dialect Name
- **Macroarea** - Region
- **Latitude** - lat
- **Longitude** -long
- **Glottocode** - Unique ID for all languages assigned by Glottolog org
- **Countries** - Countries
- **Family_ID** - ID of language family
- **~ID~** *removed* - same data as glottocode
- **~Language_ID~** *removed* same data as Family_ID
- **~ISO63P3code~** *removed*- International language codes (ISO 639-3) for all natural languages, faulty information did not import
- **~Closest_ISO36P3code~** *removed* closest ISO 639-3
- **~First_Year_of_Documentation~** *removed* - missing data, irrelevant to project
- **~Last_Year_of_Documentation~** *removed* - missing data, irrelevant to project

#### Global Predictors Study
- **ISO**  - used isocode to glottocode for key
- **EGIDS**- Expanded Graded Intergenerational Disruption Scale (see below)
- **L1 Pop** - number of speakers (estimated)
- **GDPpc** - GDP Per Capita
- **education_spending** - percentage of GDP spending dedicated to education



### Tables/Scales
**[Agglomerated Endangerment Scale (AES)](https://glottolog.org/langdoc/status#:~:text=The%20Agglomerated%20Endangerment%20Status%20measures,Languages%20in%20Danger%20and%20Ethnologue.)**
| ID |       Parameter_ID | Name |    Description |                                   numerical_value |     |
|---:|-------------------:|-----:|---------------:|--------------------------------------------------:|-----|
| 18 | aes-not_endangered |  aes | not endangered |            EGIDS: <=6a; UNESCO: safe; ElCat: safe | 1.0 |
| 19 |     aes-threatened |  aes |     threatened |  EGIDS: 6b; UNESCO: vulnerable; ElCat: vulnerable | 2.0 |
| 20 |       aes-shifting |  aes |       shifting | EGIDS: 7; UNESCO: definitely endangered; ElCat... | 3.0 |
| 21 |       aes-moribund |  aes |       moribund | EGIDS: 8a; UNESCO: severely endangered; ElCat:... | 4.0 |
| 22 | aes-nearly_extinct |  aes | nearly extinct | EGIDS: 8b; UNESCO: critically endangered; ElCa... | 5.0 |
| 23 |        aes-extinct |  aes |        extinct |       EGIDS: >=9; UNESCO: extinct; ElCat: extinct | 6.0 |

**[Expanded Graded Intergenerational Disruption Scale (EGIDS)](https://www.ethnosproject.org/expanded-graded-intergenerational-disruption-scale/)**
| Level | Label               | Description                                                                                                                                              |
|-------|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0     | International       | The language is widely used between nations in trade, knowledge exchange, and international policy.                                                      |
| 1     | National            | The language is used in education, work, mass media, and government at the national level.                                                               |
| 2     | Provincial          | The language is used in education, work, mass media, and government within major administrative subdivisions of a nation.                                |
| 3     | Wider Communication | The language is used in work and mass media without official status to transcend language differences across a region.                                   |
| 4     | Educational         | The language is in vigorous use, with standardization and literature being sustained through a widespread system of institutionally supported education. |
| 5     | Developing          | The language is in vigorous use, with literature in a standardized form being used by some though this is not yet widespread or sustainable.             |
| 6a    | Vigorous            | The language is used for face-to-face communication by all generations and the situation is sustainable.                                                 |
| 6b    | Threatened          | The language is used for face-to-face communication within all generations, but it is losing users.                                                      |
| 7     | Shifting            | The child-bearing generation can use the language among themselves, but it is not being transmitted to children.                                         |
| 8a    | Moribund            | The only remaining active users of the language are members of the grandparent generation and older.                                                     |
| 8b    | Nearly Extinct      | The only remaining users of the language are members of the grandparent generation or older who have little opportunity to use the language.             |
| 9     | Dormant             | The language serves as a reminder of heritage identity for an ethnic community, but no one has more than symbolic proficiency.                           |
| 10    | Extinct             | The language is no longer used and no one retains a sense of ethnic identity associated with the language.                                               |
