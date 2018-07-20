<link rel="stylesheet" href="tufte.css"/>
# The `metadata_return` class     [[source]](https://github.com/Kristianuruplarsen/PyDST/blob/master/PyDST/connection/connection.py)
Contains the return of a metadata call. This is a return class for responses from `connection.get_metadata()`.

_Parameters:_
* response: a raw requests response served by `connection.get_metadata()`.

_Attributes:_
* `json`: json of raw data, quite usefull to look at
* `id`: ID of table
* `description`: description of table
* `unit`: measurement unit of table
* `last_updated`: last date of update of the table
* `active`: active status of table
* `contacts`: contact info on table maintainer if it exists