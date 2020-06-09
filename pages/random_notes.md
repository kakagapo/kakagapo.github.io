
Classification of systems based on behavior on detecting failure:
=================================================================
Fail closed - shutdown on detecting failure
Fail open - keep functioning even on detecting failure

Caching writing policies:
=========================
Write-through - data written to both the cache and the backing store at the same time.
write-around - data is written only to the backing store
Write-back (aka write-behind) - data is written only to the cache. Data is later shipped to the backing store in the background.

Cache coherency protocols:
==========================