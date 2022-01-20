![](../6-4-challenge-image.png)


# Find Viable Real Estate Investment Opportunities
## Data visualization: creating interactive visualizations PyViz  and Mapbox API
 




- [Function]
- [How to Install]
- [How to use]
- Technologies used
    - [Libraries] 
    - [Interfaces] 



## Function

This tool can be used to find investment opportunities in real estate.



## How to install


* Open a Jupyter Lab:

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ san_francisco_housing.ipynb ] file to see the analysis report.



## How to use

 
Mapbox API key save as .env file. 

```
 cmd + shift + [.]
```
For Mapbox API key go to https://www.mapbox.com/ Create account and request a new key. 






Save as .env file name the variable MAPBOX_API_ACCESS_TOKEN





```
MAPBOX_API_ACCESS_TOKEN = '<your key>'
```

  


## Technologies used

### Libraries


Pandas- a software library written for the Python programming language for data manipulation and analysis.
Import the following libraries;

```
import os
import pandas as pd
import plotly.express as px
import hvplot.pandas
from pathlib import Path
from dotenv import load_dotenv
```






### Interfaces

* Jupyter Lab
* GitHub
* Mapbox - Maps and location for developers ( https://www.mapbox.com/ )



   

---

Phil Hills

* Email:(bphilhills@gmail.com) 




---

* License

MIT
