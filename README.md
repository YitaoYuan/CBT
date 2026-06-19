# CBT: Efficient Batch Processing for Concurrent Operations on Shared In-Memory Tree-Based Key-Value Stores

CBT is short for Concurrent Batching Tree.

## Compilation

All files have already been compiled.

If there is a `compile.sh` file in the directory, run it directly.

If not, simply run `make`.

## Running

For `KV_multithread_loadbalance`, use:

`./selftest <NTHREADS> <NBATCH>` Recommended: `NBATCH=12`

For `mica`, use:

`./run.sh <NTHREADS>`

For the others, use:

`./selftest <NBATCH>` Recommended: `NBATCH=8`

and

`./mttest <NTHREADS> <NBATCH>`
