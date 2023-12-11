
# 🏎️ Formula 1 Data Engineering Project  🚀
![Project Image](https://github.com/SanketKuwar/Formula1-Project/blob/main/Formula1%20Project.png)

## Overview

Welcome to the Formula 1 Data Wonderland! 🌟 This project builds an extraordinary data engineering pipeline for Formula 1 racing data on Databricks with Azure.

---


##  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🚦🚦--  SETUP --🚦🚦&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


## 🚀 Mounting ADLS Containers

Explore the Depths of Azure Data Lake Storage.

🔗 [Mounting ADLS Containers Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Files_Setup/Mount_adls_containers_for_project.py)

## 🧪 Testing Access with Service Principal

Ascend the Realm of Credentials: Ensuring Rule over the Racing Kingdom.

🔗  [Testing Access Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Files_Setup/Test_Access_adls_using_service_principal.py)


## 🚦  Testing Mond ADLS with Service Principal
Navigate the Track like a Well-Tuned F1 Car: Testing Mond ADLS.

🔗  [Testing Mond ADLS Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Files_Setup/Test_mount_adls_using_service_principal.py)

---


##  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🏎️ 🏎️ --  INGESTING FILES -- 🏎️ 🏎️&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


📂 Time to unleash the racing data into our system!



### 1. Circuit File

🛣️ Buckle up! Let's ingest the Circuit file into a DataFrame and kickstart our adventure.

🔗 [Link to Circuit File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/1.ingest_circuits_file.py)



### 2. Race Details File

🏁 Ready, set, go! Ingest the Race Details file and prepare for an adrenaline-packed journey.

🔗 [Link to Race Details File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/2.ingest_races_file.py)

### 3. Constructors File

🏗️ Constructing success! Ingest the Constructors file and build a winning data structure.

🔗 [Link to Constructors File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/3.ingest_constructors_file.py)

### 4. Driver File

🏎️ On the fast track! Ingest the Driver file and accelerate into the world of racing data.

🔗 [Link to Driver File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/4.ingest_drivers_file.py)
### 5. Result File

🏆 Cross the finish line! Ingest the Result file and unveil the outcomes of thrilling races.

🔗 [Link to Result File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/5.ingest_results_file.py)

### 6. Pit Stop File

⛽ Pit stop perfection! Ingest the Pit Stop file and optimize your data strategy.

🔗 [Link to Pit Stop File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/6.ingest_pit_stops_file.py)

### 7. Lap Time File

⏱️ Lap after lap! Ingest the Lap Time file and analyze the speed of each thrilling moment.

🔗 [Link to Lap Time File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/7.ingest_lap_times_file.py)

### 8. Qualifying File

🏁 Qualify for insights! Ingest the Qualifying file and get ready for data-driven victories.

🔗 [Link to Qualifying File Ingestion Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Ingestion/8.ingest_qualifying_file.py)

---

##  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🏭 🏭 -- TRANSFORMATION -- 🏭 🏭&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;



🎨 Let's transform and shape the racing data into meaningful insights!

### 1. Race Results

🏁 Race day drama! Transform the Race Results file to reveal the winners and the underdogs.

🔗 [Link to Race Results Transformation Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Transformation/1.race_results.py)

### 2. Driver Standings

🚗 On the leaderboard! Transform the Driver Standings file and track the rise of F1 stars.

🔗 [Link to Driver Standings Transformation Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Transformation/2.driver_standings.py)

### 3. Constructor Standings

🏭 Team supremacy! Transform the Constructor Standings file and unveil the team dynamics.

🔗 [Link to Constructor Standings Transformation Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Transformation/3.constructor_standings.py)

### 4. Final Race Results

🏆 Grand finale! Transform the Final Race Results file to capture the essence of the racing season.

🔗 [Link to Final Race Results Transformation Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Transformation/4.calculated_race_results.sql)


##  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🎨🎨 -- FINAL ANALYSIS -- 🎨🎨&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

🔍 Let's analyze and uncover the key insights from the racing results!

### 1. Dominant Driver

🏎️ Zooming in on excellence! Analyze the data to identify the dominant driver in the racing season.

🔗 [Link to Dominant Driver Analysis Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Results_Analysis/1.find_dominant_drivers.sql)
### 2. Dominant Team

🏭 Team dominance revealed! Analyze the data to unveil the most dominant team on the racing track.

🔗 [Link to Dominant Team Analysis Code](https://github.com/SanketKuwar/Formula1-Project/blob/main/Results_Analysis/2.find_dominant_teams.sql)

![Project Image](https://github.com/SanketKuwar/Formula1-Project/blob/main/Dominant_Driver_Analysis.png)


