# y86-debugger: A debugger extension for Y86 assembly language

This debugger extension is specifically designed for [y86-pipe-rs](https://github.com/sshwy/y86-pipe-rs)

## Getting Started

Before debugging, you need to build the debug server by running `cargo build`. You can execute `./target/debug/ydb` for help.

Then open the y86 file you want to debug and set some breakpoints.

Basically you can execute `./target/debug/ydb -p 2345` to start the debug server. You may set different architectures by `--arch` option.

Finally, click the debug icon at the right side of the menu bar to start debugging. The debugger should stop at the entry of your program.

![](images/screenshot.png)