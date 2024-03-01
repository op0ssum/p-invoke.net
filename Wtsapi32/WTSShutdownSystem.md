## WTSShutdownSystem

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSShutdownSystem(
   IntPtr hServer,
   int ShutdownFlag
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsshutdownsystem)