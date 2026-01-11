# System Informer Build Tool

<img width="1129" height="821" alt="image" src="https://github.com/user-attachments/assets/9db95b45-7de7-4c57-b8be-34acb9482cd5" />

在上图中，将

```csharp
Debug = Build32bit | Build64bit | BuildArm64bit | BuildDebug | BuildApi | BuildVerbose,
Release = Build32bit | Build64bit | BuildArm64bit | BuildRelease | BuildApi | BuildVerbose,
All = Build32bit | Build64bit | BuildArm64bit | BuildDebug | BuildRelease | BuildApi | BuildVerbose,
```

改为

```csharp
Debug = Build32bit | Build64bit | BuildDebug | BuildApi | BuildVerbose,
Release = Build32bit | Build64bit | BuildRelease | BuildApi | BuildVerbose,
All = Build32bit | Build64bit | BuildRelease | BuildApi | BuildVerbose,
```
