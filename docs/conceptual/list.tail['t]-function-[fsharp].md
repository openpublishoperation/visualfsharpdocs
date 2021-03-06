# List.tail<'T> Function (F#)

Returns the list without the first element.

**Namespace/Module Path:** Microsoft.FSharp.Collections.List

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
List.tail : 'T list -> 'T list

// Usage:
List.tail list


```





#### Parameters
*list*
Type: **'T**[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)



**The tail of the list, that is, the list without the first element.**
## Remarks
This function is named **Tail** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code shows how to use List.tail.**
[!code-fsharp[Main](snippets/fslists/snippet63.fs)]
**Abbreviated Output**
**[2; 3]System.ArgumentException: The input list was empty.**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.List Module &#40;F&#35;&#41;](Collections.List-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

