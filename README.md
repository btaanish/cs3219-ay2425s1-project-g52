[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/bzPrOe11)
# CS3219 Project (PeerPrep) - AY2425S1
## Group: G52

### Note: 
- You can choose to develop individual microservices within separate folders within this repository **OR** use individual repositories (all public) for each microservice. 
- In the latter scenario, you should enable sub-modules on this GitHub classroom repository to manage the development/deployment **AND** add your mentor to the individual repositories as a collaborator. 
- The teaching team should be given access to the repositories as we may require viewing the history of the repository in case of any disputes or disagreements. 

# Local Setup Guide

This guide describes how to set up the Peerprep's frontend and backend locally.

## Clone the Repository

In a command line, navigate to the destination folder and clone the repository from GitHub to your local machine:

```bash
git clone https://github.com/CS3219-AY2425S1/cs3219-ay2425s1-project-g52.git
```

then change directory into

```bash
cd cs3219-ay2425s1-project-g52
```

## Installing dependencies
(FOR MILESTONE 2)
Navigate to the frontend directory and install the dependencies

```bash
cd frontend
npm install
```

Similarly, navigate to the backend question-service directory and install the dependencies
```bash
cd ..
cd backend
cd question-service
npm install
```

Once these are done, last step is to get both the frontend and backend `.env` files from a developer and drop it into the `frontend` and `backend\question-service` directory respectively.


## Running the application

The app is now ready to run. For proper functionalty, both the client and server must be running.

### Frontend
(FOR MILESTONE 2)
In terminal, navigate to the frontend directory 
```bash
cd frontend
```
Then run
```bash
npm start
```

This launches the app in development mode and you should see `Compiled successfully!` displayed.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Backend

In another terminal instance, navigate to the backend question-service directory 
```bash
cd backend
cd question-service
```
Then run
```bash
npm start
```

This launches the server locally and you should see 
`Listening on localhost:8000` `Database connected..`

The server is hosted on [http://localhost:8000](http://localhost:8000) and you can see the documentation in [http://localhost:8000/docs](http://localhost:8000/docs) (documentation is WIP)

## Conclusion

You are now set up locally and can explore the app. You can check out our [developer guide](DeveloperGuide.md) to learn more. 

Further enhancement to be made in future updates.