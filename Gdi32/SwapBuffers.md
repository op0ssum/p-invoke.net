## SwapBuffers

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SwapBuffers(
   IntPtr hdc
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-swapbuffers)