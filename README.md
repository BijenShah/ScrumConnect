# ScrumConnect

Solution:
1. The api.txt file stores the api key from newsapi.
2. The newsapi.py file extracts the data from Newsapi and stores the data into a CSV format file.
3. This file is then stored into Azure Storage Container.
4. A pipeline is built under Azure Data Factory to pull the CSV file clean the data and save it into a different CSV file.

Limitations: There were some limitations to my Azure account.
              To run the python code as a Batch inside ADF pipeline, hence the code was run for pilot testing on Google Colab.
              
Doubts/Improvements: The purpose of the data could be understood to better clean and transform the data.
                     Azure Data Flow or some other ETL tool as per the purpose could be utilised for transformation.
