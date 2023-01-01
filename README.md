# energyPlots
Movies of the World's energy supply and demand.

Data from [BP Statistical Review or World Energy](https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy.html) and [The World Bank Population](https://data.worldbank.org/indicator/SP.POP.TOTL?view=chart).

Made in Jupyter Notebooks using Python, Matplotlib, Pandas, and [celluloid](https://github.com/jwkvam/celluloid). To play the animation in the notebook, you may need to install [ffmpeg](https://www.ffmpeg.org/download.html).

This is one example, primary energy consumption versus CO2 emissions:

<video src="https://user-images.githubusercontent.com/54630348/210180214-f5176b7b-1434-4ce6-9152-ec9f70e3d8d0.mp4"></video>

Points are color coded by region and their size represents population. Regions are as follows:

1. North America: Pale green
2. South and Central America: Dark green
3. Europe: Blue
4. CIS: Magenta
5. Middle East: Orange
6. Africa: Red
7. Asia Pacific: Yellow

Axes are logarithmic. x and y axes are not at the same scale. When comparing cross-plotted variables, please pay attention to the orders or magnitude.

Any comments or questions, please contact me at [nestor.cardozo.uis.no](nestor.cardozo@uis.no)
