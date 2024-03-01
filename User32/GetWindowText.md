## GetWindowText

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int GetWindowText(
   IntPtr hWnd,
   [Out] StringBuilder lpString,
   int nMaxCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getwindowtext)