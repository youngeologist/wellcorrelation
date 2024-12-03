
# Well Correlation App 
The app utilizes a straightforward workflow to visualize well log correlations:

## 1. Data Setup:

Template-based Data Input: utilize the pre-formatted XLS file template to store well log and marker data for your reference wells.
File Format:
<li>HEADER Sheet: This sheet requires a minimum of two columns - WELLNAME and RTE.</li>
<li>LOGDATA Sheet: This sheet requires the following columns: DEPTH, TVD, GR, RESDP, DEN, NEU. </li>
<li>MARKER Sheet: This sheet requires two columns: MARKER (name of the marker) and TVDSS (depth of the marker)</li>

## 2. Basic Features:

<li>Multi-well Correlation: Display correlations for up to four wells simultaneously.</li>
<li>Horizon/Marker Flattening: Simplify comparison by flattening horizons and markers in the visualization.</li>
<li>Interactive Gamma Ray fill adjustment: Each well has a dedicated slider for adjusting the GR curve fill based on a custom shale baseline.</li>

## 3. Marker Management:
Currently, the app doesn't offer dedicated marker management functionality. To add or edit markers, simply update the "MARKER" sheet in your XLS file and re-upload it. The changes will then reflect in the app.
