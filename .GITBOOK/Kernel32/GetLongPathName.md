## GetLongPathName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetLongPathName(
   string lpszShortPath,
   StringBuilder lpszLongPath,
   uint cchBuffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getlongpathnamew)