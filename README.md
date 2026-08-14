# GBBO Star Baker Performance Tableau Dashboard
Interactive Tableau visualization for analyzing baker performance in The Great British Baking Show (GBBO).

## Live Interactive Dashboard
Open the fully interactive online Tableau Viz:
https://public.tableau.com/views/StarBakerperformancefortheGBBO/BakerPerformance?:language=zh-CN&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Project Overview
This dashboard analyzes competition performance metrics of all contestants in GBBO, including:
- Star Baker winning frequency per contestant
- Episode-level scoring & elimination trends
- Performance comparison across different baking categories
- Filterable multi-dimensional contestant ranking analysis

## File Description
1. `tableau_source/baker_performance.twbx`
    Packaged Tableau workbook with embedded raw dataset, directly openable via Tableau Reader / Tableau Desktop.
2. `tableau_source/baker_performance.twb`
    Plain-text Tableau workbook for Git version control tracking.
3. `dataset/gbbo_baker_data.csv`
    Raw open dataset of GBBO contestants, challenge scores and elimination records.
4. `dashboard_preview.png`
    Static screenshot of the full visualization dashboard.

## How to Use
### 1. View Online (No Software Required)
Visit the Tableau Public link above to browse interactive filters, charts and rankings.

### 2. Open Local Source File
1. Clone this repository
```bash
git clone https://github.com/YourName/GBBO-Star-Baker-Performance-Tableau-Dashboard.git
cd GBBO-Star-Baker-Performance-Tableau-Dashboard
