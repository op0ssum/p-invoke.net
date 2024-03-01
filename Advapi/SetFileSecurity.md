## SetFileSecurity

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetFileSecurity(
   string lpFileName,
   uint SecurityInformation,
   [In] byte[] pSecurityDescriptor
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setfilesecuritya)