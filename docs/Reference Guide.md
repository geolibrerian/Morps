## Buffer

Used to created a buffer for any point, line, or polygon file. Currently no attribute information is carried over into the output file (working on it!).

#### Creation
buffer(*Input File*, *Output File*, *Buffer Distance*, *File Type*)

#### Arguments

Argument | Type | Description
--- | --- | ---
input file | string | File to be buffered. Supported types are .shp, .geojson, and .kml
output file | string | File containing results of the buffer geoprocess. Will be the same output file type as input file
buffer distance | string | Size of buffer. Units currently calculated as degrees, sorry!
file type | string | *Optional:* specify type of file. Currently accepts *shp*,*json*, and *kml* as string arguments. Defaults to *shp* if no argument is passed. 