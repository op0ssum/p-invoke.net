## GetShortPathName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetShortPathName(
   string lpszLongPath,
   StringBuilder lpszShortPath,
   uint cchBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getshortpathnamew)