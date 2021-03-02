# Task.FromResult&lt;TResult&gt; method

Creates a [`Task`](../Task-1.md) that is completed successfully with the specified result.

```csharp
public static Task<TResult> FromResult<TResult>(TResult result)
```

| parameter | description |
| --- | --- |
| TResult | The type of the result returned by the task. |
| result | The result to store into the completed task. |

## Return Value

The successfully completed task.

## See Also

* class [Task&lt;TResult&gt;](../Task-1.md)
* class [Task](../Task.md)
* namespace [Microsoft.Coyote.Tasks](../Task.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->