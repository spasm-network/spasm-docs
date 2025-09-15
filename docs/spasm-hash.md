## Spasm hash

#### Spasm hashes

Spasm hashes are prepended with 'spasm', a two-letter identifier of a hash type, and a two-digit identifier of a version of a hash.

#### Spasm ID

For example, here is a hash of a [genesis](https://forum.spasm.network/news/spasmid01192d1f9994bf436f50841459d0a43c0de13ef4aaa5233827bdfe2ea2bc030d6f) message 'not your keys, not your words':

```
spasmid01192d1f9994bf436f50841459d0a43c0de13ef4aaa5233827bdfe2ea2bc030d6f
```

`spasm` - identifies that this is a Spasm hash

`id` - identifies that this is a hash of an event

`01` - identifies a hash version

The Spasm ID of version `01` is a sha256 hash prepended with identifiers.

#### Spasm media hashes

[Video](https://media.spasm.network/spasmvi01f316a39a710c2bef7288a8f8485876c48a87ede8f4f23941d4577c05617101ee.mp4) files are hashed and prepended with `spasmvi01`.

```
spasmvi01f316a39a710c2bef7288a8f8485876c48a87ede8f4f23941d4577c05617101ee
```

[Image](https://media.spasm.network/spasmim01b6b7dc9972c02b70eec2d1ae4a5b95d9b3f0ebb04725d03bfd93664646ca41aa.jpeg) files are hashed and prepended with `spasmim01`.

```
spasmim01b6b7dc9972c02b70eec2d1ae4a5b95d9b3f0ebb04725d03bfd93664646ca41aa
```

Audio files are hashed and prepended with `spasmau01`.

Other files are hashed and prepended with `spasmfl01`.

