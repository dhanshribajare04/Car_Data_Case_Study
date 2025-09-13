Vehicle Data Analysis Case Study
This project presents a data analysis case study on a dataset containing information about various vehicles. The analysis explores relationships between different vehicle attributes to uncover insights about performance, efficiency, and country-specific preferences.

Dataset
The dataset, cars.csv, includes the following columns:

mpg: Miles per gallon

cylinders: Number of cylinders

cubicinches: Engine size in cubic inches

hp: Horsepower

weightlbs: Weight in pounds

time-to-60: Time to reach 60 mph

year: Model year

brand: Country of origin (US, Europe, or Japan)

Analysis Questions
The core of this analysis is to answer several key questions about the dataset:

Is there an improvement in miles per gallon (mpg) over the years?

How does the engine size (cubic inches) affect the time to reach 60 mph?

Do specific countries tend to prefer vehicles with more horsepower?

What is the relationship between a vehicle's horsepower and its mpg?

How do cubic inches affect a vehicle's mpg?

What is the effect of the number of cylinders on a vehicle's mpg?

What is the relationship between cubic inches, cylinders, and horsepower?

What proportion of the total records are occupied by vehicles with 8 cylinders?

Key Findings
The analysis in the Jupyter Notebook (Data Analysis Case Study - Vehicles Data (1).ipynb) yielded the following main findings:

MPG vs. Year: There is a clear and gradual improvement in the average miles per gallon of vehicles over the years included in the dataset.

Cubic Inches vs. Time-to-60: A vehicle's engine size has an inverse relationship with the time it takes to reach 60 mph. As cubic inches increase, the time to accelerate to 60 mph decreases.

Horsepower vs. Brand: The analysis suggests that vehicles from the US tend to have higher horsepower compared to those from Europe and Japan.

Horsepower vs. MPG: There is a strong inverse relationship between horsepower and miles per gallon. As horsepower increases, mpg tends to decrease.

Cubic Inches vs. MPG: Similar to horsepower, cubic inches have an inverse relationship with mpg. Vehicles with larger engines generally have lower miles per gallon.

Cylinders vs. MPG: The number of cylinders is also inversely proportional to mpg. As the number of cylinders increases, mpg decreases.

Relationship between Cubic Inches, Cylinders, and Horsepower: These three variables are directly proportional to each other. Higher cubic inches are associated with more cylinders and more horsepower.

8-Cylinder Vehicles: Approximately 30% of the vehicles in the dataset have 8 cylinders.

How to Use
To explore the analysis, simply open the Jupyter Notebook file in a compatible environment such as Jupyter, JupyterLab, or VS Code. The notebook contains all the Python code, visualizations, and detailed explanations of the findings.
