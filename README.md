# performance-https2
Storing various performance test for secured protocol

# Normal HTTPS

**Payload:** `Hello Server! Love, Client.`

**Bytes:** 84 bytes

![classic](https://raw.githubusercontent.com/crimson-med/performance-https2/master/https.png)


# HTTPS2 + Protobuf + Custom Secured Algorithm for Protobuf

**Payload:** `{text: 'Hello Server! Love, Client.', timestamp: + new Date() }`

**Bytes:** 68 bytes

![optimized](https://raw.githubusercontent.com/crimson-med/performance-https2/master/https2%2Bprotobuff-%2Bsecu.png)

# Conclusion

Need to optimize the security protocol. But for now a bigger payload is smaller on the network and not MITM as long ssl is proper.
