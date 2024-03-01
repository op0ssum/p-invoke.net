## NtQuerySystemTime

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void NtQuerySystemTime(
   out LARGE_INTEGER SystemTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-kequerysystemtime)