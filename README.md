# Comprenhensive ETL workflow with Python <br>

The task aims to extract data from CSV, JSON, and XML formats, transform it,
and load the transformed data into a structured format for further processing.<br><br>

<strong>Tools used : Python <br>

<h3>Basic Workflow : </h3>

<strong>Step 1: Download the files <br>
> download the files from the given link <br> 
  
<strong>Step2 : Import the necessary libraries <br>
> pandas to read CSV and JSON files.<br>
> xml.etree.ElementTree to parse XML data.<br>
> logging to create logfile. <br>
  
<strong>Step3 : Set up paths for<br>
>  logfile.log to record the logs.
>  transformed_data.csv to save the final output.

<strong>Step4 : Extraction <br>
> Extract the CSV, JSON, XML files into pandas dataframes <br>

<strong>Step5 : Transformation <br>
> After txtraction, combine all the dataframes <br>
> Some necessary transformations are applied on the dataframe such as changing the column datatypes, heights from inches to meters, weights from pounds to 
  kilograms<br>
> deleting of extra columns <br>
  
<strong>Step6 : Loading  <br>
> After all the transforms done the data is loaded into a csv file <br>

<strong>Step7 : Execute the etl pipiline <br>
> A log file is created to log the process starting from extraction to loading <br>
