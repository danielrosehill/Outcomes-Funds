# Get all data as JSON from the API

There is a public API that lets you download all the data as JSON.

To get a list of data objects available, fetch:

- https://golab-indigo-data-store.herokuapp.com/app/api1/project for projects

- [https://golab-indigo-data-store.herokuapp.com/app/api1/organisation](https://golab-indigo-data-store.herokuapp.com/app/api1/organisation) for organisations

These will provide a list of ID’s and whether the data associated with that ID is public at this time. For each record that is public, you can then fetch another URL to get the data.

- https://golab-indigo-data-store.herokuapp.com/app/api1/project/INDIGO-POJ-0009  for a specific project

- https://golab-indigo-data-store.herokuapp.com/app/api1/organisation/INDIGO-ORG-0016 for a specific organisation

Just put the ID of the project or organisation you want to fetch in the URL.


