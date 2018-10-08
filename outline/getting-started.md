The getting started guides start with a tutorial then goes into a very high
level tour of necessary knowledge for being productive with Tokio.

# Pages:

* [Hello world!](#hello-world)
* [The Tokio Runtime and Futures](#futures)
* [Going Further: Streams and Tasks](#further)
* [Example: An Echo Server and Client](#echo)

<a name="hello-world"></a>
## Hello world!

**Status**: [Complete](https://tokio.rs/docs/getting-started/hello-world/)

A "Hello world!" Tokio tutorial. Implement a TCP client that writes "hello world" to
a TCP stream.

<a name="futures"></a>
## The Tokio Runtime and Futures

**Status**: rylev

A high level overview of how and when execution happens in Tokio, how futures
are lazy and the basics of the polling model.

### Contents

* High level Explanation of Tokio's runtime model and how it is significantly different than other languages.
* Explanation that Tokio's futures are lazy. If the future is not spawned, no work will ever be done.
* High level explanation of Tokio's polling model.

<a name="further"></a>
## Going Further: Streams and Tasks

**Status**: rylev

A high level overview of Streams (as the iterator version of futures) and spawning
tasks on the runtime.

### Contents

* High level explanation of Streams.
* Explanation of running tasks on the runtime.

<a name="echo"></a>
## Example: Echo Server and Client

**Status**: rylev

A tutorial showing how to implement an echo server and client.