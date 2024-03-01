## DdeSetQualityOfService

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeSetQualityOfService(
   IntPtr hwndClient,
   ref SECURITY_QUALITY_OF_SERVICE pqosNew,
   ref SECURITY_QUALITY_OF_SERVICE pqosPrev
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddesetqualityofservice)