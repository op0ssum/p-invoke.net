## GetThemeSysFont

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern HRESULT GetThemeSysFont(
   IntPtr hTheme,
   int iFontId,
   out LOGFONT pFont
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-getthemesysfont)