# lunchbox - A basic system-wide TPM management toolkit

Well, maybe.

Anyway:

1) register your sekrit
2) unlock sekrit
3) add new seal for sekrit with new (expected) hashes
4) remove old sealed sekrits
5) export sekrit bundle for tpm on another machine

secrets are stored in a local cryptographic bundles on disk, but locked
with a key that's stored on the tpm

I don't actually know what I'm doing yet in terms of the tpm functionality, so
this document will almost certainly be revised with better descriptions.
