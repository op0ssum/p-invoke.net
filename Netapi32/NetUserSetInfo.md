## NetUserSetInfo

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUserSetInfo(
   string ServerName,
   string UserName,
   uint Level,
   IntPtr Buffer,
   out uint ParmError
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netusersetinfo)