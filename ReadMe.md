# COpenCL

Linux Swift module map for OpenCL

### Usage:

Add to application's Package.swift:
```
   ...
   dependencies: [
      // Dependencies declare other packages that this package depends on.
      .package(url: "https://github.com/sdrpa/COpenCL", from: "1.0.0")
   ],
   ...
```

Then:
```
#if os(Linux)
import COpenCL
#else
import OpenCL
#endif
```
