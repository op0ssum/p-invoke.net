## RtlInitializeSid

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlInitializeSid(
   out SID Sid,
   ref SID_IDENTIFIER_AUTHORITY IdentifierAuthority,
   byte SubAuthorityCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-rtlinitializesid)