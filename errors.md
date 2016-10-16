
# Errors in utab API

## System Errors

Infrastructure-level errors should be represented by HTTP Status Code.

## Application Errors

Application-level errors should return Error Object in error property of response.

### Importing Data

#### [0] Tournament Not Found

```
{
  "statusCode": 0,
  "statusText": "Tournament Not Found",
  "message": "No such tournament name: 'test tournament'",
}
```




