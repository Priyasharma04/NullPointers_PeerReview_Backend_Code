# Peer Review Project – Null Pointers

## Overview
This repository contains the **backend implementation** of a peer review project developed by the group **Null Pointers**.

The project follows a modular architecture where the **backend**, **frontend**, and **machine learning model** are maintained on separate platforms. This repository serves as the **primary submission**, as required.


## Group Details
- **Project Name:** PeerReviewAI 
- **Group Name:** Null Pointers 


## Project Structure
The project is divided into three main components:

### Backend (This Repository)
- Contains the complete backend source code
- Handles API requests and business logic
- Acts as the central connector between frontend and model
- Designed to support ML-based processing

 *This repository is submitted for evaluation.*


### Frontend
- Developed and maintained in a **separate GitHub account**
- The website is **live and functional**
- Communicates with backend through APIs

 Frontend GitHub Repository: *[https://github.com/aasthac26/NullPointers_PeerReviewAI_code]*  
 Live Website URL: *[https://frontend-one-iota-23.vercel.app/]*  


### Machine Learning Model
- Model is developed and trained on **Kaggle**
- Training notebook is hosted there


Model processing is currently **disabled**, but backend integration points are already implemented for future activation.
## Ngrok Integration Instructions
To connect the machine learning model with the backend:

1. Open the **model code on Kaggle**
2. Add your **Ngrok authentication token** in the specified section
3. Run the model code
4. Ngrok will generate a **public URL**
5. Copy this URL
6. Paste the URL into the backend file:
 Kaggle Model / Notebook Link: *[https://www.kaggle.com/code/priyasharma040404/nullpointers-peerreviewai-model-code]*  


## Workflow
1. User interacts with the live frontend
2. Frontend sends requests to backend APIs
3. Backend processes the request
4. Backend connects to ML model for inference
5. Response is returned to the frontend

> ML inference is currently turned off, but the system architecture supports it.


## Reason for Multiple Repositories
The project components are hosted separately due to:
- Clear separation of frontend, backend, and ML logic
- Kaggle being suitable for model training and experimentation
- Independent deployment and maintenance of frontend


## Submission Note
This repository is submitted as part of the software engineering project.  
All external project components are clearly documented for transparency.
