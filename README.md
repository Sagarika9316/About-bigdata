## About-bigdata
### Big Data With Examples and Types
1. Structured

2. Unstructured

3. Semi-structured

**_Structured_**

Data that has a set format for efficient access by both software and people is referred to as structured data. Typically, it is tabular with clearly defined rows and columns for data properties.

#### Examples

Tables, Relational Databases, XML, JSON

| Sno | Name | Age |
| --- | ---  | --- |
| 1   | John | 30  |
| 2   | Jane | 25  |
| 3   | Bob  | 35  |



**_Unstructured_**

Unstructured data, which includes emails, text messages, photos, videos, and audio files, is all the information that isn't predetermined and searchable in a table. Unstructured data cannot be immediately evaluated and searched without additional processing, in contrast to structured data, which can be easily inserted into tables like those available in Microsoft Excel.

#### Examples

Books, Journals, Documents, metadata, audio, videos

**_Semi-structured_**

The phrase "semi-structured data" (also known as "partially structured data") describes a class of data that does not follow the tabular structure present in relational databases or other types of data tables, but does have tags and metadata that separate semantic elements and create hierarchies of records and fields. 

#### Examples

Email

### 6 V's of Big Data

. Volume

. Velocity

. Variety

. Variability

. Veracity

. Value

![newimage](https://github.com/Sagarika9316/About-bigdata/assets/89766169/3081fcfc-e84a-4ee9-b5b8-9fb8b74c7a8f)

**_. Volume_** 
     The volume of Big data is too large so that it is not capable of fitting in a particular  single machine, we define the volume of big data is vast and many specialized tools and frameworks are required to both store and visualize the process in the data

**_. Velocity_**
      Velocity in big data refers to the movement of the data that is created and used, data is being generated by very large sources of data hence the velocity of the data generated might be high, also certain sources of data highly produce rapid movements in data, consider the example of social media data, email data, etc

**_. Variety_**
     It represents the forms of data, we have three forms of data like :
     **_Structured_**
     **_Unstructured**
     **_Semi_structured**
         
**_. Variability_**
      There are certain cases of consistency and inconsistency in data, and the data will be inconsistent in certain cases, such cases need managing and handling with care. For example, social media data is highly sensitive and private it requires certain data management handling techniques whereas data produced by sensors will be inconsistent
      
**_. Veracity_**
     It refers to the quality of data and verifies whether the data is accurate or not. To get particular values from the data we need to clean the data set and remove the unnecessary part.
     
**_. Value_**
     Value is nothing but the usefulness of data for a particular purpose. The final goal might be the usage of any big data analytics system to extract valuable insights from the data.
     
## Phases of Big Data Analysis.
```mermaid
stateDiagram-v2
   [*] --> Acquisition/recording
   Acquisition/recording --> Extraction Cleaning/Annotation
   Extraction Cleaning/Annotation --> Integration
   Integration --> Analysis
   Analysis --> Interpretation
```

 **_Acquisition/Recording_**
 
  1. Data is generated from many sources like IoT/Sensors/Computing/Social media etc.
  2. Some data might not have a lot of importance and the important data can be filtered and compressed by some orders of magnitude
  3. Certain filters have to be designed for cleaning.
  4. Data acquisition has been understood as the process of gathering, filtering, and cleaning data before the data is put in a data warehouse or any other storage 
     solution[1]
  5. Storing the right information when the data has been created or so
       . Example - Storing of pictures in devices

  **_Extraction and Cleaning_**

  1.**_Information extracting_** : Extracting the information from the sources and express it in a structural form
  2.**_Data Cleaning_** : Attempting to clean the data set , fill the null values and remove the noise values

  **_Data Integration_**

  1.**_Data Integration_** : Merging from multiple resources
  2.**_Data Representation_** : Using various techniques of visualization like plotting graphs suchs as charts,histogram,bar,boxplots etc

  ETL is the general workflow of prepping data for analysis, whether it be big or small, integrated or siloed. Because it is a fairly generic term, it is scalable to 
  big data.[2]

  **_Data Analysis_**

  1.**_Query Process_** : Query is a way to get useful data subsets by some process like abstract modellingand standardizing them to one another
        .Exammple - Database modelling, semantic data modelling

  2.**_No SQL_** : Certain methods in big data and queries cannot only be done by SQL queries we have to use no sql in such cases

  My favorite NO SQL  workspace is [Neo4j](https://neo4j.com/)

  **_Interpretation_**

  Interpreting the data and verifying the results produced by the computer, for interpreting the data visualizations help a lot, after the interpretation it is ready to make decision making 

  ### Challenges in big data 
  Following are the challenges in big data:
  1. Privacy
  2. Scaling
  3. Timeline
  4. Incompleteness
  5. Human Collaboration

     **_Privacy_**
     The biggest challenge that ever comes into mind is privacy concern, a lot of information is being observed and grasped by viewers on social media, this can be a 
     present and future concern
     Big data in healthcare,lot of concern on privacy concern in health department since the information of patient keeping secretive is quite questionable
     All ethics and Privacy concerns must be known to every one in the big data field
    In generating Big Data, it is important to ensure that the information is securely collected, processed, transmitted, stored, and accessed in accordance with 
     established rules.[3]

     For more information on  privacy concerns of big data and some solutions[4]*click on the image below **_visit this_**
     [![Privacy concerns in Bigdata](https://tse1.mm.bing.net/th?id=OVP.-pi2Yb0bJe0gGqJGNrm1ZQHgFo&pid=Api&h=360&w=480&c=7&rs=1)](http://www.youtube.com/watch?v=y8yMlMBCQiQ)


     

     **_Scaling_**
     
     As the data increases and getting adopted to newer technologies is nothing but increasing the hard disk space!!
     And yeah data volume increases faster and scaling is necessary, changing storage subsystem potentially touches every aspect of data processing too

     **_Timeliness_**
     
     All things have deadliness and analysis and decision-making making is quite important,if there is a huge data set cleaning is a must, one cannot skip the step and it takes much time to even clean the data.
     And some problems of cleaning data and searching for the appropriate answer require a huge time. There is a need for new index strategies that are need based on the features

     **_Incompleteness_**
     
     The ubiquitous problem of data sets lacking all the information necessary for thorough analysis or decision-making is referred to as the "big data incompleteness challenge." Big data frequently contains missing, 
     incorrect, or out-of-date data, which can result in imprecise insights and incorrect conclusions. To address this issue and improve data quality, advanced data cleaning and imputation approaches are required. It 
    also emphasizes the significance of data governance and validation procedures for reducing the influence of incomplete data on the accuracy and dependability of analytical results in the age of big data analytics.

### References

[1]Lyko, K., Nitzschke, M., & Ngomo, A. N. (2016). Big data acquisition. In _Springer eBooks_ (pp. 39–61). https://doi.org/10.1007/978-3-319-21569-3_4

[2]Allen, R. (2023, September 6). _Big Data Integration In 2023 | Challenges, Tasks & Tools._  https://www.selecthub.com/big-data-analytics/big-data-integration/

[3]Bentotahewa, V., Hewage, C., & Williams, J. (2021). Solutions to big data privacy and security challenges associated with COVID-19 surveillance systems._Frontiers in Big Data_, 4. 
https://doi.org/10.3389/fdata.2021.645204

[4]THINKR.(2013)._Dangers of Big Data_.Youtube.https://www.youtube.com/watch?v=y8yMlMBCQiQ












