# QueryBuilder.Find<'T,'Q> Method (F#)

A query operator that selects the first element selected so far that satisfies a specified condition.

**Namespace/Module Path**: Microsoft.FSharp.Linq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
member this.Find : QuerySource<'T,'Q> * ('T -> bool) -> 'T

// Usage:
queryBuilder.Find (source, predicate)


```





#### Parameters
*source*
Type: [QuerySource](http://msdn.microsoft.com/en-us/library/873589c1-c5dc-47d9-8abf-fee7258dfb00)&lt;'T,'Q&gt;


The input query.


*predicate*
Type: 'T -&gt; [bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


A function that tests each element.



**exceptions tag is not supported!!!!**

## Return Value
The first element for which the Boolean function *predicate* returns **true**.


## Remarks
For more information and examples, see [Query Expressions (F#)](http://msdn.microsoft.com/en-us/library/ff72235c-3ad8-4215-8679-2754484823db).


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Linq.QueryBuilder Class &#40;F&#35;&#41;](Linq.QueryBuilder-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Linq Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Linq-Namespace-%5BFSharp%5D.md)

[Query Expressions (F#)](http://msdn.microsoft.com/en-us/library/ff72235c-3ad8-4215-8679-2754484823db)

