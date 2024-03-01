## GetDiskFreeSpaceEx

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool GetDiskFreeSpaceEx(
   string lpDirectoryName,
   out ulong lpFreeBytesAvailableToCaller,
   out ulong lpTotalNumberOfBytes,
   out ulong lpTotalNumberOfFreeBytes
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getdiskfreespaceexa)