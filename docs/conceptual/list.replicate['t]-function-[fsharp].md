# List.replicate<'T> Function (F#)

Creates a list of a specified length with every element set to the given value.

**Namespace/Module Path:** Microsoft.FSharp.Collections.List

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
List.replicate : int -> 'T -> 'T list

// Usage:
List.replicate count initial


```





#### Parameters
*count*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)


The number of elements to replicate.


*initial*
Type: **'T**


The value to replicate



**The generated list.**
## Remarks
This function is named **Replicate** in compiled assemblies. If you are accessing the function from a .NET language other than F#, or through reflection, use this name.

**The following code shows how to use List.replicate.**
[!code-fsharp[Main](snippets/fslists/snippet52.fs)]
**Output**
**["test"; "test"; "test"; "test"]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.List Module &#40;F&#35;&#41;](Collections.List-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

