# **Sustainability Tracker**

## **Description**
The **Sustainability Tracker** is a tool designed to help individuals and organizations monitor and track their resource usage (such as Paper, Plastic, Water, and Electricity) and calculate the associated environmental impact, specifically CO2 savings. This tracker encourages more sustainable practices by providing an easy way to quantify resource consumption and its impact on the environment.

## **Features**
- Track daily/weekly resource usage data (Paper, Plastic, Water, Electricity).
- Automatically calculate CO2 savings based on predefined conversion factors for each resource.
- Summarize the total quantity and CO2 impact for each resource category.
- Visualize sustainability trends and environmental impact using charts.

## **How to Use**
1. **Download the Spreadsheet**: Download the `Sustainability-Tracker.xlsx` file from this repository.
2. **Open the Spreadsheet**: Open the file in Google Sheets or Microsoft Excel.
3. **Fill in Data**:
   - **Date**: Enter the date of the activity (e.g., 01/09/2023).
   - **Category**: Choose a resource category from the dropdown list (Paper, Plastic, Water, Electricity).
   - **Quantity**: Enter the amount used in the corresponding unit (kg, liters, kWh).
   - **Unit**: Specify the unit of measurement (kg, liters, kWh).
4. The **Impact (CO2 Saved)** column will automatically calculate the CO2 savings based on the resource and quantity.
5. **Analyze**: Review the summary table to see the total resource usage and CO2 impact. You can also use charts to visualize trends and impacts.

## **Sample Data**

| Date       | Category   | Quantity | Unit   | Impact (CO2 Saved) |
|------------|------------|----------|--------|--------------------|
| 01/09/2023 | Paper      | 19       | kg     | 0.0285             |
| 02/09/2023 | Water      | 35       | liters | 0.105              |
| 03/09/2023 | Water      | 19       | liters | 0.057              |
| 04/09/2023 | Plastic    | 25       | kg     | 0.05               |
| 06/09/2023 | Electricity| 45       | kWh    | 22.5               |

## **Calculations**
The **Impact (CO2 Saved)** column automatically calculates the CO2 savings based on the amount of resource used. Conversion factors (e.g., 0.0015 for Paper, 0.003 for Water) are used to estimate the impact in tons of CO2 saved.

For example:
- 10 kg of Paper saves 0.015 tons of CO2.
- 20 liters of Water saves 0.06 tons of CO2.

## **Summary Section**
- **Total Quantity** and **Total Impact** for each resource category are calculated automatically.
  Example:
  - Total Paper usage: 120 kg
  - Total CO2 Saved from Paper: 0.18 tons

## **Visualizations**
Visualize your data with charts:
- Insert Pie or Bar charts to display resource distribution or trends over time.
- Customize the charts to show the most important data points.

## **License**
This project is open-source and available under the **MIT License**.

## **Contributions**
Feel free to contribute to the project by submitting issues or pull requests.
