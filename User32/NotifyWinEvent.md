## NotifyWinEvent

```
[DllImport("user32.dll", SetLastError = true)]
public static extern void NotifyWinEvent(
   uint eventMin,
   IntPtr hwnd,
   int idObject,
   int idChild
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-notifywinevent)