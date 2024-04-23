## Overview

Our project presents an innovative Healthcare Recommendation and Management System, designed to enhance the healthcare experience for both patients and medical professionals. By integrating advanced technologies like AI-driven data analysis, vector databases, and automated data processing workflows, this system aims to simplify the complexity of healthcare decision-making.

## Problem Statement:

The healthcare sector often grapples with the challenge of effectively managing vast amounts of medical data and providing personalized care. Patients struggle to navigate through this information overload for informed healthcare decisions, while healthcare professionals seek efficiency in diagnosis and treatment processes. Our system addresses these challenges by offering a seamless, integrated solution that utilizes the power of AI and data management technologies.

## Project Description

Our system comprises five interconnected modules:

-     	Data Processing with Apache Airflow:
  - Manages and orchestrates data workflows.
  - Processes diverse medical data sources for real-time insights.
-     	Pinecone and OpenAI for Personalized Recommendations:
  - Leverages Pinecone's vector database for efficient data retrieval and OpenAI's capabilities for intelligent data processing.
  - Provides personalized medicine lists, doctor suggestions, and hospital recommendations.
-     	Streamlit-Based Doctor's Portal:
  - A user-friendly interface for medical professionals to access patient information, input symptoms, and receive AI-driven diagnostic and treatment suggestions.
-     	FastAPI for Backend Services:
  - Handles requests from the Streamlit frontend, interacting with Pinecone and OpenAI.
  - Integrates with a PostgreSQL database for robust data management.
-     	Snowflake for Data Analysis and Storage:
  - Extracts the data from Amazon S3.
  - Performed Data cleaning, formatting and modelling. Interacts with FastAPI.

## Technology stack

- Apache Airflow: Workflow management and data processing.
- Pinecone/Weaviate Vector Databases: Efficient handling and retrieval of vectorized data.
- OpenAI: AI models for generating intelligent recommendations and embeddings.
- Streamlit: Interactive web application for doctors and patients.
- FastAPI: Backend service management.
- PostgreSQL Database: Secure and robust data storage.
- Google Cloud Platform (GCP): Hosting and cloud infrastructure.
- Pandas: Data manipulation and analysis.
- Jupyter Notebook: Data exploration and initial analysis.
