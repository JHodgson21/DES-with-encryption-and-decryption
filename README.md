# DES Encryption & Decryption

This project is an implementation of the Data Encryption Standard (DES), including both encryption and decryption functionality. The DES algorithm is a symmetric key block cipher that encrypts data in blocks of 64 bits using a 56-bit key. This implementation also showcases the permutation tables and substitution (S-boxes) used in the DES algorithm.

## Features

- Initial Permutation (IP) and Final Permutation (IP-1)

- Expansion (E) Table for the F-function

- S-box substitution logic
 
- Permutation (P) Box used in the F-function

- Key schedule for generating subkeys

- Encryption and decryption functions

## Files

- des.py: Contains the main code for encryption and decryption, key generation, and the permutation logic.

## How to Use

### Prerequisites

Python 3.x installed on your system.

## Running the Code

Clone the repository:
```bash
git clone https://github.com/your-username/DES-Algorithm-With-Decryption.git
cd DES-Algorithm-With-Decryption
```

Run the script to see encryption and decryption in action:
```bash
python des.py
```

## Example

The script encrypts and decrypts the provided plaintext using DES. You can modify the plaintext and keys in the `main` section of the code:

- Plaintext: `0123456789ABCDEF`

- Key: `133457799BBCDFF1`

The example also includes encryption and decryption for the text `jakehodgson` represented in hex as `6A616B65686F6467736F6E`.

Output

The script will print the following:

- Original plaintext

- Encrypted ciphertext

- Decrypted plaintext

## Project Structure

- Initial Permutation (IP): Initial rearrangement of the 64-bit input.

- Final Permutation (IP-1): Inverse permutation applied after all rounds.

- S-boxes: Perform non-linear substitution to improve security.

- P-box: Permutes the output of the S-boxes to further mix the bits.

- Key Scheduling: Uses key permutation and left shifts to generate subkeys.

## Learning Objectives

This project helps in understanding:

- The step-by-step process of DES encryption and decryption.

- How permutations, expansions, and substitutions are performed.

- The role of key scheduling in generating subkeys for each round.

## References

- Wikipedia - Data Encryption Standard


## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the implementation.

## Contact

Created by Jake Hodgson. If you have any questions or feedback, feel free to reach out!
