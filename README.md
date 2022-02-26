# Week-7-Industrial-IoT-using-Google-Cloud-Quiz
Week 7

Quiz 1: Dataprep Lab

1. Which of the following are characteristics of Dataprep? (Choose TWO)

Ans: In Dataprep, a dataset is a pointer to your data. 
     In Dataprep you can import data from Cloud Storage, BigQuery, or your local computer. 


2. A colleague is designing an IoT network. They want to send data to Dataprep, modify the data and store the changed data on Dataprep for fast access during analysis. 
They've asked for your advice and you have confirmed that this will work. Is your advice TRUE or FALSE? 

Ans: False


3. You are designing an IoT network to monitor robotic arms . The temperature in the environment you are monitoring remains fairly constant for long periods of time (usually for several weeks). Occasionally the temperature spikes very high. 
You need to keep track of these spikes: how high, how long and how many, for each piece of equipment in the environment. 
Which of these designs would best suit your network? (Choose TWO)

Ans: Store the data in a Standard Cloud Storage bucket. Then connect it to Dataprep and create a recipe to filter the data, looking for temperatures that fall outside the typical range. 
     Use a Dataprep recipe to filter the data, looking for temperatures that fall outside the typical range. Then send the data to BigQuery for further analysis. 



Quiz 2: Data Studio

1. You are designing an IoT network. The network will monitor a colony of penguins in New Zealand. There are penguin researchers all over the world interested in this data. 
Which of these designs is well suited to your needs?

Ans: Use Dataprep to clean the data, BigQuery to analyze it, and Data Studio to create a dashboard. Share the link on social media and set access to view for reports and data. 


2. You have an IoT network monitoring solar farm in a remote location. The telemetry data from the solar farm is: amount of sunlight and electricity produced. You also have a data set that contains information for each panel: panel_id, age, location of the panel, make and model of the panel.
You've been asked to create a dashboard for the maintenance team. What information should be on it?

Ans: Alerts for low performance panels
     A map of the land with an interactive marker for each panel. 
     Average output of the panels


3. You are designing a dashboard for a flower delivery company in a large city. The dashboard will be used by the truck dispatchers, customer service representatives, and the truck driver manager. 
What information should be on it?

Ans: An interactive map showing the location of each truck, in real time. 
     Estimated time of delivery for each delivery. Possibly in the form of a list of deliveries.

