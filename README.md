# DRAFT-Temporary US Exhibitions of Historical Islamic Art 1914-2020 - Dataset
In 2024, XXX and XXX compiled a research dataset of all documented temporary exhibitions of pre-Modern Islamic Art held in the United States (US) from 1914 to 2020 with the goal of understanding the exhibition history of Islamic Art in the US. This research is based in part on XXX's 2022 dissertation XXX.

The dataset **Temporary US Exhibitions of Historical Islamic Art 1914-2020 - Dataset.csv** is hosted here in this Github repository in csv format and on **tableau public**, along with multiple interactive data visualizations. 

## How this Dataset was Compiled

By the term pre-Modern Islamic art, we mean art made in the Islamic world prior to the nineteenth-century and the globalization of Euro-American conceptions of art and aesthetics, similar to the division before and after the early twentieth century (i.e. modern/contemporary) employed by Susan Sinclair, the editor of the *Bibliography of Art and Architecture in the Islamic World* (2012). Sinclair's section “Museums, Libraries & Galleries; Collectors & Collections; Exhibitions; Auctions; Foundations & Institutions,” (pp. 32-60) served as a starting point. Past exhibitions listed on websites of art galleries and museums of note were reviewed, as well as those on Art-Collecting.com and Google maps. Exhibition titles incorporating the terms Muslim, Islamic or names of key dynasties were selected, but if the focus of an exhibition was not obvious, it was further researched to determine whether it included "Islamic" art. Only temporary exhibitions were included.

## Dataset Fields

The fields for the data set are as follows:

|Field Name|Type|Description|Example|
|----------|:--:|---------|------:|
|COUNTRY|String|Name of country.|US|
|STATE|String|Abbreviated name of state.|NY|
|PARTISAN-LEAN|Number|The degree to which a state leans towards the Republican or Democratic party based on a blend of presidential and state-legislative results in congressional and gubernatorial elections and based on [FiveThirtyEight's Partisan Lean dataset 2022](https://github.com/fivethirtyeight/data/tree/master/partisan-lean) (CC 4.0). Democratic leans are positive numbers, while Republican leans are negative numbers. A number is entered only for the initial occurence of the state.|13.20919|
|CITY|String|Name of city. Each instance is numbered to achieve desired tableau visualization.|New York|
|DATE-BEGIN|Date|Begin date for exhibition (M/D/Y). When only month is known, the first of the month is used. When only the year is known the January 1st is used.|3/1/1914|
|DATE-END|Date|End date for exhibition (M/D/Y). When only month is known, the first of the month is used. When only the year is known the December 31st is used.|4/1/1914|
|DAYS|Number|Number of days exhibition was held.|85|
|INSTITUTION|String|Name of exhibiting institution. Initial article "The" is is removed from instituion names. University/college galleries or museums have their parent educational institutions' names appended at the end unless included in the exhibiting instittion's names. For large gallery or museum organizations, the umbrella name is used.|Smithsonian|
|TITLE|String|Title of Exhibition. Alternate titles or additional information such as the names of private collectors are added in [square] brackets. Travelling exhibitions with the same name are differentiated with square bracketted numbers appended to the title.|The Emperor's Carpet Lent by Edith Rockefeller McCormick [Collection]|
|MEDIA|String|Predominant type of media of works exhibited. For shows with various media, "Material Culture" is used.|Textiles|
|TRAVELLING|String|Whether the exhibition travelled to other locations or not (Yes/No)|Yes|
|INSTITUTION-DIVISION|String|Subdivision of institution hosting exhibition.|National Museum of Asian Art - Freer Gallery of Art|
|URL-SUMMARY|URL|Link to summary of exhibition, typically to gallery or museum website.|https://harvardartmuseums.org/exhibitions/5231|
|URL-CATALOGUE|URL|Link to catalogue reference or digital copy, typically to gallery or museum website, Worldcat, and/or archive.org|https://harvardartmuseums.org/exhibitions/2594|

## Tableau
The **tableau public** dataset and visualizations are available [here](https://public.tableau.com/views/TemporaryUSExhibitionsofHistoricalIslamicArt1914-2020/Chronology?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link]).

![Clipboard01](https://github.com/user-attachments/assets/9870a8c7-3b14-43f4-b6ae-6d89bc813bb4)

## Feedback
Every effort has been made to ensure the dataset is complete accurate. If you notice an error or omission, or you have used this dataset in your work please inform us at ??????.

## Cite this Dataset

#### Chicago-style NOTE
XXX and XXX, *Temporary US Exhibitions of Historical Islamic Art 1914-2020 - Dataset*, 2024, distributed by darc | digital art history research collective, https://github.com/darcideas/islamic-art-exhibitions-us/.

#### Chicago-style BIBLIOGRAPHIC ENTRY
XXX and XXX. *Temporary US Exhibitions of Historical Islamic Art 1914-2020 - Dataset*, 2024. Distributed by darc | digital art history research collective. https://github.com/darcideas/islamic-art-exhibitions-us/.

## Works Citing this Dataset

## Licence
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/darcideas/islamic-art-exhibitions-us/">Temporary US Exhibitions of Historical Islamic Art 1914-2020 - Dataset</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/darcideas">XXX and XXX</a> is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p> 
