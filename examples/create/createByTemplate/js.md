```javascript
const response = await fetch(
  "https://dev.demo.sensenet.com/OData.svc/Root/Content('IT')",
  {
    credentials: "include",
    method: "POST",
    body:
      "models=[" +
      JSON.stringify({
        __ContentType: "EventList",
        __ContentTemplate: "Calendar",
        DisplayName: "Calendar",
        Index: 2
      }) +
      "]"
  }
);
```
