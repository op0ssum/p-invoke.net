## GetFileInformationByHandleEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetFileInformationByHandleEx(
   SafeFileHandle hFile,
   FILE_INFO_BY_HANDLE_CLASS FileInformationClass,
   out FILE_STANDARD_INFO lpFileInformation,
   uint dwBufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfileinformationbyhandleex)