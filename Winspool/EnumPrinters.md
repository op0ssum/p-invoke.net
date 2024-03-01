## EnumPrinters

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool EnumPrinters(
   uint Flags,
   string Name,
   uint Level,
   IntPtr pPrinterEnum,
   uint cbBuf,
   out uint pcbNeeded,
   out uint pcReturned
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-enumprintersa)