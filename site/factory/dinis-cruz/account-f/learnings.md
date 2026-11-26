# Learnings

- The container has no ssh-keygen by default: run apt-get update, then apt-get install -y openssh-client.
- Git prints "No signature" under --show-signature without an allowed-signers file; check the commit object for gpgsig instead.
