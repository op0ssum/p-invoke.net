## SetPixelV

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetPixelV(
   IntPtr hdc,
   int x,
   int y,
   int crColor
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setpixelv)