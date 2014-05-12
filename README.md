# Reddnodes
Reddnodes is currently being developed to estimate the size of the Reddcoin network by finding all the reachable nodes in the network. The current methodology involves sending [getaddr](https://en.bitcoin.it/wiki/Protocol_specification#getaddr) message recursively to find all the reachable nodes in the network starting from a set of seed nodes. Reddnodes uses Reddcoin protocol version 70003, so nodes with older protocol version will be skipped.

## Setup
See [Provisioning Bitcoin Network Crawler](https://github.com/ayeowch/bitnodes/wiki/Provisioning-Bitcoin-Network-Crawler)

## License
Copyright (c) 2014 Addy Yeow Chin Heng &lt;ayeowch@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
