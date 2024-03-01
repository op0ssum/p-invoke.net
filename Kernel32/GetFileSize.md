## GetFileSize

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetFileSize(
   SafeFileHandle hFile,
   out uint lpFileSizeHigh
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfilesize)