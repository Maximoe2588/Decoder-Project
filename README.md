# Decoder

# Decoding Applications

Welcome to the Decoding Applications project! This project contains three different decoding applications - Caesar Shift, Polybius Square, and Substitution Cipher. These applications are designed to provide users with various options to encode and decode messages in a secure and efficient manner.

# Caesar Shift

The Caesar Shift application allows users to encode messages by shifting the position of each character in the message by a specified number of places. The encoded message can be decoded by applying the same shift in the opposite direction. The tests for the Caesar Shift application ensure that the following conditions are met:

It returns false if the shift value is equal to 0, less than -25, greater than 25, or not present.
It ignores capital letters.
It handles shifts that go past the end of the alphabet.
It maintains spaces and other non-alphabetic symbols in the message, before and after encoding or decoding.

# Polybius Square

The Polybius Square application allows users to encode messages by converting each letter in the message to a combination of two numbers, based on a 5x5 square. The encoded message can be decoded by converting the numbers back to letters. The tests for the Polybius Square application ensure that the following conditions are met:

When encoding, it translates the letters i and j to 42.
When decoding, it translates 42 to (i/j).
It ignores capital letters.
It maintains spaces in the message, before and after encoding or decoding.

# Substitution Cipher

The Substitution Cipher application allows users to encode messages by substituting each letter in the message with a different letter, according to a given alphabet. The encoded message can be decoded by reversing the substitution process. The tests for the Substitution Cipher application ensure that the following conditions are met:

It returns false if the given alphabet isn't exactly 26 characters long.
It correctly translates the given phrase, based on the alphabet given to the function.
It returns false if there are any duplicate characters in the given alphabet.
It maintains spaces in the message, before and after encoding or decoding.
It ignores capital letters.

# Conclusion

If you have any questions or suggestions, please feel free to open an issue on our Github repository. We are always looking for ways to improve these applications and make them a better experience for all users.
