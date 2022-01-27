# Londinium - An example city of a transport ABM.

The Londinium is  a bigger, more realistic datasetthan Test Town that we can use it for testing our tools.

The Londinium dataset is comprised of:

- an OSM data file covering a region in west London
- a GTFS public transit schedule for the same geographical area
- a synthetic MATSim population of 100 agents with travel plans inside this region

## OSM Data
We chose the location so as to have a selection of different public transit modes, allowing us to see agents
interchange modes. We also wanted to have a mixture of major and minor roads, which this particular section of west
London gives us.

### Geographical Bounds
<kbd><img src="londinium-larger-context-map.png"/></kbd>
<kbd><img src="londinium-context-map.png"/></kbd>
<kbd><img src="londinium-map.png"/></kbd>

## Population Data
The Londinium synthetic population includes various activities, personal attributes and modes. The agents created
were classified into different subpopulations by gender and income. Activities are Home-to-Home round trips, all
within 24 hours. Daily activity plans for each agent were created using random choice. Agents choose different travel
modes such as bus, walk, car randomly for each trip.

### Population Files
| File                                       | Size   |
| -------------------------------------------|:-------|
| `data/londinium/population/population.xml` | 126k   |


It has been used to generate some scenarios' [data](https://github.com/arup-group/ersa/tree/main/data) using [matesto](https://github.com/arup-group/matesto) pipelines.

More information about the londinium can be found from this [link](https://github.com/arup-group/matesto/blob/main/data/londinium/DATASET.md)

The generation of londinium population are from a [notebook](https://github.com/arup-group/pam/blob/main/examples/04_Example-Create-Population-Londinium.ipynb) in [pam](https://github.com/arup-group/pam)

Visualization for activities and trips' legs from londinium dataset. 
![image](https://github.com/arup-group/londinium/blob/master/activities.png)
