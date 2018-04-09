* DLP tables for [she-wasm](https://github.com/herumi/she-wasm/)

# file name

```
she-dlp-<curveType>-<hashBitSize>-<group>.bin
```
* `curveType` : 0 (BN254)
* `hashBitSize` : hash table size
* `group` : g1/g2/gt

# api

## C api
```
mclSize sheLoadTableForGTDLP(const void *buf, mclSize bufSize, mclSize tryNum);
```

## JavaScript api
```
she.loadTableForGTDLP(a) // a is Uint8Array of table
```
