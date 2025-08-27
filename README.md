# Ocean Data Visualization and Metrics Analysis

This project provides tools for visualizing and analyzing ocean data, including super-resolution comparison and metrics evaluation.

## Project Structure

```
visualization_and_metric/
├── ocean_metrics_results.json          # Computed metrics results
├── visualization_and_metric.ipynb      # Main Jupyter notebook for analysiss
└── data/
    └── static/
        ├── lat.npy                     # Latitude demo data
        ├── lon.npy                     # Longitude demo data
        └── mask.npy                    # Ocean mask data
```

## Features

- **Ocean Data Visualization**: Create comprehensive visualizations of ocean datasets
- **Super-Resolution Analysis**: Compare different super-resolution methods for ocean data
- **Metrics Computation**: Calculate and analyze various performance metrics
- **Geographic Mapping**: Utilize latitude/longitude coordinates for spatial analysis

## Requirements

```python
numpy
matplotlib
jupyter
latex
# Add other specific requirements based on your notebook
```

## Usage

### Running the Analysis

1. Open the Jupyter notebook:
```bash
jupyter notebook visualization_and_metric.ipynb
```

2. The notebook contains the complete workflow for:
   - Loading ocean data from the `data/static/` directory
   - Performing visualization analysis
   - Computing metrics for super-resolution comparison
   - Generating comparison plots

### Data Files

- **`lat.npy`**: Contains latitude coordinates of Guangdong-Hong Kong-Macao Greater Bay Area as a demo
- **`lon.npy`**: Contains longitude coordinates, same as `lat.npy`
- **`mask.npy`**: Ocean mask to define valid data regions
- **`ocean_metrics_results.json`**: Stored results from metrics computation

## Output

The analysis generates:
- Quantitative metrics stored in JSON format
- Visual comparisons saved as PNG images
- Interactive plots within the Jupyter notebook

## Getting Started

1. Clone or download this project
2. Install required dependencies
3. Place your ocean data in the appropriate format in `data/static/`
4. Run the Jupyter notebook to perform the analysis

## Notes

- Ensure your ocean data is properly formatted as NumPy arrays
- The mask file should correspond to valid ocean regions in your dataset
- Coordinate files should match the spatial dimensions of your data