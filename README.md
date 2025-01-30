# Vehicle_Sales_Dashboard

## Introduction

The Vehicle Sales Dashboard is an interactive and visually appealing Power BI project designed to analyze and showcase sales information across various vehicle types. This dashboard provides a comprehensive overview of vehicle sales performance, with specific pages dedicated to different vehicle categories such as Motorcycles, Classic Cars, Trucks and Buses, Vintage Cars, Planes, Ships, and Trains. The project demonstrates advanced Power BI features like data transformations, DAX calculations, and interactive navigation.

![image](https://github.com/user-attachments/assets/3b0bc0af-ba4d-42ca-80ab-c246b4f993fc)


## Dataset Overview

The dataset used for this project includes sales data for different vehicle types. Key columns include:

Vehicle Type: Motorcycles, Classic Cars, Trucks and Buses, Vintage Cars, Planes, Ships, Trains

Sales Information: Sales amount, number of units sold, and average price

Geographic Details: Customer name, city, country, and postal code

Date Information: Order date (corrected and transformed for analysis)

Deal Details: Deal size, sales status

## Data Preparation

Data Import: The dataset was imported into Power BI from a CSV file.

Data Cleaning and Corrections:

Corrections were made to postal code, city, and country columns.

The date column was split into day, month, and year for better flexibility in analysis, and a new date column was created in Power Query.

## DAX Calculation:

A custom DAX measure, Sales Growth, was created to calculate month-over-month sales growth.

Dashboard Design

Pages and Visualizations

The dashboard consists of 7 pages, each dedicated to a specific vehicle type.

## Visual elements include:

Background Images: Pictures of each vehicle type used as page backgrounds.

Cards: Display key metrics such as total sales, sales growth, units sold, and average price.

Bar Graph: Show sales by status.

Pie Chart: Visualize sales distribution by deal size.

Column Chart: Illustrate yearly sales trends.

Slicers: Enable year-based filtering.

Interactive Navigation

## Page Navigation:

Two buttons on each page (left and right) allow users to navigate between pages.

## Menu Bar:

A button to open the menu bar reveals slicers for filtering by customer name, city, and country.

A close button hides the menu bar and its slicers for a clean layout.

## Purpose and Value

This dashboard project demonstrates:

Data Cleaning and Transformation: Handling inconsistencies in geographic and date fields.

Advanced DAX Calculations: Implementing sales growth measures.

Interactive Design: Enhancing user experience with navigation buttons and menu bars.

Visual Storytelling: Using vehicle-specific pages to present focused insights.

## How to Use

Clone or download this repository.

Open the Power BI file (.pbix) in Power BI Desktop.

Interact with the dashboard by using the slicers, navigation buttons, and visualizations to explore vehicle sales data.
