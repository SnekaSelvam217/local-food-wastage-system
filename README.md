Project Overview

Food wastage is a major social issue, with surplus food often discarded while many people face food insecurity.
This project implements a Local Food Wastage Management System that connects food providers (restaurants, grocery stores, individuals) with receivers (NGOs, community centers, or individuals) to redistribute surplus food efficiently.

The system leverages Python, SQL, and Streamlit to:

Store and manage food listings in a structured SQL database.

Enable CRUD operations for food donations and claims.

Provide insights into food wastage trends through queries and visualizations.

Project Features

Food Providers & Receivers:

View and filter providers and receivers by city, type, and contact.

Identify top providers and receivers based on donations and claims.

Food Listings & Claims:

Track available food items and their quantity.

Claim surplus food and update status (Pending, Completed, Canceled).

CRUD operations to add, update, or delete food listings and claims.

Data Analysis & Insights:

Top food providers by quantity donated.

Most claimed food items and meal types.

Food availability trends across cities.

SQL-powered queries for reporting and decision-making.

Datasets

The project uses the following datasets stored in data/ folder:

providers_data.csv – Details of food providers.

receivers_data.csv – Details of food receivers.

food_listings_data.csv – Surplus food items available for claim.

claims_data.csv – Records of claimed food items.
