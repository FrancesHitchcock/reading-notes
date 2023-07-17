# Module 3 Class 13 Reading Notes

## Local Storage

Local storage: [Smashing Magazine](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

### Why a dev might use local storage for a web app

Local storage is useful for when you want a user to be able to access a previous state when returning to a web app when the state has not been saved to the server.

### Information that should **not** be stored in local storage

Information that only needs to be stored during the session should be saved to session storage rather than local storage.

### Local storage data type

Only strings can be saved to local storage. Other data types need to be stringified first using JSON.stringify() and then parsed on retrieval using JSON.parse()

## The Past, Present and Future of Local Storage

Local storage: [HTML5 Doctor](http://diveinto.html5doctor.com/storage.html)
