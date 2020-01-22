# Description
`ksed` = Kubernetes secret encrypt/decrypt

This script can be used in your pipeline to convert the secret file in plain text to a ecrypted one.
Or you can use it as standalone! 

`PS.: When the script runs to encrypt the file it generates a backup file to preservate your original.`

# Encrypt file
`ksed -e /path/to/your/file/in/plain/text`

# Decrypt file
`ksed -d /path/to/your/file/in/plain/text`

# Encrypt hash
`ksed -e stringToEncrypt`

For help use `ksed -h`
