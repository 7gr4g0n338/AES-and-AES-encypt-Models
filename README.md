# AES-and-AES-encypt-Models
Demo AES, GCM and CCM algorithms.

## Differences between GCM and CCM
### GCM: authenticated encryption based on ciphertext
Usually encryption and MAC generation can be done in parallel but the chip usually only implements 1 AES set
But GCM has a performance cost of 1 AES and 1 GHASH per block. But GHASH is faster than AES => GCM has higher performance than CCM

### CCM: authenticated encryption based on plaintext
GCM has a performance cost of 2 AES/ 1 block.

![image](https://github.com/user-attachments/assets/bd8cb96d-4da8-48fa-bf61-efd68eb71b83)

![image](https://github.com/user-attachments/assets/67acc6f5-eb70-447a-903a-6a58a4c0209e)

![image](https://github.com/user-attachments/assets/15034049-4052-4688-89d8-d95922df8ce5)
