# Timestamps

[OpenTimestamps](https://opentimestamps.org) proofs for the assets of release `v3`.
Each proof commits to the SHA-256 of the file below.

| file | SHA-256 |
|---|---|
| `abc-valuation-product-5over3-v3.pdf` | `7253db16f67e1875c0f587bccc8a9a579f2fa0e4ba7f864f404032edab7722da` |
| `abc-valuation-product-5over3-v3.tar.gz` | `f30e64d75101d596f1a0414db8cbeac4469de2be9c26f5e7eea801407da0c568` |

To verify, download the release asset into this directory and run

    pip install opentimestamps-client
    ots verify timestamps/<file>.ots
