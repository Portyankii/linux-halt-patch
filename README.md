# linux-halt-patch
adds a new system call that invokes the "hlt" instruction

requires a hard reset once invoked becuase CPU halted (duh)

# how to invoke
simply call the halt_system syscall, which is number 666
