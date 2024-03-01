## GetCurrentDirectory

```
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetCurrentDirectory(
   uint nBufferLength,
   StringBuilder lpBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getcurrentdirectory)