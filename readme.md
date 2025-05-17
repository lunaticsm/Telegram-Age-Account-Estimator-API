# Telegram Account Age Estimation API

## API Usage Guide

### Endpoint
The API can be accessed using the following URL format:

```
https://age.lunaticsm.web.id/{id}
```

### Example
To retrieve the age data for a specific ID (e.g., `1983980399`), use the following URL:

```
https://age.lunaticsm.web.id/1983980399
```

### Response Format
The API will return a JSON response in the following format:

```json
{
  "status": "aprox",
  "date": "11/2013",
  "age": 11
}
```

#### Field Descriptions:
- **status**: Indicates the estimated accuracy of the ID. Possible values are:
  - `older_than`: The ID is older than the estimated age.
  - `newer_than`: The ID is newer than the estimated age.
  - `aprox`: The age is approximate.
- **date**: The estimated date in the format `MM/YYYY`.
- **age**: The calculated age in years.
