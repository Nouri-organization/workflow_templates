# test_workflow:
## Notes:
- tensorflow not spurted with python version 3.12

- `arch: [arm64, amd64]` is  This can be relevant when your software or dependencies have architecture-specific considerations. For `macOS and Ubuntu`, use amd64. for `Windows`, GitHub Actions uses amd64 by default

    **Software:**
    * Docker
    * FFmpeg

    **Python Packages:**
    * NumPy
    * TensorFlow
    * PyTorch
    * Pandas

    **Dependencies:**

    - **Cryptography Libraries**
    - **Database Drivers:** Drivers for databases like PostgreSQL or MySQL may have architecture-specific versions.
    - **Image Processing Libraries:** Libraries like Pillow for image processing may have optimized builds
