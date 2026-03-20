# Software Configuration


(To be completed.)

The software configuration section consists of the configuration for two parts: simulation environment and software stack on the vehicles. Below provides the configuration for these two software. 

## Simulation Environment: 

The off-road roboracers can be simulated and tested in a simulator. At this moment, nVIDIA ISAAC Sim is used to simluate the off-road environment. The hardware to deploy the simluation environment can be found [here](../hardware-configuration/).
  
### Install nVIDIA ISAAC Sim for Off-road roboracier

### 3D Model for Philly Pumptrack Environment:
Philly pumptrack is a sample off-road shown below to demonstrate the capability of off-road robo-racier. 

![PhillyPumpTrack](https://private-user-images.githubusercontent.com/47904673/562330328-e82d4f94-69d8-4047-81e6-f180c6f57236.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzQwMDE3ODAsIm5iZiI6MTc3NDAwMTQ4MCwicGF0aCI6Ii80NzkwNDY3My81NjIzMzAzMjgtZTgyZDRmOTQtNjlkOC00MDQ3LTgxZTYtZjE4MGM2ZjU3MjM2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjAzMjAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwMzIwVDEwMTEyMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQ4NzkzODA3ZjE5NWZkZjAwMDI5MjJkZjkxZGVkNWNjMDhkYzhhNTBmOWI2YWE3MzVjNzhmNzk5ODBmZjI3M2YmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.xOuDmuYr4_RQ_RHETcq3e2J0HIY4MldoAakf2jzTP4Y)


## Software Stack on Off-road roboracier:

No road infrastructures are available in off-road environment. Machine-learning-based vision models are developed and deployed to identify the drivable area, route, and control the vehicle. This section provide the reference design of the software stack for off-road roboraicer. 

### Software Architecture: 

### Drivable Area Detection:
