# LeNa Decryption Script

Simple decryption script for the LeNa.b/.c variants.

Designed for use on the elf binary that LeNa drops, it works by decrypting the
encrypted string and dropping the decrypted bytes as a comment where ever the
string's pointer is used.

The decryption is really easy (a MVNS), basically a xor to 0xFF

Timothy Strazzere <Tim.Strazzere@mylookout.com>
March 2012

