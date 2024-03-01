## SetWindowsHookExA

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr SetWindowsHookExA(
   int idHook,
   HookProc lpfn,
   IntPtr hmod,
   uint dwThreadId
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowshookexw)