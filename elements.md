# CH Digital Collections Element Details

Each element is presented in a table format under Element Details. Directly below is an description of each field in this table template.

| Element:              | *Metadata element name*                                                         |
|-----------------------|---------------------------------------------------------------------------|
| **Description**           | *General overview of element*                                               |
| **Obligation**            | *Element use requirement; Required, Mandatory (if applicable), or Optional* |
| **Repeatable?**           | *Ability to include more than one instance of the element*                 |
| **Range**                 | *Data type or value*                                                        |
| **Input Guidelines**      | *How to specifically populate the element field*                            |
| **Controlled Vocabulary** | *Suggested vocabularies to populate the element field. See the [Controlled Vocabularies](/./controlledvocabs.md) for more details on how these are utilized.*                      |
| **Example(s)**            | *Sample inputs from the specific element field*                             |

## Element Details

|**Element:**|Asset Type                                                         |
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Format of described resource based on technical characteristics|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text|
|**Input Guidelines**|Automatically generated by system based on file type|
|**Controlled Vocabulary**|DCMI Type Vocabulary, ebu_MediaTypeCS|
|**Example(s)**|Image; Audio|

|**Element:**|Content Type|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Specific and explicit definition of what is represented in the resource|
|**Obligation**|Required|
|**Repeatable?**|Yes|
|**Range**|Controlled text string|
|**Input Guidelines**|The type of asset or what the asset depicts. For example, the content type can be as concrete as "flyer" or "3-sheet," or it can describe the specific event taking place with keywords such as "interview" or "workshop recording."|
|**Controlled Vocabulary**|PBCoreAssetType Vocabulary, PBCore @descriptionType Vocabulary, ebu_ContentGenreCS, ebu_EditorialFormatCodeCS|
|**Example(s)**|event image; program page|

|**Element:**|System ID                                                         |
|-----------------------|---------------------------------------------------------------------------|
|**Description**|System-generated ID of described resource|
|**Obligation**|Required (automated)|
|**Repeatable?**|No|
|**Range**|Identifier|
|**Input Guidelines**|Automatically generated by system|
|**Example(s)**|CH1378771|

|**Element:**|Department|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Carnegie Hall Department that mediates access to the resource and for whom the resource is intended or useful|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|The field must be populated to determine an asset's usage, visibility, and rights|
|**Example(s)**|Rose Museum and Archives; Public Relations|

|**Element:**|Height|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Height of digital resource|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Automatically generated by system|
|**Example(s)**|360px|

|**Element:**|Relationship Indicator|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Relationship field that links a resource to an event record or to a collection|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Associates asset to a record representing: an event described in [CH's performance history](http://data.carnegiehall.org/); a named archival collection; or a specific department, program, or project. Current system implementation is the asset exists in a folder representing one of the concepts described. The system field which establishes this link is populated with folder name or specific event identifier pertaining to the asset.|
|**Example(s)**|Louis Salter Collection; Artist Management Provided Images; [Jazz at the Philharmonic](http://data.carnegiehall.org/events/41777/about) (March 26, 1967 performance in the Main Hall featuring Ella Fitzgerald, Duke Ellington, and others) |

|**Element:**|Purpose|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|A class of entity for whom the resource is intended or useful|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Assets are automatically assigned the purpose "Pending Process" upon ingest. Administrator upgrades the purpose based on usage and rights.|
|**Example(s)**|Pending Process; For Staff Reference Only|

|**Element:**|Size|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Extent, height, width, and file size of digital resource|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Automatically generated by system|
|**Example(s)**|490px by 360px; 5MB; 26 pages|

|**Element:**|Source|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Person, organization, or service responsible for contributions to defined resource|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Includes photographers, lendors, institutions, organizations, etc.|
|**Example(s)**|Carnegie Hall Archives|

|**Element:**|Subtype|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Functional field that dictates how descriptive information is presented to the user|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Automatically generated by system, but editable where necessary. Most visual assets will be assigned "default image," but can be edited to reflect specific subtypes such as "flyer."|
|**Controlled Vocabulary**|DCMI Type Vocabulary|
|**Example(s)**|Default Image; Flyer|

|**Element:**|Title|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Primary name given to described resource|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Format as performer or event name. For archival assets, include the date (Month Day, YYYY).|
|**Controlled Vocabulary**||
|**Example(s)**|New York Philharmonic; Carnegie Hall exterior, 1900|

|**Element:**|Width|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Width of digital resource|
|**Obligation**|Required|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Automatically generated by system|
|**Controlled Vocabulary**||
|**Example(s)**|490px|

|**Element:**|Approval Conditions|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Information about who can access the resource or its security status|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Used to clairify or specify rights and usage statuses. Populate with an explanation of why an asset is approved or not approved, a range of dates for an asset's usage, or specific approval instructions not already clarified by the usage field.|
|**Example(s)**|Contact Public Relations before use; Image to only be used for 2017-2018 season|

|**Element:**|Archives Unique ID|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Carnegie Hall Archives ID of the physical version of the described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Populate with exact formatted ID|
|**Example(s)**|CHA-FL-02923_001|

|**Element:**|Carnegie Hall Archives Collection|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Carnegie Hall Archives Collection of which described resource is a part|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|Yes|
|**Range**|Controlled text string|
|**Input Guidelines**|Only populate for assets managed by the Carnegie Hall Archives. [List of collections](https://www.carnegiehall.org/About/History/Archives/Collections-Overview) represents both general and named collections. |
|**Example(s)**|Photographs Collection; Programs Collection|

|**Element:**|Copyright|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Information about rights held in and over described resource, including more specific contributor or creator rights|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Populate this field with text exactly as it should read, including the "©" and any associated year or date where appropriate. Includes photographer copyright. |
|**Example(s)**|©Carnegie Hall; Photo by Carnegie Hall Corporation|

|**Element:**|Date|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Date depicted in or by the defined resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Date|
|**Input Guidelines**|Only populate this field if the asset pertains to a specific date|
|**Controlled Vocabulary**|ISO 8601|
|**Example(s)**|43013|

|**Element:**|Date (Free Text)|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Temporal date(s) of described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Populate with date information that is not implied by Date, Season, or Date (Year), such as a known range of dates pertaining to the asset, a month and year combination (if the specific day and formatted date is unknown), an "undated" or "date unknown" clause, etc.|
|**Example(s)**|August 1980; May 5, 1891 through May 8, 1891|

|**Element:**|Date (Year)|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Year of the described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Populate as YYYY|
|**Example(s)**|2018|

|**Element:**|Description|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Textual account of described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Recommended for entering descriptive information not present in other fields. Do not populate this field with any general notes or internal notes.|
|**Example(s)**|This photograph shows the interior of Carnegie Hall as it appeared for the November 1, 1949 recital of tenor Miklos Gafni.|

|**Element:**|Digital Accession Date|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Date resource was uploaded/ingested to Carnegie Hall to provides a clear delineation point for the assumption of responsibility for the digital content's preservation. |
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Date|
|**Input Guidelines**|For migrated assets, populate with the date of original ingest into previous system or storage environment. |
|**Controlled Vocabulary**|ISO 8601|
|**Example(s)**|2018-04-11|

|**Element:**|Legacy Filename|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Previous filename of described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Populate with filename from previous system or filename other than Original Filename (filename upon ingest)|
|**Example(s)**|CHA-FL-00402_001.jpg|

|**Element:**|Production Keyword|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Production status of described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Only applies to audio/video assets. This field is highly recommended for video and audio assets, as it will group together assets in specific production stages.|
|**Controlled Vocabulary**|PBCore instantiationGenerations Vocabulary|
|**Example(s)**|demo; indexed by work|

|**Element:**|Season|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Temporal date range of described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|As determined by concert season, which begins in September and ends in August.|
|**Example(s)**|1891-1892|

|**Element:**|Source ID|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Original, legacy, or source-generated ID of described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Populate with original source IDs (not original filenames) from other systems, databases, etc.|
|**Example(s)**|OLD86700|

|**Element:**|Usage|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Information about approval and use ratings of resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Affects an asset's visibility and users. Recommended when a specific approval is known (not estimated).|
|**Example(s)**|artist rejects use of image; approved|

|**Element:**|Venue|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Event location associated with or depicted by described resource|
|**Obligation**|Mandatory (if applicable)|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Includes event locations within Carnegie Hall (including historic venue names) and external venues|
|**Example(s)**|Isaac Stern Auditorium / Ronald O. Perelman Stage; Zankel Hall; Knockdown Center; Carnegie Lyceum|

|**Element:**|Internal Notes|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Internal-facing notes pertaining to the described resource|
|**Obligation**|Optional|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Use for internal-only notes, excluding approval condition notes. Notes in this field will not be visible to public users, but are visible to Carnegie Hall staff members.|
|**Example(s)**|Provided via email to the Archives; Original TIFF image contained this and another ticket stub in the same scan|

|**Element:**|Keywords|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Content depicted by the described resource|
|**Obligation**|Optional|
|**Repeatable?**|Yes|
|**Range**|Controlled text string|
|**Input Guidelines**|Populate to increase searchability of specific content, programs, projects, etc.|
|**Controlled Vocabulary**|LCSH|
|**Example(s)**|children; audience|

|**Element:**|Language|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Language(s) of described resource|
|**Obligation**|Optional|
|**Repeatable?**|Yes|
|**Range**|Controlled text string|
|**Input Guidelines**|Populate for audio, video, or textual assets|
|**Controlled Vocabulary**|ISO 639-3|
|**Example(s)**|English; French|

|**Element:**|Names|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Entities featured as content of the resource|
|**Obligation**|Optional|
|**Repeatable?**|Yes|
|**Range**|Controlled text string|
|**Input Guidelines**|Populate with performance and non-performance entities, such as artists, speakers, designers, board members, etc., associated with the asset|
|**Controlled Vocabulary**|LCNAF|
|**Example(s)**|New York Philharmonic; Frank Sinatra (1915-1998)|

|**Element:**|Notes|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Notes pertaining to the described resource|
|**Obligation**|Optional|
|**Repeatable?**|No|
|**Range**|Free-text|
|**Input Guidelines**|Populate with public-facing notes, such as notes that do not specifically pertain to an asset's description or to another tagging field, but are nonetheless important. For example, include in this field notes about the physical asset, such as copies or similar materials available.|
|**Example(s)**|60s Festival Brochure Images; Price: Fifty cents, includes printed address label|

|**Element:**|Original Format|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Physical medium of defined resource|
|**Obligation**|Optional|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Select from the list based on the format types available|
|**Controlled Vocabulary**|PBCore instantiationPhysical Vocabularies|
|**Example(s)**|Betacam; audiocassette|

|**Element:**|Place|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Spatial characteristics of described resource, such as country, city, county, or other geographical term|
|**Obligation**|Optional|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Cities and counties must have accompanying states, formatted by state abbreviation|
|**Controlled Vocabulary**|GeoNames|
|**Example(s)**|New York, NY; London|

|**Element:**|Stereo/Mono|
|-----------------------|---------------------------------------------------------------------------|
|**Description**|Representation of original version of audio|
|**Obligation**|Optional|
|**Repeatable?**|No|
|**Range**|Controlled text string|
|**Input Guidelines**|Select from the list based on technical characteristics of physical item|
|**Example(s)**|Mono|

⬅️ **Return to [Overview](/README.md)**