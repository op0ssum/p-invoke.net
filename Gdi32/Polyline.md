## Polyline

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool Polyline(
   IntPtr hdc,
   [In] POINT[] apt,
   int cpt
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polyline)