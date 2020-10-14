# kubectl-krb
client-go credential plugin for kerberos


### Build

You may build the plugin for your OS:

- `cd scripts`
- Run the build script for your OS
- Or use `build.sh` as a jumping off point and use these to help build for your OS
  - From **_stackoverflow_**: [All possible GOOS value?](https://stackoverflow.com/questions/20728767/all-possible-goos-value)
  - GOOS => `android darwin dragonfly freebsd linux nacl netbsd openbsd plan9 solaris windows`
  - GOARCH => `386 amd64 amd64p32 arm arm64 ppc64 ppc64le mips mipsle mips64 mips64le mips64p32 mips64p32le ppc s390 s390x sparc sparc64`

Then rename the plugin copy the plugin to an executable path:

- `/usr/local/bin/kubectl-krb` Linux/Mac
- `C:\windows\system32\kubectl-krb.exe` Windows - don't forget to add the `.exe` extension

### Debug

To debug the plugin with VS Code:

- set env variables in `.vscode/launch.json` in `configurations->env`
