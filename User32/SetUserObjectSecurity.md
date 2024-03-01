## SetUserObjectSecurity

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetUserObjectSecurity(
   IntPtr hObj,
   [In] ref SECURITY_INFORMATION pSIRequested,
   [In] byte[] psd
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setuserobjectsecurity)