

**Table of Contents**
- [SmartDS Download](#smartds-download)
- [Project Tools](#project-tools)
- [SmartDS Tutorial](#smartds-tutorial)
- [SmartDS Dashboard](#smartds-dashboard)


# SmartDS Download


<p align="center"><img src="0_images/AWS_CLI_Download.png" width="500" /></p>

<p align="center"><img src="0_images/Notebook_directory.png" height="100" /></p>
     

### Caution 
- Due to changes to OpenDSS made since the publishing of SmartDS changes need to be made to SmartDS `PVSystems.dss` files prior to any PV scenario simulations. Unfortunately there is a `PVSystems.dss` file in every scenario for every feed. Use find/replace in lieu of a custom script:
  - VV_RefReactivePower --> RefReactivePower
  - kvarlimit --> kvarmax

# Project Tools
- **Opendssdirect**  
- **Holoviz** Both the tutorial and dashboard use [Holoviz tools](https://holoviz.org/index.html) extensively. HvPlot, Holoviews, Geoviews and Panel are the core visualization tools in this project.

# SmartDS Tutorial

- Explain how the SmartDS dataset is organized and how it can be used in a customized fashion
- Tutorial will explain how the dashboard is created 
- Tutorial will serve as a sandbox environment for the Dashboard
- Format is a jupyter 

# SmartDS Dashboard
The SmartDS

Below is a prototype dashboard illustrating a Panel layout of SmartDS data and widgets.
<p align="center">
<img src="0_images/SmartDS_dashboard_mockup.png" 
     height="300" />
</p>


