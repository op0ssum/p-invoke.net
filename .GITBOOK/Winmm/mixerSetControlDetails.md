## mixerSetControlDetails

```
[DllImport("winmm.dll", SetLastError = true)]
public static extern uint mixerSetControlDetails(
   IntPtr hmxobj,
   ref MIXERCONTROLDETAILS pmxcd,
   uint fdwDetails
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mmeapi/nf-mmeapi-mixersetcontroldetails)