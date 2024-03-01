## ExtractIconEx

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern uint ExtractIconEx(
   string lpszFile,
   int nIconIndex,
   IntPtr[] phiconLarge,
   IntPtr[] phiconSmall,
   uint nIcons
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-extracticonex)