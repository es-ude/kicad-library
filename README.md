# kicad-library
In this repo a design library is shared for common designs in KiCAD. It concludes the symbol, footprint and 3D models.

## Using library
For using the 3D models, you have to add the path to the KiCAD variable ${KICAD8_OWNLIB_DIR} over the main window. There you click on Settings/Prerefences -> Path configuration. Add there the name `KICAD8_OWNLIB_DIR` with the path `${LOCAL_PATH_TO_GIT}/kicad-library/library`. Afterwards, you have to add the libraries for symbols and footprints in 
separately in the libraries.