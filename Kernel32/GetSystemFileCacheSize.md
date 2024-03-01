## GetSystemFileCacheSize

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetSystemFileCacheSize(
   out uint lpMinimumFileCacheSize,
   out uint lpMaximumFileCacheSize,
   out uint lpFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemfilecachesize)