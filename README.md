# android app Signature acquisition tool

# Obtain signature Methods
sed '1d;$d' certificate.pem | base64 --decode | md5sum
