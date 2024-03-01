## OleDoAutoConvert

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleDoAutoConvert(
   IStorage pStg,
   out Guid pClsidNew
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-oledoautoconvert)