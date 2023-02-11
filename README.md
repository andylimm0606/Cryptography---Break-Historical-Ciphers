# Cryptography-Break-Historical-Ciphers

Part 1:
Given 1000 hex-encoded strings, one of them being English plaintext that has been XOR'd against a single byte key,
the program decrypts the messeage using self-implemented XOR function and frequency analysis of English plaintext that gives perecent error of characters analyzed. 

Part 2:
Given a file with plaintext that has been XOR'd against a multi-byte key (unknown length) and base64 encoded,
the program decrypts the message by guessing the key length using hamming distance and finds key using frequency analysis, similar to that of part 1. Then it finishes decrpyting using undo-ing single byte XOR & combining. 

Part 3:
Given a file with ASCII-encoded file that has been encrypted using Vigenère cipher,
the program decrypts the message in a similar method to that of part 2, but also looking at the shift of English characters.


Due to academic policy, code cannot be publicly published.
Can be privately forked given notice.

Please contact:
andylimm0606@gmail.com
