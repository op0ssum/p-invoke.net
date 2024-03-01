## GetThemeRect

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeRect(
   IntPtr hTheme,
   int iPartId,
   int iStateId,
   int iPropId,
   ref RECT pRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemerect)