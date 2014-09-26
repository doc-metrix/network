Network Metrics
===

> Documentation for network performance metrics.


## Metrics


#### [net.bytesRX](http://linux.die.net/man/5/proc)

The total number of bytes received by a network interface.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | [B](https://github.com/doc-metrix/units#b) | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.bytesTX](http://linux.die.net/man/5/proc)

The total number of bytes transmitted by a network interface.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | [B](https://github.com/doc-metrix/units#b) | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.carrierTX](http://linux.die.net/man/5/proc)

The total number of loss-of-carrier-signal events detected by the device driver. If this value is high, especially when it has only been active for a short time, it means the connection is going up and down a lot. This can be caused by problems either on the device, the device on the other end, or a faulty ethernet cable plugged in to the device.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | errors | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.collsTX](http://linux.die.net/man/5/proc)

The number of packet collisions detected when transmitting. Packet collisions occur when multiple devices use a shared resource (such as an ethernet cable) to transmit a packet at the same time. Frequent packet collisions degrade network performance.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | collisions | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.compressedRX](http://linux.die.net/man/5/proc)

Number of compressed packets received by a network interface.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | packets | raw | [count](https://github.com/doc-metrix/data-types#count)



#### [net.compressedTX](http://linux.die.net/man/5/proc)

Number of compressed packets sent by a network interface.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | packets | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.dropRX](http://linux.die.net/man/5/proc)

Number of packets dropped and otherwise not received by a network interface. This means that your system is unable to process incoming packets fast enough, overwhelming its buffer, or there is an issue in your cabling leading to packet loss.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | packets | raw | [count](https://github.com/doc-metrix/data-types#count)



#### [net.dropTX](http://linux.die.net/man/5/proc)

Number of packets dropped by a network interface. This means that your system is unable to process outgoing packets fast enough, overwhelming its buffer.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | packets | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.errsRX](http://linux.die.net/man/5/proc)

Number of malformed packets received by a network interface. Errors are typically caused by bursts of traffic causing overloads, a speed/duplex mismatch with the connecting port on the other end, or a large number of security rules.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | errors | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.errsTX](http://linux.die.net/man/5/proc)

Number of errors detected by a network interface when transmitting. Errors are typically caused by bursts of traffic causing overloads, a speed/duplex mismatch with the connecting port on the other end, or a large number of security rules.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | errors | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.fifoRX](http://linux.die.net/man/5/proc)

The number of receiving queue errors detected by a network interface. This is often caused by receiving more packets than the computer can process, leading to buffer overflows.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | errors | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.fifoTX](http://linux.die.net/man/5/proc)

The number of transmitting queue errors detected by a network interface. This is often caused by trying to send more packets than the network connection can handle, leading to buffer overflows.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | errors | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.frameRX](http://linux.die.net/man/5/proc)

Number of packets received by an interface with framing errors. This is often a physical issue (faulty cables or bad Network Interface Card), though it may be caused by mismatched duplex settings.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | errors | raw | [count](https://github.com/doc-metrix/data-types#count)


#### [net.multicastRX](http://linux.die.net/man/5/proc)

Number of multicast frames received by a network interface.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | frames | raw | [count](https://github.com/doc-metrix/data-types#count)



#### [net.packetsRX](http://linux.die.net/man/5/proc)

Number of packets received by a network interface.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | packets | raw | [count](https://github.com/doc-metrix/data-types#count)



#### [net.packetsTX](http://linux.die.net/man/5/proc)

Number of packets transmitted by a network interface.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | `MAX_UNSIGNED_LONG` | packets | raw | [count](https://github.com/doc-metrix/data-types#count)



#### [net.utilizationRX](http://linux.die.net/man/5/proc)

Percentage of a network interface's maximum bandwidth being used for receiving packets.

Note: The data received is reported in `bytes` while bandwidth is in `megabits per second`, so some conversion is necessary to ensure the units match.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | 1 | [utilization](https://github.com/doc-metrix/units#utilization) | derived | [percentage](https://github.com/doc-metrix/data-types#percentage)


#### [net.utilizationTX](http://linux.die.net/man/5/proc)

Percentage of a network interface's maximum bandwidth being used for transmitting packets.

Note: The data transmitted is reported in `bytes` while bandwidth is in `megabits per second`, so some conversion is necessary to ensure the units match.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | 1 | [utilization](https://github.com/doc-metrix/units#utilization) | derived | [percentage](https://github.com/doc-metrix/data-types#percentage)



#### [net.utilizationRXAverage](http://linux.die.net/man/5/proc)

Average percentage of the maximum bandwidth across all interfaces (except loopback) being used for receiving packets.

Note: The data received is reported in `bytes` while bandwidth is in `megabits per second`, so some conversion is necessary to ensure the units match.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | 1 | [utilization](https://github.com/doc-metrix/units#utilization) | derived | [percentage](https://github.com/doc-metrix/data-types#percentage)



#### [net.utilizationTXAverage](http://linux.die.net/man/5/proc)

Average percentage of the maximum bandwidth across all interfaces (except loopback) being used for transmitting packets.

Note: The data transmitted is reported in `bytes` while bandwidth is in `megabits per second`, so some conversion is necessary to ensure the units match.

Min | Max | Units | Metric Type | Data Type 
:---: | :---: | :---: | ---: | ---: |
0 | 1 | [utilization](https://github.com/doc-metrix/units#utilization) | derived | [percentage](https://github.com/doc-metrix/data-types#percentage)



===
## Contributing

To contribute to this documentation, see the contributing [guide](https://github.com/doc-metrix/contributing). Any updates to the documentation should be tagged.

``` bash
$ git tag -a <major.minor.patch> -m "[UPDATE] version."
$ git push origin <major.minor.patch>
```

Use [semantic versioning](http://semver.org/) (semvar) for communicating versions.

*	Any new metrics should be communicated as `minor` updates.
*	Any corrections/value modifications should be `patches`.
* 	Any documentation restructuring (changing field names, removing fields, etc) should be communicated as a `major` update.


===
## Usage

The documentation is stored as [JSON](http://json.org/), a lightweight data-interchange format. Many languages provide JSON support: [JavaScript](http://www.json.org/js.html), [Python](https://docs.python.org/2/library/json.html), [Go](http://golang.org/pkg/encoding/json/), [PHP](http://php.net/manual/en/book.json.php), [Java](http://json.org/java/), [Haskell](http://hackage.haskell.org/package/json), and [others](http://json.org/).

You are free to use the JSON documentation, as is. Simply copy the file and use accordingly.

For those using package managers to manage dependencies, we provide package manager support, as outlined below.


### Bower

The documentation is registered as a [Bower](http://bower.io) package. Bower provides a straightforward means for managing dependencies.

In order to use Bower, you must first install [Node.js](http://nodejs.org/) and [Git](http://git-scm.com/book/en/Getting-Started-Installing-Git). Once the prerequisites are installed,

``` bash
$ npm install -g bower
```

To [install](http://bower.io/docs/api/#install) the latest documentation,

``` bash
$ bower install doc-metrix-network
```

Bower will place the documentation in a `bower_components/` directory within the current working directory.

To [update](http://bower.io/docs/api/#update) to the latest documentation,

``` bash
$ bower update doc-metrix-network
```


### Utilities

List of utilities using this documentation:

*	[Node.js Module](https://github.com/doc-metrix/network-node)


---
## License

[MIT license](http://opensource.org/licenses/MIT). 


---
## Copyright

Copyright &copy; 2014. NodePrime.
