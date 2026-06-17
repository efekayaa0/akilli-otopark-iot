# Efe Parking Systems - IoT Smart Parking Prototype

This project is a smart parking management system prototype and simulation, developed by Mustafa Efe KAYA for the "Internet of Things (IoT)" course at Istanbul Health and Technology University.

The system is designed to reduce the time wasted finding parking spots, lower fuel consumption, and decrease driver stress. It automatically calculates the shortest route ("Nearest-First" algorithm) to the nearest available parking space from the entrance gate.

## Key Features

* Real-Time Occupancy Monitoring: Instant tracking of available and occupied parking spots.
* Nearest-First Assignment: Algorithmically determines the closest parking spot based on North or South entrance gates.
* Dynamic Route Planning: L-shaped routing that restricts vehicle movement to corridors, calculating distance in meters/km.
* Interactive Simulation: A web-based visual simulation interface developed with Python and HTML/JS, running on Google Colab.

## Technologies Used

Simulation Layer:
* Python (Jupyter/Google Colab): Backend logic, algorithm design, and event schema management.
* HTML/CSS/JavaScript: Web-based visualization of the simulation.

Proposed Field Architecture (Future Work):
* Hardware: ESP32 Microcontroller, HX711 Load-Cell (Weight Sensor).
* Communication: LoRaWAN / NB-IoT for low-power, long-range data transmission.
* Backend: Edge-cache (Redis), MQTT/HTTP protocols, REST/WebSocket architecture.

## Setup and Execution

To run the simulation, follow these steps:

1. Clone this repository:
   git clone https://github.com/efekayaa0/efe-parking-systems.git
2. Upload the akilli_otopark_colab (1).ipynb file to Google Colab.
3. Run all cells in the notebook.
4. The code will generate an index.html file in the backend.
5. Click the local tunnel link provided in the output cell to access the simulation interface.

## Project Documentation

For more information on the project's background, literature review, and detailed architecture, please refer to the included documents:
* Efe_Otopark_Sistemleri_Rapor_v3.docx: Comprehensive project report, formulations, and evaluation.
* IoT_project.pptx: Project presentation file.

## Developer

* Mustafa Efe KAYA - Istanbul Health and Technology University, Software Engineering
