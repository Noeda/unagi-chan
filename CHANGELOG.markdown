### 0.1.1.0

- support new criterion and GHC 7.8.3
- small performance improvement to boxed unagi

### 0.2.0.0

- implement a bounded variant (See issue #1)
- address issue with stale tickets when running in GHCi

### 0.2.0.1

- conditionally use tryReadMVar (as before) when GHC >= 7.8.3
- set proper CPP flags when running tests
