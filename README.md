# energyPlots
Animations of the World's energy supply and demand.

Data from [The Energy Institute Statistical Review or World Energy](https://www.energyinst.org/statistical-review) and [The World Bank Population](https://data.worldbank.org/indicator/SP.POP.TOTL?view=chart).

Made in Jupyter Notebooks using Python, Matplotlib, Pandas, and [celluloid](https://github.com/jwkvam/celluloid). To play the animation in the notebook, you may need to install [ffmpeg](https://www.ffmpeg.org/download.html).

This is one example, primary energy consumption versus CO2 emissions:

https://github.com/nfcd/energyPlots/assets/54630348/15f8b974-e478-4136-a665-890093c1c869

Points are color coded by region and their size represents population. Regions are as follows:

1. North America: Pale green
2. South and Central America: Dark green
3. Europe: Blue
4. CIS: Magenta
5. Middle East: Orange
6. Africa: Red
7. Asia Pacific: Yellow

Axes are logarithmic. x and y axes are not at the same scale. When comparing cross-plotted variables, please pay attention to the orders or magnitude.

*NEW:*

In the movies folder, there are other type of animations using the ipyvizzu library: gas production, oil reserves and production, and primary energy consumption and CO2 emissions per capita.

Any comments or questions, please contact me at [nestor.cardozo.uis.no](mailto:nestor.cardozo@uis.no)
