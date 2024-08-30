# DRAFT-Temporary US Exhibitions of Historical Islamic Art 1914-2020 - Dataset
In 2024, Dr. Chelsea Baumgartner (Independent Scholar) and Dr. Hussein Keshani (UBC) compiled a research dataset of all documented temporary exhibitions of pre-Modern Islamic Art held in the United States (US) from 1914 to 2020 with the goal of understanding the exhibition history of Islamic Art in the US. This research is based in part on Dr. Baumgartner's 2022 dissertation ["Queer contemporary artists of Muslim heritage in the United States and Canada : art, display, and reception."](https://dx.doi.org/10.14288/1.0415869)

The dataset is hosted here in this Github repository in csv format and on **tableau public**, along with multiple interactive data visualizations. 

## Dataset Fields

The fields for the data set are as follows:

|Field Name|Type|Description|Example|
|----------|:--:|---------|------:|
|COUNTRY|String|Name of country.|US|
|STATE|String|Abbreviated name of state.|NY|
|PARTISAN LEAN|Number|The degree to which a state leans towards the Republican or Democratic party based on a blend of presidential and state-legislative results in congressional and gubernatorial elections, using [FiveThirtyEight's Partisan Lean dataset 2022](https://github.com/fivethirtyeight/data/tree/master/partisan-lean) (CC 4.0). Democratic leans are positive numbers, while Republican leans are negative numbers. A number is entered only for the initial occurence of the state.|13.20919|
|CITY|String|Name of city. Each instance is numbered to achieve desired tableau visualization.|New York|
|DATE_BEGIN|Date|Begin date for exhibition (M/D/Y). When only month is known, the first of the month is used. When only the year is known the January 1st is used.|3/1/1914|
|DATE_END|Date|End date for exhibition (M/D/Y). When only month is known, the first of the month is used. When only the year is known the December 31st is used.|4/1/1914|
|INSTITUTION|String|Name of exhibiting institution. If the initial article "The" is used, it is removed. University/college galleries or museums have their parent educational institutions' names appended at the end unless included in the gallery or museum names. For large gallery or museum organizations, the umbrella name is used.|Smithsonian|
|TITLE|String|Title of Exhibition. Alternate tiles or additional information such as the names of private collectors is added in [square] brackets.  

## Tableau
The **tableau public** dataset and visualizations are available [here](https://public.tableau.com/views/TemporaryUSExhibitionsofHistoricalIslamicArt1914-2020/Chronology?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link]).

## Cite this Dataset

## How this Dataset was Compiled

## Feedback

## Works Citing this Dataset

## Licence

