## GlobalLock

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr GlobalLock(
   IntPtr hMem
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globallock)