## PFXExportCertStore2

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool PFXExportCertStore2(
   IntPtr hStore,
   ref CRYPT_DATA_BLOB pPFX,
   string szPassword,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-pfxexportcertstore2)