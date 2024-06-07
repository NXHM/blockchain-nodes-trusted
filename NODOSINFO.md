# Nodos
Son los nodos que componen la red blockchains, solo unos especificos se han unido. Similar a permisionada
1. Primer nodo
``` shell
  nicolas@DESKTOP-OQLS8GH:~/projects/tesis-polkadot/substrate-node-template$ ./target/release/node-template key generate-scheme Sr25519 --password-interactive
  Key password:
  Secret phrase:       satoshi case seek protect story useful clock they caught keen opera drip
    Network ID:        substrate
    Secret seed:       0xd67e810fe7685b1a8c38f1781b483e40db2bb8d5ae77333c2ad596e0cce37137
    Public key (hex):  0xe6675742a90b3dc4188158264b8eac33d525443329553f319e62ae4b336f5369
    Account ID:        0xe6675742a90b3dc4188158264b8eac33d525443329553f319e62ae4b336f5369
    Public key (SS58): 5HGoZyM3WALEQDhFAweUj7M2r5g16AJ7zKCvTE9sY64CkKVf
    SS58 Address:      5HGoZyM3WALEQDhFAweUj7M2r5g16AJ7zKCvTE9sY64CkKVf
```

2. Segundo nodo
```shell
nicolas@DESKTOP-OQLS8GH:~/projects/tesis-polkadot/substrate-node-template$ ./target/release/node-template key inspect --password-interactive --scheme Ed25519 "satoshi case seek protect story useful clock they caught keen opera drip"
  Key password:
  Secret phrase:       satoshi case seek protect story useful clock they caught keen opera drip
    Network ID:        substrate
    Secret seed:       0xd67e810fe7685b1a8c38f1781b483e40db2bb8d5ae77333c2ad596e0cce37137
    Public key (hex):  0x18d6870613ae85b0090b996d716047ae8a3b0bda463f28aa872283a1291482ae
    Account ID:        0x18d6870613ae85b0090b996d716047ae8a3b0bda463f28aa872283a1291482ae
    Public key (SS58): 5CdGjYcnyyxLM1PpY4dnwZiQDcYaEPnYWGDBEoMA6EacPU5L
    SS58 Address:      5CdGjYcnyyxLM1PpY4dnwZiQDcYaEPnYWGDBEoMA6EacPU5L
```

3. Tercer Nodo
```shell
  nicolas@DESKTOP-OQLS8GH:~/projects/tesis-polkadot/substrate-node-template$ ./target/release/node-template key generate --scheme Sr25519 --password-interactive
  Key password:
  Secret phrase:       display liberty make afraid afford promote pulp flip consider huge cycle mirror
    Network ID:        substrate
    Secret seed:       0xd61489a8db8df389b7656eb349ababdd3d1b780d09ef9dd7fb26af5af4834e5e
    Public key (hex):  0x249271ec3f93b83aad76a8f5f1966b2627c89e63e38697f24b8b6b8c09b1144b
    Account ID:        0x249271ec3f93b83aad76a8f5f1966b2627c89e63e38697f24b8b6b8c09b1144b
    Public key (SS58): 5Ctf5qikajeH3zdrrSKruXxM5jzZj4ARxQy3Ggwdru2EpEyE
    SS58 Address:      5Ctf5qikajeH3zdrrSKruXxM5jzZj4ARxQy3Ggwdru2EpEyE
```

4. Cuarto Nodo
``` shell
  nicolas@DESKTOP-OQLS8GH:~/projects/tesis-polkadot/substrate-node-template$ ./target/release/node-template key inspect --password-interactive --scheme Ed25519 "display liberty make afraid afford promote pulp flip consider huge cycle mirror"
  Key password:
  Secret phrase:       display liberty make afraid afford promote pulp flip consider huge cycle mirror
    Network ID:        substrate
    Secret seed:       0xd61489a8db8df389b7656eb349ababdd3d1b780d09ef9dd7fb26af5af4834e5e
    Public key (hex):  0xf9e9aec5241e31237f8525312d64be551c106e2bf2cdc191815814cf98bd5042
    Account ID:        0xf9e9aec5241e31237f8525312d64be551c106e2bf2cdc191815814cf98bd5042
    Public key (SS58): 5HiPCUipdyeipQXRAw9uwombFmYv2pXhcVPf9Pga97PahrrZ
    SS58 Address:      5HiPCUipdyeipQXRAw9uwombFmYv2pXhcVPf9Pga97PahrrZ
```