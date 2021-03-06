# AsyncBuilder.For<'T> Method (F#)

Implements the **for** expression in asynchronous computations. Creates an asynchronous computation that enumerates the sequence on demand and runs a function representing the body of a **for** expression for each element.

**Namespace/Module Path:** Microsoft.FSharp.Control

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
member this.For : seq<'T> * ('T -> Async<unit>) -> Async<unit>

// Usage:
asyncBuilder.For (sequence, body)


```





#### Parameters
*sequence*
Type: [seq](http://msdn.microsoft.com/en-us/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'T&gt;**


The sequence to enumerate.


*body*
Type: **'T -&gt;**[Async](http://msdn.microsoft.com/en-us/library/e0b28ea2-dea5-4021-b2b9-d7d4761babde)**&lt;**[unit](http://msdn.microsoft.com/en-us/library/00b837c2-6c8a-483a-87d3-0479c64037a7)**&gt;**


A function to take an item from the sequence and create an asynchronous computation. Can be seen as the body of the **for** expression.



**An asynchronous computation that will enumerate the sequence and run body for each element.**
## Remarks
A cancellation check is performed on each iteration of the loop. The existence of this method permits the use of **for** in the **async { ... }** computation expression syntax.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Control.AsyncBuilder Class &#40;F&#35;&#41;](Control.AsyncBuilder-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Control Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Control-Namespace-%5BFSharp%5D.md)

