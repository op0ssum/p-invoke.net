## CertAddCRLLinkToStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CertAddCRLLinkToStore(
   IntPtr hCertStore,
   IntPtr pCrlContext,
   uint dwAddDisposition,
   ref IntPtr ppStoreContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certaddcrllinktostore)