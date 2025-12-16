# Terrain & Habitat Mapping (Private Land Study)

## Purpose
A learning-focused GIS project to demonstrate terrain analysis, spatial reasoning, and clear documentation using QGIS.  
This project applies elevation data and field knowledge to understand access, drainage, and movement patterns on a privately managed land parcel.

## 1) Research Question
**Primary question:**  
How do terrain, slope, and drainage patterns influence human access routes and animal movement across a privately managed property?

**Secondary questions:**
- Where do slope and micro-topography constrain or channel movement?
- How do drainage features shape natural travel corridors?
- Which access routes minimize disturbance while maintaining terrain feasibility?

## 2) Why This Matters Spatially
Movement across landscapes is constrained by elevation, slope, and hydrology.  
Understanding these spatial factors is essential for land management, habitat interpretation, and terrain-based decision making.

This analysis emphasizes:
- Terrain-driven movement rather than assumed paths
- The interaction between human access and environmental constraints
- Spatial context derived from elevation, not anecdote

## 3) Study Area
- **Location:** Privately managed rural property (exact location withheld)
- **Scale:** Parcel-level terrain analysis
- **Access:** Field-observed with on-site familiarity

## 4) Data

### Included
- Digital Elevation Model (DEM)  
  - Source: Publicly available elevation data  
  - Resolution: Documented per dataset  
  - Format: GeoTIFF

### Excluded / Not Used
- Wildlife population datasets
- GPS collar or tracking data
- Personally identifying location data

### Data Limitations
- DEM resolution limits micro-scale interpretation
- Elevation-derived flow paths are approximations
- Field observations are qualitative and non-instrumented

## 5) Methods

### In plain language
- Examined elevation surfaces to understand terrain form
- Derived slope and hillshade to interpret movement difficulty
- Identified drainage patterns influencing travel corridors
- Integrated field knowledge to contextualize spatial patterns

### Tools / algorithms
- QGIS: DEM visualization and raster analysis
- QGIS Processing: Slope and hillshade generation
- Manual digitization informed by field observation

## 6) Scope

### Included
- Terrain and slope interpretation
- Drainage pattern visualization
- Access and movement reasoning based on spatial form

### Out of Scope (Explicitly Excluded)
- Wildlife management recommendations
- Hunting strategy or tactical guidance
- Legal, safety, or environmental compliance analysis
- Population or behavioral modeling

## 7) Outputs (Current)
- Planned terrain visualization maps
- Draft movement and access interpretation
- Status: In progress

## 8) Next Steps
- Generate finalized hillshade and slope rasters
- Export first terrain overview map
- Document assumptions and uncertainty
- Add visual outputs to repository

## File Management Note
Raw data and working QGIS project files are stored locally.  
This repository contains documentation and selected outputs only.
