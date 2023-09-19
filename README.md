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

**. Volume** 
     The volume of Big data is too large so that it is not capable of fitting in a particular  single machine, we define the volume of big data is vast and many specialized tools and frameworks are required to both store and visualize the process in the data

**. Velocity**
      Velocity in big data refers to the movement of the data that is created and used, data is being generated by very large sources of data hence the velocity of the data generated might be high, also certain sources of data highly produce rapid movements in data, consider the example of social media data, email data, etc

**. Variety**
     It represents the forms of data, we have three forms of data like :
     **_Structured_**
     **_Unstructured**
     **_Semi_structured**
         
**. Variability**
      There are certain cases of consistency and inconsistency in data, and the data will be inconsistent in certain cases, such cases need managing and handling with care. For example, social media data is highly sensitive and private it requires certain data management handling techniques whereas data produced by sensors will be inconsistent
      
**. Veracity**
     It refers to the quality of data and verifies whether the data is accurate or not. To get particular values from the data we need to clean the data set and remove the unnecessary part.
     
**. Value**
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

 **Acquisition/Recording**
 
  1. Data is generated from many sources like IoT/Sensors/Computing/Social media etc.
  2. Some data might not have a lot of importance and the important data can be filtered and compressed by some orders of magnitude
  3. Certain filters have to be designed for cleaning.
  4. Storing the right information when the data has been created or so
       . Example - Storing of pictures in devices

  **Extraction and Cleaning**

  1.**_Information extracting_** : Extracting the information from the sources and express it in a structural form
  2.**_Data Cleaning_** : Attempting to clean the data set , fill the null values and remove the noise values

  **Data Integration**

  1.Data Integration : Merging from multiple resources
  2.Data Representation : Using various techniques of visualization like plotting graphs suchs as charts,histogram,bar,boxplots etc

  **Data Analysis**

  1.Query Process : 











