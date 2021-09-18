# Quantum Hasher

A simple hasher for generating normal or truly random hashes using Qubits.

# Usage

import the LyriHash class and use the functions defined within it.

# NormalHasher
* Usage: LyriHash().NormalHash({word}, {length of hash})
* Stores key:value pairs of the generated hashes, key as the word and value as the hash in a txt file.  

# CheckPassword
* Usage: LyriHash().CheckPassword({Hash of the password as a string})
* Scans the hashes file for a match, returns "valid password" along with the key:value pair if a match is found.

# BIP32_seed_phrase_gen
* Usage: LyriHash().BIP32_seed_phrase_gen({length of the phrase})
* Stores the generated BIP32 seed phrase in a txt file.

# CheckPhrase
* Usage: LyriHash().CheckPhrase({Phrase})
* Scans the phrases file for a match, returns "Phrase exists in the phrases file." if a match is found.

# QuantumHash
* Usage: LyriHash().QuantumHash({word}, {length of hash})
* Uses qubits to generate a truly random hash and stores the key:value pair of the hash in a txt file.