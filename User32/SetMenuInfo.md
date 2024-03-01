## SetMenuInfo

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetMenuInfo(
   IntPtr hMenu,
   ref MENUINFO lpcmi
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setmenuinfo)