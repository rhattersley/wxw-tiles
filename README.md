# wxw-tiles

Good Things:

* Minimal chatter for discovery & metadata
  * e.g. Single request for array metadata, parameter metadata, and coordinate data & metadata.
* Highly scalable for data volume & concurrent reads
  * Volumes into TBs (e.g. split into tens of thousands of chunks)
  * Concurrency into the hundreds
  * Bulk transfer supported by existing cloud object stores
    * Compatible with read-after-write consistency
* Readable via existing software, or at least by largely building on existing software
* Supports appending to existing datasets

Building blocks:

* Cloud-native labelled array
* Parameter defn convention
* Coordinate reference system convention
