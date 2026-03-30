# RideSharing App Simulation

A Python-based object-oriented simulation of a simple ridesharing system. The program models real-world ride-matching behavior by representing passengers, cars, and locations, and finding optimal matches based on distance and cost.

---

## 🚗 Features

* Create and manage car and passenger objects
* Track real-time locations using coordinate-based systems
* Calculate distance between passengers and cars
* Find the nearest available car for a passenger
* Identify the cheapest car based on cost per mile
* Simulate movement of cars and passengers
* Add new cars dynamically during runtime

---

## 🧠 Core Classes

### 📍 `Location`

Represents x and y coordinates in a 2D space.

### 🚘 `Car`

Stores:

* Car name
* Current location
* Cost per mile
  Includes functionality to move the car to a new location.

### 👤 `Passenger`

Stores:

* Passenger name
* Current location
  Includes functionality to update passenger position.

### 🧭 `RideSharingApp`

Main system class that:

* Stores all cars and passengers
* Adds/removes users and vehicles
* Finds optimal matches based on:

  * Distance (nearest car)
  * Cost (cheapest car)

---

## ⚙️ Algorithms Used

* Euclidean distance calculation:

  * Used to determine nearest car to a passenger
* Linear search:

  * Used to scan through available cars
* Basic optimization logic:

  * Min cost and min distance selection

---

## 🧪 Simulation Scenarios

The program demonstrates:

* Initial object creation (cars + passengers)
* Matching passengers to nearest/cheapest cars
* Updating locations dynamically
* Adding new cars and recalculating matches

---

## 🛠️ Concepts Practiced

* Object-Oriented Programming (OOP)
* Class relationships and composition
* Real-world system modeling
* Distance-based algorithms
* Data management using lists
* State updates and simulation design

---

## 🎯 Purpose

This project was built to simulate a simplified ridesharing platform and strengthen understanding of object-oriented design, spatial reasoning, and algorithmic decision-making.
