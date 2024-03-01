## SHBindToParent

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHBindToParent(
   IntPtr hwnd,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pidl,
   ref IntPtr ppidlLast,
   out IntPtr ppsi,
   ref Guid riid,
   out IntPtr ppv,
   uint dwAttr
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shobjidl_core/nf-shobjidl_core-shbindtoparent)