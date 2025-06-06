# Questions & criteria for data preservation partners 

These questions are designed to help data preservation partners evaluate requests and offers from data holders and hosts and determine if they are a good fit for a project. We informally call this “the matchmaking document” and the questions are meant to be value neutral. Think through these questions and bring your answers to your conversations with potential partners to assess and match needs and capacities. Groups should expand and remix this question list based on their expertise and capacity, as well as the specifics of the data. This material is CC0 licensed.

### For data sources:

1.  Describe the risk to the data

    1.  E.g. data will no longer be collected, data deletion, loss of access (web portals, APIs), end of data products & services

    2.  How much time do you have to assess options

    3.  The [repository crisis scorecard](https://zenodo.org/records/15208172) is an additional resource for assessment questions

2.  Is this the only source of the data?

3.  What is the total volume of metadata and data? (in GB, TB etc)

4.  Is the data all in one place and accessible? If so, what’s the URL?

5.  What data types are held, ex. observations, model analysis, others. 

6.  What are the data formats? E.g. netCDF, csv

7.  How much internet bandwidth is available at the current host for upload and download?

8.  How many and which metadata schemas can be outputted?

9.  Is it possible to download an archive copy of all datasets with all metadata attached?

10. Are there foundational datasets that need to be saved, while other data products can be regenerated? 

    1.  Do we need to preserve the code to regenerate those other data and data products? 

11. Is this dataset static or dynamic? If dynamic (data collection is ongoing), can that be reconnected to a new location?

12. What sensitivities are there around the data? (e.g., licensing limitations, restricted data, Indigenous data)

    1.  Note that if this data contains personally identifying information (aka PII) or personal data ([as defined under the EU’s General Data Protection Regulation](https://gdpr-info.eu/issues/personal-data/)) such as names + associated contact information it may have special requirements for how it can be shared or hosted. **This worksheet is not legal advice** - check with legal counsel before working with sensitive data.

13. Who is using this data (communities, companies, state/local governments) and what are they using it for? Please be as specific as you can. Understanding user needs helps plan for future demand and design (e.g. an API that handles hundreds of low volume calls per minute needs a different solution than a large text file published weekly).

    1.  What are the potential impacts of losing access to this data? 

14. Is this data used for emergency warning systems or disaster response?


### For potential hosts:

1.  What’s the total amount of static data you can host? For how long? By ‘static’ we refer to snapshots or complete datasets that will not be changed or added to once posted

2.  What data types can you support (e.g. tabular, video)? Do you require specific data schemas, standards, or other elements to host the data?

    1.  Do you require specific data structures (metadata, tags, other) for the data to be discoverable in search from your platform?

3.  Do you have content restrictions or preferences?

4.  Can you host dynamic datasets? By ‘dynamic’ we mean datasets that will be regularly updated and/or connected to ongoing data collection efforts

5.  What volume of requests / connections can you support?

6.  Can you support access restrictions for sensitive data and/or data sovereignty?

7.  Do you have staff time and capacity/skill to support moving the data? For ongoing maintenance?

8.  How much will it cost to store the data and what services are provided at that cost (e.g. storage only, access up to a certain volume)?


### For matchmakers/data preservation stewards and facilitators:

1.  Who are the chief contacts and what is their

    1.  Capacity

    2.  Access

    3.  Level of professional and personal exposure/risk

2.  Do you or the partner know if the dataset has been archived/backed up anywhere else?

3.  Do you know how to do this and have the capacity to do it? Can you bring in other partners as needed?

4.  Is a new host already connected to user communities for this data (e.g. not a generic AWS bucket but moving observation data to a place people already go to look for observation data)?

5.  Is this a temporary solution that will need a longer-term fix later, and, if so, do you have a plan for that?

6.  Is this data that you would like to see rehosted in the US in the future? If so, how will you document and plan for that?

7.  Are there other risks in moving this data to this host?


