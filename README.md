# ECE428 - MP3

This is our implementation of a distributed file system.
### How to Start
- Clone the repo using `git clone`
- `cd` into the scripts folder
- You can run the server by typing `./start_client.sh`

### Description
This program will create a network of nodes and handle failure detectors. The failure detection will be spread across all nodes in the network quickly and everyone _should_ be updated quickly on the status of the entire network using the gossiping algorithm and membership lists.

This system also implements a distributed file system which can handle up to 2 failures. Replication is done to ensure files are reachable even if nodes fail and we have a group of masters to ensure that coordination can still be done even if master nodes fail.

## Authors
- Rahul Surti
- Shashank Saxena

