⭐In Node.js, streams are an essential concept used to handle asynchronous data flows, particularly when dealing with large amounts of data. 
They allow data to be processed piece-by-piece (in chunks) instead of waiting for the entire data to be available.
This makes streams efficient for tasks like reading files, network operations, or any operation where large data sets are involved.

<h1>🔑Key Characteristics of Streams:</h1>

<pre>Asynchronous:
Streams process data asynchronously, enabling non-blocking I/O operations.

Chunk-Based:
Data is divided into manageable chunks for processing, rather than requiring the entire data to be loaded into memory.

Event-Driven:
Streams rely on events like data, end, error, and finish to signal changes or actions in the data flow.


<h1>🧮Types of Streams in Node.js:</h1>
Readable Streams: For reading data (e.g., reading files, receiving HTTP requests).
Examples: fs.createReadStream, http.IncomingMessage

Writable Streams: For writing data (e.g., writing files, sending HTTP responses).
Examples: fs.createWriteStream, http.ServerResponse

Duplex Streams: For both reading and writing data (e.g., sockets).
Example: net.Socket

Transform Streams: A special type of Duplex Stream that can modify or transform data while reading and writing.
Example: zlib.createGzip</pre>
