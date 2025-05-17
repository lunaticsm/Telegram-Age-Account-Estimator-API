API Usage Guide

Endpoint

The API can be accessed using the following URL format:

https://age.lunaticsm.web.id/{id}

Example

To get the age data for the ID 1983980399, use:

https://age.lunaticsm.web.id/1983980399

Response Format

The API will return a JSON response in the following format:

{
  "status": "aprox",
  "date": "11/2013",
  "age": 11
}

status: Indicates whether the ID is older_than, newer_than, or aprox (approximate).

date: The estimated date in the format MM/YYYY.

age: The calculated age in years.



