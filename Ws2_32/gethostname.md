## gethostname

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int gethostname(
   byte[] name,
   int namelen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-gethostname)