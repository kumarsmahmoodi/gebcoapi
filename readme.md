# GEBCO API (FastAPI-based)

This app provides elevation data using the GEBCO 2024 dataset through a user-friendly web interface and API.

## Features
- Point and batch queries via REST API
- Returns depth from GEBCO 2024 NetCDF
- HTML interface for interactive use
- MATLAB examples included

## How to Run
1. Install requirements: `pip install -r requirements`
2. Run: `uvicorn gebco_api.main:app --reload`
