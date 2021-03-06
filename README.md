# Securo
A small PowerShell script for doing security related tasks.

## Usage

* For GnuPG usage, the script checks that GnuPG is installed on the system, if not, attempts to install it.

Usage is quite self-explanatory:

```powershell
.\Securo.ps1 -Gpg -SigningKeyFilePath "path\to\key\tails-signing.key" -SignatureFilePath "path\to\sig\tails-amd64-4.1.1.img.sig" -FileToValidatePath "path\to\file\tails-amd64.img" -Verbose

# OR

.\Securo.ps1 -Hash -FileToHashPath ".\Securo.ps1" -Algorithm "SHA256"

# OR

.\Securo.ps1 -Hash -FileDirHashPath "D:\path\to\directory" -Algorithm "MD5" -Verbose
```

## Contributing

* Feel free to point out any issues or help me make improvements to the script 😊

## Authors -- Contributors

* **dbrennand** - *Author* - [dbrennand](https://github.com/dbrennand)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) for details.