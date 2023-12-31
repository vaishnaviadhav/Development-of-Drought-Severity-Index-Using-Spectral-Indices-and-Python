# Development of Drought Severity Index (DSI) for Drought Monitoring using different Spectral Indices and Python Programming Language

## Problem statement

A drought is one of the most common environmental calamities that have occurred in almost all climatic regions and caused huge damage to the economy of several countries and caused a high number of deaths to livestock population. The Godavari and the Krishna rivers flows through the states of Andhra Pradesh and Telangana in peninsular India. In spite of this fact, these both the regions suffering from a drought. 70% of the population of Andhra Pradesh lives in rural areas and relies on agriculture for their livelihoods. Not only does agriculture contribute to the economy of a state but it also brings food security to the state and to the country as well. A large portion of the population employs themselves indirectly in agro-based occupations. Arid climatic circumstances caused by irregular rainfall patterns and consecutive drought years in the states of Andhra Pradesh and Telangana, along with extreme industrialization and mining negatively impacts produce levels, which have made droughts a more frequent threat.

## Objectives

- To establish a drought monitoring index that can provide near real time information and impacts on a regional basis.
- To estimate the intensity and pattern of agriculture drought by major spectral indices using remote sensing, python programming language, and meteorological data.
- To analyse spatio-temporal pattern of drought severity, and comparison among the years.

## Area of Interest

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/d2c86997-b599-41be-90ef-2b8d1c8d649c)

## Methodology

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/4518f169-70d6-4092-8e44-d079aed4603d)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/52049a24-35a2-4065-8f30-6f0090de0b98)

## Python in Drought Monitoring

Data preparation in python

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/dac55330-0dc7-47b3-970b-912f65b34974)

Reading of raster data arrays

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/cddeeb70-c47b-42c1-b69a-800a831c0906)

Application of Band Math

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/b3793001-6089-4409-aa46-52da752aafa3)

## Visualization of the result

Visualization of VCI

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/83ac659f-ca94-491f-b3ce-12f13868d26e)

Visualization of TCI

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/4b628cf3-3a7f-4af6-a1da-4f21aed4ca03)

Visualization of PCI

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/5deaec74-b6b1-4e5d-90b2-f518ef13dd45)

## Results

Vegetation Condition Index (VCI)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/8423df4f-6308-4197-9a24-a4c04d80273f)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/e24acc0d-d421-4bdf-9fcf-32e7a39a7250)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/7e390f66-cb2a-4a91-8c1e-4a338361a933)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/051ddd5f-444f-4bf0-8fde-021d9c26dfa5)

Temperature Condition Index (TCI)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/acd5de8d-0674-4f78-ae61-f36f11ad6b8f)

Precipitation Condition Index (PCI)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/d756ebd9-219a-4d39-8353-babbb09fcc94)

Drought Severity Index (DSI)

The Drought Severity Index (DSI) is calculated by the major parameters such as NDVI, temperature, and precipitation condition of the interested region. The main three index of the study which are VCI, TCI, and PCI are generated by using these three major parameters. These three generated indices are then converted into thematic data layer. That means they are converted into percentile format for the representation. After that weighted overlay analysis is performed on these three results to get the final result as Drought Severity Index (DSI). Weighted analysis is done to reclassify the cells on input raster image into a common evaluation scale of suitability. A DSI map shows condition severity of the region. Here, in this study, this map shows the severity of a drought in the area of interest. This is the thematic map of DSI which indicates the unique colour to the specific condition of the severity. For example, red colour indicates very poor condition of severity in the region, orange colour indicates poor severity condition in the states, light green colour indicates moderate amount of drought severity in the state, dark green colour indicates good amount of health condition in these two states.

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/f8c4c4ab-a28b-43c2-a3bc-d1879abc4965)

## Validation with the result

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/6943d88d-7ef1-4ed5-b6db-4c179a3ea4b8)

![image](https://github.com/vaishnaviadhav/Development-of-Drought-Severity-Index-Using-Spectral-Indices-and-Python/assets/71253152/0e64b9b9-3304-4be8-b0ba-27bd83bf6cfe)

In the above-mentioned map, the first image shows DSI and the second image shows the % sown within the area. As described above, the DSI represents that the north-eastern area of the state Andhra Pradesh which is known as the region of Coastal Andhra and one of the eastern districts of Telangana state has major drought severity, whereas, looking after the same area very less i.e., less than 75% of crop seeds sowing has been done in the current year. Dominance of good condition with respect to drought severity can be observed in the Rayalaseema area of the state Andhra Pradesh, similarly, can be seen in the map of % sown area which had 75% to more than 100% of sowing done.

## Conclusions

The study of developing the Drought Severity Index (DSI) using major spectral indices and with the help of python programming language is done to monitor and analyse the severity condition of drought in the interested area. During the study, it is observed that few research papers, articles, study, thesis, and citations have been made for drought analysis using python programming language. As mentioned earlier, python is the OOP, easy to learn and read, easy to interpret, and interactive programming language. Hence, a small attempt has been made in this study to develop the DSI using the programming language. This python code can be used to monitor any remote sensing data and calculate mentioned spectral indices. It is very easy and convenient method to monitor drought conditions. It doesn’t even require huge data or complex data structure, and advanced GIS software.

After developing a python code and running on the system, all the condition indices such as VCI, TCI, and PCI can be seen already stored in the given path of the system. By these three major condition indices and weighted overlay analysis, DSI is made and validated with the % sown area afterwards.

Overall, by this study, it is observed that Andhra Pradesh and Telangana states suffered from drought in the year 2015. But Rayalaseema and Uttar Andhra regions of state Andhra Pradesh except Coastal Andhra region and some parts of Telangana state received optimal amount of rainfall in the current year such as in 2020. The Coastal Andhra region received very low rainfall and also suffered by extreme temperature in the region at the same season. Thus, the Coastal Andhra region of Andhra Pradesh hit by drought severity condition in 2020. Therefore, it can be said that Coastal Andhra region of the state suffered from agriculture drought in the current year 2020. 

The drought severity of the region is very important to know for farmers for sowing of crop seeds and good amount of crop yield productivity. Thus, it can be beneficial to them financially and physically.
