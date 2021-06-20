# bashbench

`bashbench` is a command line program that benchmarks a Linux system by using
the bash shell.

The benchmark measures both shell and system performance. The program solely
depends on the bash shell which is ubiquitous to nearly all Linux distributions,
making it especially useful for getting a quick glance of system performance on
a newly installed system.

## Usage

```text
NAME
bashbench - benchmark a Linux system using the bash shell

SYNOPSIS
$0 [-c concurrency]

OPTIONS
-c, --concurrency=number The number of concurrent benchmark routines to run.
                         The default is the number of CPUs on the system.

NOTES
A benchmark run will take approximately 30 seconds and uses little memory and
disk space.

The unit of benchmark result "loops/second" is only meaningful for comparison
between Linux systems that have similar software configuration (e.g. similar
bash and Linux kernal versions).
```

## Copyright and License

Copyright (C) 2021 Google Inc. and contributors (Houzuo Howard Guo, etc), all
rights reserved.

This program is free software subject to the terms of European Union Public
License version 1.2. You may find the license text in the LICENSE file.

This is not an officially supported Google product.
