# Set.IsSupersetOf<'T> Method (F#)

Evaluates to **true** if all elements of the second set are in the first.

**Namespace/Module Path:** Microsoft.FSharp.Collections

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
member this.IsSupersetOf : Set<'T> -> bool (requires comparison)

// Usage:
set.IsSupersetOf (otherSet)


```





#### Parameters
*otherSet*
Type: [Set](http://msdn.microsoft.com/en-us/library/50cebdce-0cd7-4c5c-8ebc-f3a9e90b38d8)**&lt;'T&gt;**


The set to test against.



**true if this set is a superset of otherSet.**
## Remarks
**The following code illustrates the use of the IsSupersetOf method.**
[!code-fsharp[Main](snippets/fssets/snippet12.fs)]
**Output**
**set [1; 2; 3; 4; 5; 6; 7; 8; 9] is a superset of set [1; 2; 3; 4; 5; 6]: trueset [1; 2; 3; 4; 5; 6] is a superset of set [1; 2; 3; 4; 5; 6]: trueset [5; 6; 7; 8; 9; 10] is a superset of set [1; 2; 3; 4; 5; 6]: false**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Set&#60;'T&#62; Class &#40;F&#35;&#41;](Collections.Set%5B%27T%5D-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

