# Verify an official release

Download the release's `SHA256SUMS.txt`, `SHA256SUMS.txt.sig`, and the files listed in the checksum manifest.
Use the [public key](../release/keys/PeCOS2k5-release.pub) and
[allowed signers](../release/keys/allowed_signers) in this repository.
The public Ed25519 release key fingerprint is `SHA256:wNrD0/sbgby3LJt8/5cvUYXQk3zSxoXnVZJGNaWioac`.

The verification helper is available from the [1.0.1 release](https://github.com/PeCOS2k5/Gothic3VR-Releases/releases/tag/v1.0.1).
With Windows OpenSSH and Python 3.10 or later, keep the original filenames and run:

```powershell
ssh-keygen -lf .\PeCOS2k5-release.pub
python .\Sign-Release.py verify .\SHA256SUMS.txt --allowed-signers .\allowed_signers
```

The release signature authenticates the checksum manifest and is separate from Windows Authenticode.
