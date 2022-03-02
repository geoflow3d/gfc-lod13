To run with geoflow/geof download the whole repository (leave the directory structure intact) and run the `runner.json` flowchart. 

## Testing
By default `runner.json` should load the test data from the `test-data` folder. And when you run it should produce output in the obj and cityjson folders (they will be created).

NOTE. If you have not setup a postgres database you might want to remove the OGRWriter nodes (in the gui: shift+click and press delete)
