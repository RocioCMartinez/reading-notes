# Bcrypt and Passwords

## [Intro to password hashing](https://auth0.com/blog/hashing-passwords-one-way-road-to-security/)

Define the term “hashing”.

Hashing is a method of encrypting a password.

Explain to a non-technical friend what a hash function does to a password.

It changes up the cleartext(plain text) version to a complicated encrypted version. Making it almost impossible to replicate the original version.

## [bcrypt overview](https://medium.com/@danboterhoven/why-you-should-use-bcrypt-to-hash-passwords-af330100b861)

What does it mean to ‘salt’ a password?

It means to add a long string of bytes to a password. Making it harder to find the original input.

What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?

They would need access to your source code.

## [jBCrypt](https://www.mindrot.org/projects/jBCrypt/)

How does the Blowfish block cipher handle the increased computation speed of new computers?

The algorithm is parametised.

What are the issue with the two most common password hashes for Java (“Java password hash” and “Java password encryption”)?

> *"The top two hits in Google (as of 2006/05/24) for "Java password hash" and "Java password encryption" both offer terrible advice: one uses an unsalted hash which allows reverse dictionary lookup of passwords and the other recommends reversible encryption, which is rarely needed and should only be used as a last resort."*

## Things I want to know more about

I will look into some security breach cases that have occured and possible fixed. There was a lot to this area of learning and it would be helpful to look into real world senarios.
