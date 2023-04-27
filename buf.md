### Firehose Service

Protobuf definitions for consuming StreamingFast Firehose stream of blocks.

A stream request to receive Firehose blocks can be done using [sf.firehose.v2.Stream.Blocks](https://buf.build/streamingfast/firehose/docs/main:sf.firehose.v2#sf.firehose.v2.Stream.Blocks).

A RPC request to receive a single Firehose block can be done using [sf.firehose.v2.Fetch.Block](https://buf.build/streamingfast/firehose/docs/main:sf.firehose.v2#sf.firehose.v2.Fetch.Block).

The [Response](https://buf.build/streamingfast/firehose/docs/main:sf.firehose.v2#sf.firehose.v2.Response) object contains a block response of type `google.protobuf.Any`, the type returned depends on the endpoint you reach, there is a chain specific Protobuf Block.

Here a list of links to currently supported chain Protobuf definitions (more may be available):
- [Ethereum](https://github.com/streamingfast/firehose-ethereum/blob/develop/proto/sf/ethereum/type/v2/type.proto) <small>Englobe Ethereum, BSC, Polygon and other Ethereum forks</small>
- [NEAR](https://github.com/streamingfast/firehose-near/blob/develop/proto/sf/near/type/v1/type.proto)
- [Solana](https://github.com/streamingfast/firehose-solana/blob/develop/proto/sf/solana/type/v1/type.proto)
- [Arweave](https://github.com/streamingfast/firehose-arweave/blob/develop/proto/sf/arweave/type/v1/type.proto)
- [Antelope](https://github.com/pinax-network/firehose-antelope/blob/develop/proto/sf/antelope/type/v1/type.proto)

Useful links:
- Documentation: [https://firehose.streamingfast.io/](https://firehose.streamingfast.io/)
- Source: [https://github.com/streamingfast/firehose](https://github.com/streamingfast/firehose)