# WritableSource.CheckFileDeletable Method 
 

Checks if a file can be deleted, but doesn't actually do so. For the purpose of this method, directories do not count as files.

**Namespace:**&nbsp;<a href="ce38c3d6-f720-9c09-02a8-24d191d963ed">LVFS.External</a><br />**Assembly:**&nbsp;LVFS (in LVFS.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

**C#**<br />
``` C#
public abstract NtStatus CheckFileDeletable(
	string path
)
```

**VB**<br />
``` VB
Public MustOverride Function CheckFileDeletable ( 
	path As String
) As NtStatus
```

**C++**<br />
``` C++
public:
virtual NtStatus CheckFileDeletable(
	String^ path
) abstract
```

**F#**<br />
``` F#
abstract CheckFileDeletable : 
        path : string -> NtStatus 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path to the file to check</dd></dl>

#### Return Value
Type: NtStatus<br />Success if the file can be delted. If not, an appropriate error status.

## See Also


#### Reference
<a href="eef32198-3bf0-ea5f-1d5c-ef3cf7488a57">WritableSource Class</a><br /><a href="ce38c3d6-f720-9c09-02a8-24d191d963ed">LVFS.External Namespace</a><br />