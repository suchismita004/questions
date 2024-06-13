# questions_rtCamp
### How can you validate your email?
- **Email validation** can be done using regular expressions (regex) to ensure the format is correct and by sending a confirmation email with a verification link.

### Hashing and Encryption
- **Hashing**: Converts data into a fixed-size string of characters, which is typically a digest that cannot be reversed.
- **Encryption**: Transforms data into a different format, protecting it from unauthorized access, and can be decrypted back to the original data.

### Differentiate between Hashing and Encryption
- **Hashing**: One-way process, used for data integrity checks. Example: SHA-256.
- **Encryption**: Two-way process, used for data confidentiality. Example: AES (symmetric), RSA (asymmetric).

### Symmetric and Asymmetric Algorithms
- **Symmetric Algorithms**: Same key for encryption and decryption. Faster. Example: AES.
- **Asymmetric Algorithms**: Different keys for encryption (public key) and decryption (private key). More secure. Example: RSA.

### Which is faster, React or JS?
- **JavaScript (JS)** is the base language and can be faster for small tasks.
- **React** is a library built on JS and is optimized for building and updating user interfaces efficiently, but adds overhead compared to vanilla JS.

### How Git Init Actually Works
- **Git Init**: Creates a new Git repository by initializing a .git directory in the specified folder, setting up the necessary structure for version control.

### Indexing, Session, and Cookies
- **Indexing**: Technique used by databases to improve query performance.
- **Session**: Server-side storage of user data to persist state across requests.
- **Cookies**: Client-side storage of user data, sent with each HTTP request to the server.

### What if they disabled Encryption
- **Disabling Encryption**: Would expose data to potential interception and unauthorized access, compromising confidentiality and security.

### Hashing and Types
- **Hashing**: Process of converting data into a fixed-size hash value. Types include MD5, SHA-1, SHA-256, and SHA-3.

These summaries provide a quick overview of the concepts and their differences.



### Git vs GitHub
#### Can we use GitHub without Git?
- **No**, GitHub is designed to work with Git, the version control system. While you can browse repositories on GitHub and download files, to fully utilize GitHub’s features like cloning, pushing, and pulling, you need Git.

### Decryption and Encryption
- **Encryption**: The process of converting plaintext into ciphertext to protect data.
- **Decryption**: The process of converting ciphertext back into plaintext using a key.

### Which technique is used in WhatsApp, encryption or hashing, and why?
- **Encryption**: WhatsApp uses end-to-end encryption (E2EE) to ensure that only the communicating users can read the messages. This protects the confidentiality of the messages from being accessed by unauthorized parties.

### Salt, Cookies vs Session
- **Salt**: Random data added to passwords before hashing to ensure unique hash outputs.
- **Cookies**: Small pieces of data stored on the client-side and sent with HTTP requests to maintain state.
- **Session**: Server-side storage of user data to persist state across multiple requests.

### Can we use Session without Cookies?
- **Yes**, sessions can be managed without cookies by embedding session identifiers in URLs or hidden form fields, though this is less common and can have security and usability issues.
