# SWSharpProxy
Summoners War Data Extractor in C#

Initial solution is just a console app reading a base64 dummy string in /SWSharpProxy/Program.cs

## Activities:
1. Understanding key generation
2. Fix AES Decrypter
  * Test base64 decode.
  * Create an encrypter using key, 
  * then decrypt the encrypted message.
3. Build Proxy functionality
  * An alternative is use Fiddler for response capture, then take the body and use it as the dummy string.
  
Thanks to [kakaroto](https://github.com/kakaroto/SWProxy) and [crayontxx](https://github.com/crayontxx/SWProxy-GO)
