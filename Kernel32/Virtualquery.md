## Virtualquery

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint VirtualQuery(
   IntPtr lpAddress,
   ref MEMORY_BASIC_INFORMATION lpBuffer,
   UIntPtr dwLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualquery)