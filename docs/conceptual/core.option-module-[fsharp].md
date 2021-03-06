# Core.Option Module (F#)

Basic operations on options.

**Namespace/Module Path:** Microsoft.FSharp.Core

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




module Option


```





## Remarks
For an overview of options in F#, see [Options &#40;F&#35;&#41;](Options-%5BFSharp%5D.md).


## Values


|Value|Description|
|-----|-----------|
|[bind](http://msdn.microsoft.com/en-us/library/c3406192-24ac-49b5-bc3b-8f805187f1c0)<br />**: ('T -&gt; 'U option) -&gt; 'T option -&gt; 'U option**|Invokes a function on an optional value that itself yields an option.|
|[count](http://msdn.microsoft.com/en-us/library/2dac83a9-684e-4d0f-b50e-ff722a8bb876)<br />**: 'T option -&gt; int**|Evaluates the equivalent of [Set.count](http://msdn.microsoft.com/en-us/library/54acc46d-af76-474e-9ff7-bd4bd6b7b4c4) for an option.|
|[exists](http://msdn.microsoft.com/en-us/library/a606d2d4-fddc-4eab-ab37-c6138fb7ad99)<br />**: ('T -&gt; bool) -&gt; 'T option -&gt; bool**|Evaluates the equivalent of [List.exists](http://msdn.microsoft.com/en-us/library/15a3ebd5-98f0-44c0-8220-7dedec3e68a8) for an option.|
|[fold](http://msdn.microsoft.com/en-us/library/af896794-3d53-406c-9411-316cd5c33ad8)<br />**: ('State -&gt; 'T -&gt; 'State) -&gt; 'State -&gt; 'T option -&gt; 'State**|Evaluates the equivalent of [List.fold](http://msdn.microsoft.com/en-us/library/c272779e-bae7-4983-8d7f-16b345bb33a0) for an option.|
|[foldBack](http://msdn.microsoft.com/en-us/library/a882fbaf-c019-46f0-b4f5-b8c2b8b90ffb)<br />**: ('T -&gt; 'State -&gt; 'State) -&gt; 'T option -&gt; 'State -&gt; 'State**|Performs the equivalent of the [List.foldBack](http://msdn.microsoft.com/en-us/library/b9a58e66-efe1-445f-a90c-ac9ffb9d40c7) operation on an option.|
|[forall](http://msdn.microsoft.com/en-us/library/ba884586-5eae-49c5-9e36-05481c1c3428)<br />**: ('T -&gt; bool) -&gt; 'T option -&gt; bool**|Evaluates the equivalent of [List.forall](http://msdn.microsoft.com/en-us/library/e11a5233-d612-40ac-833b-d5cf496900b7) for an option type.|
|[get](http://msdn.microsoft.com/en-us/library/803e9fcb-6edd-4910-808c-25f08cbc55ea)<br />**: 'T option -&gt; 'T**|Gets the value associated with the option.|
|[isNone](http://msdn.microsoft.com/en-us/library/73db6a53-15e7-40a6-94f9-a0049e5f4819)<br />**: 'T option -&gt; bool**|Returns **true** if the option is **None**.|
|[isSome](http://msdn.microsoft.com/en-us/library/41ad0857-5672-4326-84b5-c33dc43dcf79)<br />**: 'T option -&gt; bool**|Returns **true** if the option is not **None**.|
|[iter](http://msdn.microsoft.com/en-us/library/83389eef-3dff-4074-b4cc-f69581c25191)<br />**: ('T -&gt; unit) -&gt; 'T option -&gt; unit**|Executes a function for an option value.|
|[map](http://msdn.microsoft.com/en-us/library/91a20385-7e73-40c2-9adc-635e86d6a622)<br />**: ('T -&gt; 'U) -&gt; 'T option -&gt; 'U option**|Transforms an option value by using a specified mapping function.|
|[toArray](http://msdn.microsoft.com/en-us/library/c8044873-ba17-4b52-8231-eb1a28318c64)<br />**: 'T option -&gt; 'T []**|Convert the option to an array of length 0 or 1.|
|[toList](http://msdn.microsoft.com/en-us/library/5f1af295-9fa9-40ad-b4a1-3578d94d44e1)<br />**: 'T option -&gt; 'T list**|Convert the option to a list of length 0 or 1.|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

