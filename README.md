# HashScanner
Hash Lookup
Hash Lookups
  GET https://api.metadefender.com/v4/hash/{hash}
Parameter
Type
Description
api_key
string
Required. Your API key
hash
string
Required Generated Hash

Get Data Id
  POST https://api.metadefender.com/v4/file
Parameter
Type
Description
api_key
string
Required. Your API key
Content-Type
string
application/octet-stream
file
file
file

Analyze file using Data Id
  GET https://api.metadefender.com/v4/file/{data_id}
Parameter
Type
Description
api_key
string
Required. Your API key
x-file-metadata
string
0
data_id
string
Required.data_id

Flags
Command
Detail
-f, --file
Specify file to be scanned
-k, --key
Unique API token; required
-hash, --hash
specify hash function (md5, sha1, sha256)
-m, -meta
get metadata for scanned file
-n, --name
flag to preserve file name in scan
-p, --p
password for password protected files
-s, --share
allows file scans to be share or not
-w, --workflow
active workflows, allowed values: mcl-metadefender-rest-sanitize-disabled-unarchive
