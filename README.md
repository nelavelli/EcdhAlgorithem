# Ecdh-Algorithem


This is Ecdh Algorithem is used to geneated private and public key.

Here is the process how to use this service.

1. Generate private and public key's using EcdhSingletonService
2. Perfom handshaking with you seucire random number, by passing secure random number and the public key that is generated in the previous step.

3. get the publick key generated by the remote service.
4. Generate shared secret key from the private key and public key that is passed by the remove service.
5. Encrypt your text using the generated shared secret key.
6. pass the encrypted cipher text  to the remote service.
7. ask your remote service to decrypt this using their shared secret key.
8. ask your remote service to iterate from step 4 to step 14.
