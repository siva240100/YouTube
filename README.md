# YouTube Data Harvesting and Warehousing
Project Overview:

YouTube Data Access and Analysis Application enables users to gather, clean, and examine data from several YouTube channels. This project uses SQL, MongoDB, and Streamlit to create an intuitive interface, allowing the retrieval, storage, and querying of YouTube data.

Tools and Libraries Used:

Streamlit: Provides a user-friendly interface for data retrieval and analysis.

Python: The backbone of the application, used for all aspects of data manipulation and presentation.

Google API Client: Facilitates interaction with YouTube's Data API v3 to fetch channel and video details.

MongoDB: Manages structured and unstructured data efficiently.

PostgreSQL: An advanced DBMS for robust and reliable data management.

Ethical Considerations: Responsible data handling is crucial. Respecting YouTube's terms of service and data privacy regulations is a key part of this project. The goal is to ensure that data is collected and used ethically, maintaining the privacy and rights of content creators and users alike.

Required Libraries:

googleapiclient.discovery

streamlit

psycopg2

pymongo

pandas

Features:

Data Retrieval: Fetch channel and video data via the YouTube API.

Data Storage: Utilize MongoDB as a data lake for initial storage.

Data Cleaning: Process and clean the collected data for accuracy and consistency.

Data Migration: Transfer data from MongoDB to a SQL database for more efficient querying.

Data Querying: Perform advanced searches on the SQL database to retrieve relevant information.


