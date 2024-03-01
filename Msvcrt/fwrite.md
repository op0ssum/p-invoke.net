## fwrite

```
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, SetLastError = true)]
public static extern size_t fwrite(
   IntPtr ptr,
   size_t size,
   size_t count,
   IntPtr stream
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/cpp/c-runtime-library/reference/fwrite)