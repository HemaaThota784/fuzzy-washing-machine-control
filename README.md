# Enhanced Washing Machine Fuzzy Logic System

A fuzzy logic control system for an intelligent washing machine that determines optimal washing parameters based on multiple input variables.

## Features

- **Multi-parameter fuzzy logic control** with 4 input variables:
  - Laundry weight (0-8 kg)
  - Dirt level (1-10)
  - Fabric type (Delicate, Wool, Cotton, Synthetic, Heavy Duty)
  - Water hardness (1-10)

- **Three optimized outputs**:
  - Powder required (grams)
  - Wash time (minutes)
  - Water temperature (°C)

- **Advanced visualization**:
  - 3D membership function plots
  - 3D surface plots for output variables
  - Comparative 3D analysis

## Requirements
```
numpy
scikit-fuzzy
matplotlib
scipy
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/fuzzy-washing-machine.git
cd fuzzy-washing-machine
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

Run the program:
```bash
python fuzzy.py
```

Follow the interactive menu to:
1. Calculate washing parameters for specific inputs
2. Visualize 3D membership functions
3. View 3D surface plots for different outputs
4. Compare all outputs simultaneously

## Example
```python
# Input
Laundry Weight: 5 kg
Dirt Level: 7
Fabric Type: 3 (Cotton)
Water Hardness: 6

# Output
Powder Required: 45.23 grams
Wash Time: 85.67 minutes
Water Temperature: 65.42°C
```
