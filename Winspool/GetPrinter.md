## GetPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool GetPrinter(
   IntPtr hPrinter,
   uint Level,
   IntPtr pPrinter,
   uint cbBuf,
   out uint pcbNeeded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-getprintera)