# energyPlots
Animations of the World's energy supply and demand.

Data from the [statistical review or world energy](https://www.energyinst.org/statistical-review) and the [World Bank population](https://data.worldbank.org/indicator/SP.POP.TOTL?view=chart).

Made in Jupyter Notebooks using Python, Matplotlib, Pandas, and [celluloid](https://github.com/jwkvam/celluloid). To play the animation in the notebook, you may need to install [ffmpeg](https://www.ffmpeg.org/download.html).

This is one example, primary energy consumption versus CO2 emissions:

https://github.com/user-attachments/assets/a74d512b-dfb8-4b3a-961b-61e2564599f5

Points are color coded by region and their size represents population. Regions are as follows:

1. North America: Pale green
2. South and Central America: Dark green
3. Europe: Blue
4. CIS: Magenta
5. Middle East: Orange
6. Africa: Red
7. Asia Pacific: Yellow

Axes are logarithmic. x and y axes are not at the same scale. When comparing cross-plotted variables, please pay attention to the orders or magnitude.

**NEW:** In the movies folder, there are other type of animations using the ipyvizzu library. This is one example: Primary energy consumption per capita:

https://github.com/nfcd/energyPlots/assets/54630348/ff90c3f9-53b9-4a5c-a8e7-8974c78b1938

**Latest update:** 2024. Note that in the 2024 stat. rev. of world energy dataset some sheet names were changed by the Energy Institute (this is rather sloppy and unfortunate).

Any comments or questions, please contact me at [nestor.cardozo.uis.no](mailto:nestor.cardozo@uis.no)
