Redirection-Crawler
============

The redirection crawler follows all the redirects of a domain, while saving
the corresponding domains and their returned status code.

## Table Columns

| Column |  Description |
| ----------- | ----------- |
| Redirects |  Number of redirects gotten from this site |
| StatusCodes | List of status codes received from each step along the redirect chain |
| URLs | List of all urls received along the redirect chain |
| LastIP | IP of the last host, that was crawled |
| LastStatusCode | Last status code that was returned |
| LastURL | Last crawled URL |
| ScanStatus | Pending: 0, Done: 1, Ignored: 2, Error: 255 |


 

