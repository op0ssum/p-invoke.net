## WTSFreeMemory

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern void WTSFreeMemory(
   IntPtr pMemory
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsfreememory)