# Global inequality

Using the [World Inequality Database (WID)](https://wid.world/) for a new data visualisation and storytelling project.

In this repository I use mainly the js library [arquero](https://www.npmjs.com/package/arquero) to load, join and transform the data.

## Loading.js

In this script all individual country files are loaded in order to combine them with the option to choose are timeframe and as well as the variables.
The correponding code can be found [here](js/loading.js).

## Join.js

In this second step the final file is join with the general country file from WID to create a final dataset including all variables needed as well as applying some transformation [here](js/join.js).

## Wrangeling

Afterwards for running the first visualisations, we need to change the data format, filter, aggregate etc. The correponding code can be found [here](js/data_wrangeling.js).

Made with :green_heart: by [Patrick](https://www.linkedin.com/in/patrickwojda/) && [Sandra](https://www.sandraviz.com/bio) and support form [Austin](https://github.com/thataustin?tab=overview&from=2024-06-01&to=2024-06-12).
