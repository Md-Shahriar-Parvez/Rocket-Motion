# A First-Principles Force-Based Derivation of Rocket Motion in a Uniform Gravitational Field

**Independent Analytical Note**

## Overview

This repository contains an independent rederivation of the classical rocket equation for vertical motion in a uniform gravitational field.

The derivation approaches rocket motion from a **force-based perspective**, rather than starting directly from the conventional system-wide momentum conservation formulation. The dynamics of the ejected fuel element and the remaining rocket body are analyzed separately using **Newton’s second and third laws**.

Particular attention is given to the treatment of the changing rocket mass, the direction of velocities and forces, and the sign convention associated with the differential mass change, where dm < 0 for an expelling rocket.

## Approach

The derivation proceeds through the following steps:

1. Define a fixed inertial reference frame and establish the upward direction as +î.
2. Define the rocket velocity, exhaust velocity, and gravitational acceleration using explicit vector directions.
3. Establish the relative velocity between the ejected fuel and the rocket.
4. Analyze the dynamics of an infinitesimal expelled fuel element of mass −dm.
5. Analyze the dynamics of the remaining rocket body, whose mass becomes m + dm.
6. Apply Newton’s third law to the interaction between the rocket and the expelled fuel.
7. Obtain the differential equation governing rocket motion.
8. Integrate the resulting equation under the assumption of constant exhaust speed and uniform gravitational acceleration.

## Governing Equation

The force-based analysis leads to the differential equation

**m(dv/dt) = vᵣ(−dm/dt) − mg**

where:

* **m** = instantaneous mass of the rocket system
* **v** = upward velocity of the rocket
* **vᵣ** = exhaust speed relative to the rocket
* **g** = magnitude of the gravitational acceleration
* **dm/dt** < 0 = rate of change of rocket mass

For constant exhaust speed vᵣ and uniform gravitational acceleration g, integration gives

**v = vᵣ ln(mᵢ/m𝒇) − gt**

where mᵢ and m𝒇 are the initial and final rocket masses, respectively.

## Focus of the Study

The purpose of this work is not to introduce a new form of the rocket equation. Instead, it explores how the familiar result can be reconstructed from the underlying force interactions between the rocket and its expelled fuel.

The derivation emphasizes:

* First-principles physical reasoning
* Direct application of Newton’s second law
* Newton’s third-law force pairs
* Explicit vector directions
* Consistent treatment of dm < 0
* The relationship between exhaust velocity and rocket velocity
* The role of gravity in vertical rocket motion

## Repository Contents

* **Technical report** — Full derivation in PDF format

## Scope and Assumptions

The derivation considers an idealized rocket under the following assumptions:

* Motion is purely vertical.
* The reference frame is inertial.
* The gravitational field is uniform.
* The exhaust speed relative to the rocket is constant.
* The rocket continuously ejects fuel.
* The effects of atmospheric drag and other external forces are neglected.

Under these assumptions, the derivation reduces to the classical rocket equation with the gravitational term.

## Author

**Md. Shahriar Parvez**
Department of Mechanical Engineering
Bangladesh University of Engineering and Technology (BUET)
Dhaka, Bangladesh

---

*This work is an independent study and rederivation intended to explore the mathematical and physical foundations underlying a standard result in rocket dynamics.*
