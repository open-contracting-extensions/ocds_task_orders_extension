# Task Orders

This extension enables the recording of task orders within the implementation section of an OCDS release. Task orders are specific scopes of work issued under a base contract, commonly used in contexts like On-Call contracts or Price Agreements.

## Example

```json
{
  "contracts": [
    {
      "awardID": "31001472",
      "implementation": {
        "taskOrders": [
          {
            "id": "31001472-1",
            "title": "Gateway Greenway Final Design",
            "purchaseOrderID": "22267952",
            "executionPeriod": {
              "startDate": "2019-11-18T00:00:00-0700",
              "endDate": "2021-01-31T00:00:00-0700"
            },
            "value": {
              "amount": 91145,
              "currency": "USD"
            }
          }
        ]
      }
    }
  ]
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.
