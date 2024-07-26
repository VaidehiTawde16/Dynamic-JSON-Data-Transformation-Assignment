# Dynamic-JSON-Data-Transformation-Assignment

## Problem Statement:
To create a JSON data transformation using the provided source JSON (BoxPlot data). The objective is to transform the source JSON into a specified format dynamically, without hardcoding any values. The transformation should handle any number of dimensions and measures present in the source JSON.

Given the source JSON (BoxPlot data), the output JSON format will be as follows:

![image](https://github.com/user-attachments/assets/60277cd0-2dd7-4ea2-829f-a2573d46ed3f)



## Approach:
Read Source JSON:

Extract dimension and measure names from the source JSON metadata dynamically.
Identify the number of dimensions and measures.

Build Transformation Logic:

Construct the header row for the output JSON using the identified dimensions and measures.
Iterate through the source JSON data to create corresponding rows for the output JSON.

Dynamic Handling:

Ensure the code is generic and adaptable to source JSON with any number of columns.
The logic is built to include all dimensions and measures present in the source JSON.

Output Structure:

The transformed JSON is structured to have a dataset with an ID and a source array, containing the header row and data rows.

## Outcome:
A JavaScript function that reads the source JSON, dynamically identifies dimensions and measures, and transforms the data into the required output format.
The code is reusable and adaptable to various source JSON structures without modification.

## Output Screenshot:

![image](https://github.com/user-attachments/assets/03d4ea18-4bfd-4e32-9b5b-fe50be618f06)



