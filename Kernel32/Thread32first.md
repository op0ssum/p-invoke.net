## Thread32first

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Thread32First(
   IntPtr hSnapshot,
   ref THREADENTRY32 lpte
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/tlhelp32/nf-tlhelp32-thread32first)