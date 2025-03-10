# gdb

> The GNU Debugger.
> More information: <https://www.gnu.org/software/gdb>.

- Debug an executable:

`gdb {{executable}}`

- Attach a process to gdb:

`gdb -p {{procID}}`

- Debug with a core file:

`gdb -c {{core}} {{executable}}`

- Execute given GDB commands upon start:

`gdb -ex "{{commands}}" {{executable}}`

- Start `gdb` and pass arguments to the executable:

`gdb --args {{executable}} {{argument1}} {{argument2}}`

- Skip debuginfod and pagination prompts and then print the backtrace:

`gdb -c {{core}} {{executable}} -iex 'set debuginfod enabled on' -iex 'set pagination off' -ex bt`
