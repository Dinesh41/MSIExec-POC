Execute below command

```console
candle.exe .\SampleCondition.wxs  
```
```console
light.exe .\SampleCondition.wixobj
```
To Extract
```console
msiexec /a SampleCondition.msi TARGETDIR="PATH" /l*v sample.log
```

To Install
```console
msiexec /i SampleCondition.msi /l*v sample.log
```