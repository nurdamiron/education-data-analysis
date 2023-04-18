# missing-analysis

## About Dataset
### Context

####This is official open data from The Ministry of Internal Affairs of the Russian Federation on missing and wanted people, identified and unindentified corpses. Original data available here source.
Content

### File meta.csv - contain information about data source and contact information of original owners in Russian.

### File structure-20140727.csv - describe datastructure in Russian. Main things that you need to know about data columns are here:

    "Subject" - The official name of the subject of statistical reporting. That's Russian regions, note that Crimean Federal District and city ​​of Sevastopol are included.

    "Point FPSR" - Item of the Federal Statistical Work Plan. You don't need to know this.

    "Name of the statistical factor" - this one speaks for itself. Available factors:

    -- Identified persons from among those who were wanted, including those who disappeared from the bodies of inquiry, investigation, court.

    -- Total cases on the identification of citizens on unidentified corpses that were on the register.

    -- Total wanted persons, including those who disappeared from the bodies of inquiry, investigation, court.

    -- Identified persons from among the wanted persons, including those missing.

    -- Total wanted persons.

    -- Number (balance) of unreturned missing persons in relation to 2011 (%)

    -- Number (balance) of unresolved criminals against 2011 (%)

    -- Total discontinued cases in connection with the identification of the person

    -- Total wanted persons, including those missing

    -- Identified persons from the number of wanted persons

    "Importance of the statistical factor" - value of correspondent statistical factor.

Files data-%Y%m%d-structure-20140727.csv contain actual data. Names of the files contain release date. Data aggregated by quarters of each year, for example
data-20150127-structure-20140727.csv - data for whole 2014 year
data-20150627-structure-20140727.csv - data for Q1 and Q2 of 2015

File translate.csv is used to simplify translation from Russian to English. See usage in the kernel.
Acknowledgements

Thanks to newspaper Komsomolskaya Pravda for bringing up the issue of missing kids in Russia.

Thanks to Liza Alert - Volunteer Search and Rescue Squad for efforts in rescue of missing people in Russia.

Photo by Alessio Lin on Unsplash
Inspiration

Missing people, especially kids, is a serious problem. However there is not much detailed information about it. Russian officials provide overall information without detalisation of victim's age. As a result many speculations appear in media on this topic:

    Last year about 200,000 reports of missing people were filed with police in Russia.
    45,000 kids lost every year
    More than 15,000 kids lost every year
    Radio interview - starting from minute 7:55 main point: "More
    than 15K kids lost completely, i.e. was not ever found"

Some insights to official data can be found here interview, year 2012: "Annually in Russia about 20 thousand minors disappear, in 90% of cases the police find children".

Still there is no information about kids in recent years. If you have any reliable sources, please share.
