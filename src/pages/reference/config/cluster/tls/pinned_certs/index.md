# pinned_certs

/ [config](/reference/config/index.md) / [cluster](/reference/config/config/cluster/index.md) / [tls](/reference/config/config/cluster/tls/index.md) 

List of hex-encoded SHA256 of DER-encoded public key fingerprints. When present, during the TLS handshake, the
provided certificate's fingerprint is required to be present in the list, otherwise the connection will be
closed.
