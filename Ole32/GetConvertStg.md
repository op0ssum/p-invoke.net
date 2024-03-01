## GetConvertStg

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int GetConvertStg(
   IntPtr pbc,
   uint ef,
   IntPtr qfsout,
   uint pclsid,
   uint clsid,
   IntPtr pstg,
   ref uint lpflags,
   out IStorage ppstg
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-getconvertstg)