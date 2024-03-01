## PolylineTo

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PolylineTo(
   IntPtr hdc,
   [In] POINT[] lppt,
   uint cCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polylineto)