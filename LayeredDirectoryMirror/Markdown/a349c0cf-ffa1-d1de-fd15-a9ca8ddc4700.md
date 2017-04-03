# SimpleOneWayContentMirror.CheckDirectoryDeletable Method 
 

Checks if a directory can be deleted, but doesn't actually do so. Must not return a success result if the directory is non-empty.

**Namespace:**&nbsp;<a href="d6b0b765-6849-cc2a-e275-85cc710ffc2c">LayeredDirectoryMirror.OneWay</a><br />**Assembly:**&nbsp;LayeredDirectoryMirror (in LayeredDirectoryMirror.exe) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public override NtStatus CheckDirectoryDeletable(
	string path
)
```

**VB**<br />
``` VB
Public Overrides Function CheckDirectoryDeletable ( 
	path As String
) As NtStatus
```

**C++**<br />
``` C++
public:
virtual NtStatus CheckDirectoryDeletable(
	String^ path
) override
```

**F#**<br />
``` F#
abstract CheckDirectoryDeletable : 
        path : string -> NtStatus 
override CheckDirectoryDeletable : 
        path : string -> NtStatus 
```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path to the directory to check</dd></dl>

#### Return Value
Type: NtStatus<br />Success if the directory can be deleted. If not, an appropriate status message to explain why.

## See Also


#### Reference
<a href="907d05b7-f0cb-9f1f-5ebf-526ad7f4853d">SimpleOneWayContentMirror Class</a><br /><a href="d6b0b765-6849-cc2a-e275-85cc710ffc2c">LayeredDirectoryMirror.OneWay Namespace</a><br />