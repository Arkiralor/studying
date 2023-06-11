# Inter-Process Communication _(IPC)_

The methods and mechanisms that enable communication between different processes in a computer system.

Processes are separate running programs that are executed independently and can communicate with each other through various IPC techniques. These techniques can be used to transfer data between processes, synchronize their execution, and coordinate their activities.

Examples of IPC mechanisms include

- _message passing_
- _shared memory_
- _pipes and sockets_
- _remote procedure calls (RPC)_
- _distributed file systems_

IPC is a fundamental aspect of modern operating systems and is used extensively in many areas, such as multi-threaded programming, network programming, and distributed computing.

## Basic Comparission

| __IPC Mechanism__ | __Pros__ | __Cons__ |
| --- | --- | --- |
| __Remote Procedure Call (RPC)__ | _Easy to use and understand; enables cross-platform communication; can support multiple languages_ | _Can be slower than other IPC mechanisms; requires serialization and deserialization of data_ |
| __Message Queuing__ | _Enables asynchronous communication between processes; can support high throughput and fault tolerance; can be distributed_ | _Can be more difficult to use than other IPC mechanisms_ |
| __Shared Memory__ | _Provides fast and efficient communication between processes; can be used for high-performance applications_ | _Can lead to race conditions and other synchronization issues_ |
| __Pipes and Sockets__ | _Simple and easy to use; provides communication between processes on the same machine_ | _Limited to communication between processes on the same machine_ |
| __Distributed File Systems__ | _Provides shared access to files across multiple machines; can be used for data processing and storage_ | _Can be more difficult to use than other IPC mechanisms_ |
| __REST APIs__ | _Enables programmatic access to services over the internet; can be used for web and mobile applications_ | _May be slower than other IPC mechanisms; requires serialization and deserialization of data_ |
| __WebSockets__ | _Enables real-time communication between a client and a server over the internet; can be used for chat and gaming applications_ | _Can be more complex to use than REST APIs_ |

## gRPC and REST APIs

By far, the most popular protocols/techniques are: __RPC__ (_via gRPC_) and __REST APIs__.

Here is a _one-to-one_ comparission.

| __Criteria__ | __gRPC__ | __REST API__ |
| --- | --- | --- |
| __Data Format__ | _Uses Protocol Buffers, a binary serialization format._ | _Uses JSON, XML, or other text-based formats._ |
| __Protocol__ | _Uses HTTP/2 protocol._ | _Uses HTTP/1.1 or HTTP/2 protocol._ |
| __Performance__ | _Generally faster and more efficient._ | _May be slower and less efficient._ |
| __Language Support__ | _Supports a wide range of programming languages._ | _Widely used and supports a broad range of programming languages._ |
| __Caching and Security__ | _Limited support for caching._ | _Better support for caching and established security mechanisms._ |
| __Ecosystem__ | _Has a smaller ecosystem but is growing rapidly._ | _Has a more mature ecosystem with many tools and frameworks available._ |
