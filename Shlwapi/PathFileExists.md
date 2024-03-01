## PathFileExists

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathFileExists(
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszPath
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathfileexistsw)