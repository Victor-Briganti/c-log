# C Logger

A basic log library to be used with C/C++.

### Usage

This library can be used by simpling placing this files into a project.

The function `log_set()` needs to be called to set the log level, if the output will have colors and the file were the output is going to be writted. This function needs to be called only in one placed in the program.

The following functions can be used to log the system:

```C
log_trace("Message %d", 1)
log_debug("Message %d", 1)
log_info("Message %d", 1)
log_warn("Message %d", 1)
log_error("Message %d", 1)
log_fatal("Message %d", 1)
```

### Similar Projects

This library was heavily inspired for: https://github.com/rxi/log.c
