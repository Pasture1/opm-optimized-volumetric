I noticed that [OPM volumetric](https://spacedock.info/mod/3498/Outer%20Planets%20Mod%20-%20Volumetric%20Clouds) clouds by OneSaltyPringle had low performance. I found out that this is due to flowmaps that was used. This fixes that by replacing those flowmaps with the one from jool giving a 5x performance boost

# Install

### Removing OPM related files
Remove all OPM related files and ScattererAtmosphereCache. Launch the game, create a new save and load into it. Now close the game and reinstall all the things you removed (besides ScattererAtmosphereCache).
Note that this step is not necessary in most if not all cases, but I highly recomend removing at least ScattererAtmosphereCache

### Removing perfomance impacting files from PoodsOPMVO
> [!NOTE]
> Do this regardless of using custom configs or not

Go to PoodsOPMVO and remove the following:

- clouds.cfg

- MiniAVC.dll 

- Scatterer (folder)

### Installing new config
Go to the gamedata folder and drag everything out of the zip file into it. If it asks, press overwrite. If you wish you can also just copy the text from Clouds.cfg into StockVolumetricClouds/Clouds/clouds.cfg

> [!WARNING]
> While this does drastically improve performance, it is still not as performant as it should be. It seems to be a fundamental issue with OPM
