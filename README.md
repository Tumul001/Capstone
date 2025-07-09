# Dynamic Pricing for Urban Parking Lots

This project implements a dynamic pricing system for urban parking lots using real-time data analysis and machine learning techniques.

## Project Overview

The system uses multiple pricing models to optimize parking lot prices based on:
- Real-time occupancy rates
- Queue lengths
- Traffic conditions
- Special events
- Vehicle types
- Competitive pricing from nearby lots

## Files Description

- `Main.ipynb` - Main Jupyter notebook containing the complete implementation
- `Sample_Notebook.ipynb` - Additional notebook with sample implementations
- `dataset.csv` - Real-world parking lot data
- `problem statement.pdf` - Project requirements and problem definition

## Pricing Models Implemented

1. **Baseline Linear Model** - Simple occupancy-based pricing
2. **Demand-Based Model** - Multi-factor demand calculation
3. **Competitive Model** - Considers nearby competitor prices

## Key Features

- Real-time simulation loop
- Interactive visualizations using Bokeh
- Price smoothing for stability
- Geospatial competitor analysis
- Multiple vehicle type support

## Dependencies

- pandas
- numpy
- bokeh
- pathway
- scipy

## Usage

1. Install required packages: `pip install pandas numpy bokeh pathway scipy`
2. Run the `Main.ipynb` notebook
3. The system will process the dataset and generate price recommendations

## Future Enhancements

- Integration with Pathway streaming for real-time deployment
- Machine learning model optimization
- Mobile app integration
- Payment system integration
