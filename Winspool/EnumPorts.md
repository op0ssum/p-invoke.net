## EnumPorts

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool EnumPorts(
   string pName,
   uint Level,
   IntPtr pPort,
   uint cbBuf,
   out uint pcbNeeded,
   out uint pcReturned
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-enenumerateportsa)