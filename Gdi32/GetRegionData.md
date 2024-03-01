## GetRegionData

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetRegionData(
   IntPtr hRgn,
   uint dwCount,
   IntPtr lpRgnData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getregiondata)