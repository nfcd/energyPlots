# energyPlots
Movies of the World's energy supply and demand.

Data from [BP Statistical Review or World Energy](https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy.html) and [The World Bank Population](https://data.worldbank.org/indicator/SP.POP.TOTL?view=chart).

Made in Jupyter Notebooks using Python, Matplotlib, Pandas, and [celluloid](https://github.com/jwkvam/celluloid). To play the animation in the notebook, you may need to install [ffmpeg](https://www.ffmpeg.org/download.html).

This is one example, primary energy consumption versus CO2 emissions:

https://github.com/nfcd/energyPlots/assets/54630348/08d7af6a-a257-4562-8543-f05adc8788dd

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

This is another type of animation using the ipyvizzu library:

https://github.com/nfcd/energyPlots/assets/54630348/b517ec88-e27f-4ad1-b9f8-0bb15647526d

Similar animations for oil reserves and oil production are included.

Any comments or questions, please contact me at [nestor.cardozo.uis.no](mailto:nestor.cardozo@uis.no)
