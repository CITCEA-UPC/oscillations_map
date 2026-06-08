# CITCEA Oscillation Database

Interactive map visualization of oscillation data from the Spanish electrical grid.

## Deployment

The application is deployed via GitHub Pages and accessible at:
- https://citcea.oscillations.upc.edu
- https://citcea-upc.github.io/oscillations_map

## Repository Structure

- `docs/` - Static site deployed to GitHub Pages (index.html, oscillation data, assets)
- `src/` - Legacy Flask application (deprecated)
- `legacy/` - Previous versions of the project
- `resources/` - Additional resources and documentation

## Data

The oscillation data is stored in `docs/oscillation_data.json` and is automatically loaded by the frontend.

## Analytics

- **GoatCounter**: Privacy-friendly analytics at https://alexandregracia.goatcounter.com
- **Visit counter**: Uses counterapi.dev service
