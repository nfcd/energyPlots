# energyPlots
Movies of the World's energy supply and demand.

Data from [BP Statistical Review or World Energy](https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy.html) and [The World Bank Population](https://data.worldbank.org/indicator/SP.POP.TOTL?view=chart).

Made in Jupyter Notebooks using Python, Matplotlib, Pandas, and [celluloid](https://github.com/jwkvam/celluloid). To play the animation in the notebook, you may need to install [ffmpeg](https://www.ffmpeg.org/download.html).

This is one example:

<video src='../movies/PrimEnVsCO2.mp4' width=320/>

Points are color coded by region and their size represents population. Regions are as follows:

1. North America: Pale green
2. South and Central America: Dark green
3. Europe: Blue
4. CIS: Magenta
5. Middle East: Orange
6. Africa: Red
7. Asia Pacific: Yellow

Axes are logarithmic. x and y axes are not at the same scale. Please pay attention to the orders or magnitude.