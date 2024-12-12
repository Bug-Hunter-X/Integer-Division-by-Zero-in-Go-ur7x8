# Integer Division by Zero in Go

This repository demonstrates a common, yet easily overlooked, error in Go: integer division by zero. The `MyFunc` function attempts to perform a division; however, it does not sufficiently handle the case when the divisor is zero, leading to a runtime panic.

The solution illustrates safe error handling practices to prevent this panic and provide graceful error reporting.