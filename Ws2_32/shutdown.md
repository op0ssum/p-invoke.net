## shutdown

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int shutdown(
   IntPtr s,
   int how
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-shutdown)