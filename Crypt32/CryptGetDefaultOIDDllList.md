## CryptGetDefaultOIDDllList

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetDefaultOIDDllList(
   IntPtr hFuncSet,
   IntPtr pDllList
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetdefaultoiddlllist)