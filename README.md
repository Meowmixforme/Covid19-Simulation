# Covid-19 Simulation

An agent-based simulation of Covid-19 transmission and vaccination, developed for a second-year Artificial Intelligence module at Teesside University.

## Overview

This project models the spread of Covid-19 within a population using NetLogo. It allows users to explore how factors such as infection, recovery, death, and vaccination impact the course of an epidemic. The simulation is designed for educational purposes, providing a visual and interactive means to understand infectious disease dynamics and the effects of interventions.

## Contents

- `v8255920_Fothergill_James_Covid-19_Simulation.nlogo`  
  The main NetLogo model file containing all code, parameters, interface elements, and documentation.
- `README.md`  
  This file.

## Features

- Agent-based modelling of individuals (agents/turtles) who can be:
  - Susceptible (blue)
  - Infected (red)
  - Immune (yellow)
  - Vaccinated (green)
  - Dead (black)
- Probabilistic infection, recovery, and death based on user-adjustable parameters
- Vaccination deployment with adjustable coverage
- Optional contact tracing visualisation
- Real-time statistics and plots: number of infected, immune, dead, and alive
- User-friendly controls: start, stop, and parameter sliders

## How to Use

1. **Install NetLogo**  
   Download and install NetLogo from [https://ccl.northwestern.edu/netlogo/](https://ccl.northwestern.edu/netlogo/).

2. **Open the Model**  
   Launch NetLogo and open `v8255920_Fothergill_James_Covid-19_Simulation.nlogo`.

3. **Run the Simulation**  
   - Click **Setup** to initialise the population.
   - Adjust parameters such as recovery probability, death probability, number of people, vaccination deployment, and toggle contact tracing as desired.
   - Click **Start/Stop** to begin or pause the simulation.
   - Observe the coloured agents and live statistics.

## Parameters

- **Recovery Probability**: Chance of recovery after 14 days (default simulates healthy adults in developed countries).
- **Death Probability**: Chance of dying after 10 days (default reflects reported rates; can be adjusted).
- **Number of People**: Total number of agents in the simulation.
- **Vaccination Deployment**: Percentage chance for healthy, uninfected, non-immune agents to be vaccinated each tick.
- **Contact Tracing**: Shows who infected whom with tracing lines.

## Visual Key

- **Red**: Infected with Covid-19
- **Blue**: Susceptible (not infected, not immune)
- **Green**: Vaccinated (become immune over time)
- **Yellow**: Immune (recovered or vaccinated)
- **Black**: Dead

## Notes and Extensions

- The model can be extended to include age-based survival rates, lockdown measures, and multiple vaccine types.
- While simplified for educational use, the simulation demonstrates core concepts of epidemic modelling and intervention strategies.




Click the image to view the video demonstration


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/QhhFxVyi_8g/0.jpg)](https://youtu.be/QhhFxVyi_8g)
