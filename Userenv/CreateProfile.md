## CreateProfile

```
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool CreateProfile(
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszUserSid,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszUserName,
   [Out] StringBuilder pszProfilePath,
   uint cchProfilePath
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-createprofilew)