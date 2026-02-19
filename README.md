📊 Interactive Data Visualization Masterclass
Project Overview
This project is a comprehensive guide to building interactive, web-ready visualizations using Python. It moves beyond static imagery to create dynamic tools where users can filter, zoom, and explore datasets to find their own insights.

Why Interactivity?
In modern data science, the ability to interact with data is crucial. This project demonstrates three core pillars of interactivity:

Filters: Allowing users to isolate specific categories or ranges.

Hover Effects: Displaying deep-dive details without cluttering the visual space.

Zoom Features: Enabling granular inspection of dense or high-frequency data.

🛠️ Technology Stack & Libraries
Plotly Express: Used for building high-level interactive scatter and line plots with built-in dropdown menus and range sliders.

Bokeh: Utilized for advanced, highly-customizable browser-based visualizations, including the HoverTool and WheelZoomTool.

Python: Core logic and data manipulation.

Iris Dataset: Used as the primary benchmark for demonstrating these interactive features.

🚀 Key Features Implemented
Dropdown Filters (Plotly): A functional menu that allows users to filter the Iris dataset by species in real-time.

Range Sliders: Interactive x-axis sliders that let users zoom into specific numerical ranges.

Custom Tooltips: Enhanced hover templates that display multiple data dimensions (Sepal/Petal dimensions) in a clean, organized format.

Interactive Drag Modes: Implementation of different mouse behaviors like "Pan," "Lasso Select," and "Box Select."

Bokeh Widgets: Integration of specialized tools like the Wheel Zoom and custom hover glyphs.

🖼️ Visualizations Included
Interactive Species Classifier: A scatter plot with categorical dropdowns.

Time-Series Zoom Tool: A line plot demonstrating how to handle dense data points.

Detail-on-Demand Plots: Charts that reveal underlying data statistics only when prompted by the user's cursor.

📁 How to Use
Open the Designing_Interactive_Visualizations.ipynb notebook in this repository.

Click the "Open in Colab" badge.

Run the cells to generate the interactive HTML objects.
Note: Since these are interactive web components, they are best viewed in an active Jupyter or Colab environment.
