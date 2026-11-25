cat > notes.md << 'EOF'
# Mission 5 Notes

## Task 5.1: Manual conversions

| Question | Working and answer |
|---|---|
| Convert decimal 13 to binary. | 13 ÷ 2 = 6 remainder 1; 6 ÷ 2 = 3 remainder 0; 3 ÷ 2 = 1 remainder 1; 1 ÷ 2 = 0 remainder 1. Reading upwards gives 1101. |
| Convert decimal 25 to binary. | 25 ÷ 2 = 12 remainder 1; 12 ÷ 2 = 6 remainder 0; 6 ÷ 2 = 3 remainder 0; 3 ÷ 2 = 1 remainder 1; 1 ÷ 2 = 0 remainder 1. Reading upwards gives 11001. |
| Convert binary 1010 to decimal. | (1 × 8) + (0 × 4) + (1 × 2) + (0 × 1) = 10. |
| Convert binary 1101 to decimal. | (1 × 8) + (1 × 4) + (0 × 2) + (1 × 1) = 13. |
| Convert hexadecimal A to decimal. | A represents 10 in hexadecimal. Answer: 10. |
| Convert hexadecimal 1F to decimal. | (1 × 16) + (15 × 1) = 16 + 15 = 31. |
| Convert binary 1111 to hexadecimal. | 1111 = 15 in decimal, and 15 is F in hexadecimal. Answer: F. |

## Task 5.2: Python verification

| Expression tested | Result | Does it match manual calculation? |
|---|---|---|
| bin(13) | 0b1101 | Yes |
| bin(25) | 0b11001 | Yes |
| int("1010", 2) | 10 | Yes |
| int("1101", 2) | 13 | Yes |
| hex(13) | 0xd | Yes |
| hex(25) | 0x19 | Yes |
| int("A", 16) | 10 | Yes |
| int("1F", 16) | 31 | Yes |
| hex(int("1111", 2)) | 0xf | Yes |

## Task 5.3: Number converter

| Test no | Binary output | Hexadecimal output |
10 | 0b1010 | 0xa
255 | 0b11111111 | 0xff
42 | 0b101010 | 0x2a

## Task 5.4: How is text stored?

| Character | ASCII decimal code |
|---|---|
| Uppercase A | 65 |
| Lowercase a | 97 |

**Why an encoding standard is needed:** A computer needs a character-encoding standard to convert text characters into numerical values that it can store and process. Encoding standards ensure that text is represented and interpreted consistently across different computers and applications.

**A character not in basic ASCII:** The Euro symbol (€) is not included in basic ASCII. It can be represented using UTF-8 encoding. Other examples are ₹, é and 😀.

**ASCII vs UTF-8**

| Point | ASCII | UTF-8 |
|---|---|---|
| Full form | American Standard Code for Information Interchange | Unicode Transformation Format – 8-bit |
| Characters supported | Basic English letters, numbers and symbols | Characters from many languages, symbols and emojis |
| Storage | Uses 7 bits for standard ASCII characters. | Uses 1–4 bytes per character. |
| Example | A = 65 | A = 65; ₹ can also be represented. |

ASCII is an encoding standard that represents basic English characters using numerical codes. UTF-8 is a more advanced encoding standard that supports characters from many languages, symbols and emojis. UTF-8 is widely used because it supports a much larger range of characters.
