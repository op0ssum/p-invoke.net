## MsiGetTargetPath

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetTargetPath(
   [MarshalAs(
   UnmanagedType.LPTStr)] string szProduct,
   [MarshalAs(
   UnmanagedType.LPTStr)] string szFeature,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder szPathBuf,
   ref int pcchBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigettargetpathw)