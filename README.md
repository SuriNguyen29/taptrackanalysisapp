## TapTrack: Personal Go Card Travel Dashboard
TapTrack is an interactive Shiny dashboard built with flexdashboard and ggplot2 that allows Translink Go Card users to upload their travel history and gain personalized insights into their travel patterns, top-up behavior, and fare spending.

## What It Does
This app parses and visualizes Go Card transaction data from .csv exports. Users can:

Track daily card balances and top-up amounts

Analyze fare types (Fixed Fare, Off-Peak, Transfer, etc.)

Identify frequently visited stations

Evaluate the impact of recent fare policies (like the August 2024 50-cent fare initiative)

## Techniques & Tools
Shiny & Flexdashboard: Interactive UI and layout

Data Cleaning: Regex and date parsing to standardize stop names and handle fare formats

Geospatial Mapping: Integrates GTFS stop location data for visual travel paths

Comparative Analysis: Policy impact analysis (before vs. after fare changes)

Custom Theming: Aesthetic, brand-colored visuals using a custom ggplot2 theme

## Technologies Used
R (Shiny, ggplot2, dplyr, DT)

flexdashboard for layout

shinyRatings, viridis, bslib for enhanced interactivity and styling
