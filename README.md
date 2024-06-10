# Temperature Data Processing Pipeline

## Introduction

Thank you for the opportunity to present this project. This initiative aims to display my technical expertise in developing an efficient and scalable pipeline for rapid data transfer and processing. The primary objective of this project is to upload temperature data from both the inside and outside of a main room, ensuring accurate storage and analysis. While this goal can be achieved through a series of specific steps, my approach involves building an integrated platform that simulates these steps in real life.

## Overview of the Project

The proposed platform consists of three main applications: **PipelineApp (Node 1)**, **IngestorApp (Node 3)**, and **CorrectorApp (Node 2)**. Each application has a specific role, from reading and validating data to storing it in designated locations and correcting invalid entries. This framework leverages well-known software development techniques such as parallel threading, queuing, traditional socket programming, and various data structures to optimize data processing and handling.

Furthermore, this framework is designed to be extensible, allowing for the addition of more data sources, enhanced data processing capabilities, scalability improvements, machine learning integration, and robust security measures. This vision forms the core of a broader system that can be expanded and generalized to build necessary tools for management and monitoring.

The following sections provide a detailed overview of the project's concept, implementation details, and potential expansion strategies.

## Objectives and Goals

- **Develop a robust data engineering pipeline.**
  1. Calibrate the data pipeline using a given dataset.
  2. Write code without prior knowledge of what anomalous data may be fed through this pipeline, simulating real-world conditions.
  3. Write a script that:
     - Processes this data and writes it into a database.
     - Prints out a summary of potential data issues.
  4. Test the pipeline with anomalous data in the same format as the original dataset, ensuring the script flags any issues.

1. **Clone the repository**:
      git clone https://github.com/mkhoder2013/TenderedFramework.git
2. **run**:
   docker-compose up
3. run pgAdmin on port 8181:
   user: admin@admin.com
   password: admin

## Accessing pgAdmin

1. Open your web browser and navigate to `http://localhost:8181`.
2. Log in using the following credentials:
    - **Email**: `admin@admin.com`
    - **Password**: `admin`

## Creating a Connection to PostgreSQL Server

1. After logging into pgAdmin, create a new server connection:
   - Right-click on `Servers` in the left-hand tree and select `Create` > `Server`.

2. In the `Create - Server` window, enter the following details:

    ### General Tab
    - **Name**: `postgresServer`

    ### Connection Tab
    - **Host name/address**: `postgres`
    - **Port**: `5432`
    - **Maintenance database**: `postgres`
    - **Username**: `postgres`
    - **Password**: `Temp@123`


     
