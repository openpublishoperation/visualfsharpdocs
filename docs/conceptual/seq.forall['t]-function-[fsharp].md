# Seq.forall<'T> Function (F#)

Tests if all elements of the sequence satisfy the given predicate.

**Namespace/Module Path**: Microsoft.FSharp.Collections.Seq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
Seq.forall : ('T -> bool) -> seq<'T> -> bool

// Usage:
Seq.forall predicate source


```





#### Parameters
*predicate*
Type: **'T -&gt;**[bool](http://msdn.microsoft.com/en-us/library/89c0cf9c-49ce-4207-a3be-555851a67dd5)


A function to test an element of the input sequence.


*source*
Type: [seq](http://msdn.microsoft.com/en-us/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'T&gt;**


The input sequence.



**exceptions tag is not supported!!!!**
**The predicate is applied to the elements of the input sequence. If any application returns false then the overall result is false and no further elements are tested. Otherwise, returns true.**
## Remarks
This function is named **ForAll** in compiled assemblies. If you are accessing the function from a .NET language other than F#, or through reflection, use this name.

**The following code shows how to use Seq.forall.**
[!code-fsharp[Main](snippets/fssequences/snippet39.fs)]
**Output**
**false**
**true**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Seq Module &#40;F&#35;&#41;](Collections.Seq-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections-Namespace-%5BFSharp%5D.md)

