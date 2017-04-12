# ReadOnlyDirectoryMirror.HasDirectory Method 
 

Gets whether or not this source or a predecessor controls the specified directory.

**Namespace:**&nbsp;<a href="8e43a026-b829-c5d6-efc2-1a8c2a152363">LayeredDirectoryMirror.DirectoryMirror</a><br />**Assembly:**&nbsp;LayeredDirectoryMirror (in LayeredDirectoryMirror.exe) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public override bool HasDirectory(
	string path
)
```

**VB**<br />
``` VB
Public Overrides Function HasDirectory ( 
	path As String
) As Boolean
```

**C++**<br />
``` C++
public:
virtual bool HasDirectory(
	String^ path
) override
```

**F#**<br />
``` F#
abstract HasDirectory : 
        path : string -> bool 
override HasDirectory : 
        path : string -> bool 
```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The directory path being queried</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />Whether or not this source or a predecessor controls the specified directory.

## See Also


#### Reference
<a href="9d919184-3b4b-39ec-0b51-c454c9692d1b">ReadOnlyDirectoryMirror Class</a><br /><a href="8e43a026-b829-c5d6-efc2-1a8c2a152363">LayeredDirectoryMirror.DirectoryMirror Namespace</a><br />