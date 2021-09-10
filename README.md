# Scatter Gather Error Handling

If one of the route gets faild in scatter gather, it will through an error and wont get output of successfully completed router.

Note: If one of the route gets faild, paralally it will complete other routes but it will throws an error.

We have to handle such type of errors either at processor level or flow level.

Scatter Gather error types:

```
MULE:ROUTING
MULE:COMPOSITE_ROUTING
```
