## SetupUninstallOEMInf

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupUninstallOEMInf(
   string InfFileName,
   uint Flags,
   IntPtr Reserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupuninstalloeminfw)