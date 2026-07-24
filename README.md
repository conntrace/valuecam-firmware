# ValueCam Encrypted Release Host

This public GitHub Pages site contains the ValueCam manual and encrypted
34-mode distribution firmware. It does not contain TREMOR, plaintext firmware,
the release key, or the private C source.

Opening <https://conntrace.github.io/valuecam-firmware/> directly shows the
manual and release number but no install control. The password-protected
Squarespace page uses its private key to decrypt and verify the release in the
browser, then supplies temporary Blob URLs to ESP Web Tools.

`encrypted-release.json` describes the encrypted flash parts.
`ENCRYPTED_SHA256SUMS` verifies the public ciphertext files. The decrypted
firmware and SD recovery image exist only in an authorized browser session.

See `SQUARESPACE.md` for setup and the security boundary.
