# Orbital Path Calculation Techniques

**Author**: Recai Efe Dik

---

## Table of Contents

- [Hohmann Transfer Orbits](#hohmann-transfer-orbits)
- [The Lambert Problem](#the-lambert-problem)
- [Solving Lambert's Problem with DNN](#solving-lamberts-problem-with-dnn)

---

## Hohmann Transfer Orbits

A **Hohmann transfer orbit** is half of an elliptical orbit. In the initial orbit, a prograde delta-v is applied using thrusters, which increases the orbital velocity. As a result, the spacecraft transitions to a higher orbit. This maneuver is the most fuel-efficient method for transferring between two circular orbits.

> For more information, visit: [Wikipedia - Hohmann Transfer Orbit](https://en.wikipedia.org/wiki/Hohmann_transfer_orbit)

You can explore the interactive notebook here:  
[Google Colab - Hohmann Transfer](https://colab.research.google.com/drive/1RGz7O1OoClLNUd1xMx0HY8mQuatTJBKC?usp=sharing)

---

## The Lambert Problem

### General Definition

The **Lambert Problem** determines the optimal trajectory between two points in space within a fixed time, regardless of the geometry of the orbit. The solution yields the transfer orbit connecting the two positions.

### Problem Solution Steps

- **Universal Variables Method**
- **Lancaster and Blanchard's Algorithm**
- **Gooding's Method**

---

### Universal Variables Method

This method solves the Lambert problem by connecting two position vectors with an orbit over a given time interval. It is beneficial because it uniformly handles elliptical, parabolic, and hyperbolic orbits.

**Key Steps**:
1. Define the required variables.
2. Use iterative techniques (e.g., Newton-Raphson) to find the universal variable.
3. Calculate orbital elements using these universal variables to determine the velocity vectors at the initial and final positions.

Interactive notebook:  
[Google Colab - Lambert Problem](https://colab.research.google.com/drive/1RGz7O1OoClLNUd1xMx0HY8mQuatTJBKC?usp=sharing)

---

## Solving Lambert's Problem with DNN

This section explores an approach to re-solving the Lambert Problem using Deep Neural Networks (DNNs). The goal is to approximate or improve upon classical numerical methods through machine learning models.

Notebook:  
[Google Colab - Lambert with DNN](https://colab.research.google.com/drive/1RGz7O1OoClLNUd1xMx0HY8mQuatTJBKC?usp=sharing)

---
