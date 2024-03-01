## MessageBoxIndirect

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int MessageBoxIndirect(
   ref MSGBOXPARAMS lpmbp
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-messageboxindirectw)