# List.filter<'T> Function (F#)

Returns a new collection containing only the elements of the collection for which the given predicate returns **true**.

**Namespace/Module Path**: Microsoft.FSharp.Collections.List

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
List.filter : ('T -> bool) -> 'T list -> 'T list

// Usage:
List.filter predicate list


```





#### Parameters
*predicate*
Type: **'T -&gt;**[bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


The function to test the input elements.


*list*
Type: **'T**[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)


The input list.



**A list containing only the elements that satisfy the predicate.**
## Remarks
This function is named **Filter** in compiled assembly. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following example demonstrates the use of List.filter.**
[!code-fsharp[Main](snippets/fslists/snippet24.fs)]
**The resulting list is [2; 4; 6].****The following example shows another typical use for List.filter.**
[!code-fsharp[Main](snippets/fssamples101/snippet3007.fs)]
**Animals with short names: [("Cats", 4); ("Dogs", 5); ("Mice", 3)]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.List Module &#40;F&#35;&#41;](Collections.List-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

