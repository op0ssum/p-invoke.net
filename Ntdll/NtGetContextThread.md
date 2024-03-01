## NtGetContextThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtGetContextThread(
   IntPtr hThread,
   ref CONTEXT lpContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/ntddk/nf-ntddk-ntgetcontextthread)