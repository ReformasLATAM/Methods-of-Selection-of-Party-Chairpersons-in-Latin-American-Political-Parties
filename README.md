# Methods of Selection of Party Chairpersons in Latin American Political Parties 

Welcome to the GitHub repository of the database "Methods of Selection of Party Chairpersons in Latin American Political Parties," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

The database contains information on the selection methods that political parties in Latin America implement to appoint their authorities. 

The information collection was conducted by examining the statutes from a sample of 54 political parties in Latin America. The main focus was on reviewing the statutory rules concerning the selection methods of party authorities. 

The regulation of the internal party authorities selection process refers to the statutory rules that establish the type of methods and procedures that political parties can implement to select their authorities. The database contains information on statutory articles stipulating the methods, whether the party chairpersons belong to the national executive committee as well as on the methods and bodies to carry out the selection process. 

Members of the Observatory of Political Reforms in Latin America collected and coded the information. The information collection manager is Carlos Guadarrama Cruz (FES Acatlan, UNAM, Mexico), the information coding managers are Carlos Guadarrama Cruz (FES Acatlan, UNAM, Mexico); Jazmín Jimena Álvarez Enríquez (FES Acatlan, UNAM, Mexico) and Karla Estrada López (FES Acatlan UNAM, Mexico).

## Description

The directory `./Data/` contains the file `./Data/DD_SPP` where all relevant information regarding the database linked to the selection methods of presidential candidates in Latin American political parties is located. Specifically, the database consists of the following variables:

-   `country`: Name of the country where the reform regarding the selection method for party chairpersons was implemented.

-   `cowcode`: Country according to the “Correlates of War” coding available at 
https://correlatesofwar.org/data-sets/cow-country-codes.

-   `country_code`: Country code according to the three-letter ISO code (e.g. ARG, MEX, SAL) available at http://utils.mucattu.com/iso_3166-1.html 

-   `party_id`: Numeric key  to identify each of the 54 political parties in the database. The number consists of the country number and the party number per country. 

-   `party_id`: Acronyms of each of the 54 political parties in the database, according to party documentary sources. 

-   `statute_year`: Indicates publication year of political parties statutes between 1996 and 2021, from which internal rules regarding the selection of party authorities in national leadership bodies were reviewed. If the information is not available, the number -9999 is used.

-   `statute_article`: Indicates the article number of the political party statutes where rules for the selection of party authorities are established. If the information is not available, the number -9999 is used.

-   `nec_member`: Records whether the party’s chairperson is a member of the National Executive Committee (NEC) of the political party. Its values are: No [0]: Party authorities are not members of the NEC. Yes[1]: Party authorities are members of the NEC. 

-   `selection_method`: Indicates the method of selection of party authorities according to the  political parties’ statutes. Its values are: Convention or Assembly [1]: The statutes establish that party authorities are selected through an organization convention or assembly. Closed internal elections [2]: The statutes establish that party authorities are chosen through direct voting by the organization's members. Board of Notables [3]:The statutes establish the selection of party authorities to a select group of individuals within the organization. Undetermined [99].

-   `selection_body`: Indicates the specific leadership bodies established in the party statutes. Its values are: Assembly[1]: party statutes establish national assemblies or their equivalents  as one of the party authority leadership bodies. Internal election [2]: party statutes designate internal elections or their equivalents as one of the party authority leadership bodies. Board of Directors [3]: party statutes designate boards or their equivalents as one of the party authority leadership bodies. Convention [4]: party statutes designate conventions or their equivalents as one of the party authority leadership bodies. Committee [5]: party statutes designate National Executive Committees or their equivalents as one of the party authority leadership bodies. Council [6]: party statutes designate National Political Councils or their equivalents as one of the party authority leadership bodies. Undetermined [99].

## Citation

``` r
Freidenberg, Flavia. Dir., 2023, “Methods of Selection of Party Chairpersons in Latin American Political Parties” Observatory of Political Reforms in Latin America (1978-2023). Mexico City. Institute for Legal Research (IIJ-UNAM) and Washington, D.C.: Secretariat for Strenghtening Democracy of the Organization of American States (SSD/OAS), V1. DOI: https://doi.org/10.5281/zenodo.7922194
```