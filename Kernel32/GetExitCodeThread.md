## GetExitCodeThread

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetExitCodeThread(
   IntPtr hThread,
   out uint lpExitCode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getexitcodethread)