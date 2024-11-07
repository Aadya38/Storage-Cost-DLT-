# README

This set of scripts calculates and verifies storage costs for dependency structures in linguistic data.

## Files
- **Input Files**:
  - `test.csv`, `total_f.csv`: Initial data files for calculating storage cost.
  - `computed_storage_cost_output.xlsx`: Intermediate file with computed storage costs.

- **Output Files**:
  - `storage_cost_output.csv`, `computed_storage_cost_output.xlsx`: Files with computed storage costs.
  - `recomputed_storage_cost_output.xlsx`: Final file with recalculated costs and any discrepancies.

## Usage
1. Place your input files (`test.csv`, `total_f.csv`) in the same directory as the scripts.
2. Run each script sequentially to calculate, verify, and save storage costs.
3. Discrepancies (if any) between computed and recalculated costs are flagged in the final output.

## Requirements
- Python 3.x
- pandas (`pip install pandas`)
