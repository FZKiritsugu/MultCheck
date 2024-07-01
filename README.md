<div align="center">
  <h1>MultCheck</h1>
  <br/>

  <p><i>MultCheck is a open-source, and easy-to-use malware AV test, created by <a href="https://infosec.exchange/@Pengrey">@Pengrey</a>.</i></p>
  <br />
  
</div>

MultCheck is a malware-analysis tool that can be used to test the detection of a file by multiple AV engines.

It is designed to be easy to use, and to be able to test multiple AV engines. It is also designed to be easy to extend, and to be able to add custom AV engines.

## Installation
-  Run `go build` under the root directory of the project.

-  Or directly run the compiled binaries in the bin directory.

```bash
$ cd src
# Build for Windows
## 64-bit
$ GOOS=windows GOARCH=amd64 go build -o ../bin/multcheck_x64.exe main.go

## 32-bit
$ GOOS=windows GOARCH=386 go build -o ../bin/multcheck_x32.exe main.go
```

## Demo

https://github.com/MultSec/MultCheck/assets/55480558/bf3bf85a-e9b1-408a-ab9d-bf9486602b15

# Documentation
For more information on how to use the MultLdr-cli, check the [documentation](https://multsec.github.io/docs/multcheck/)

## License
This project is licensed under the GNU General Public License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project is inspired by the following projects:
- [DefenderCheck](https://github.com/matterpreter/DefenderCheck)
- [ThreatCheck](https://github.com/rasta-mouse/ThreatCheck)
- [ThreatCheck](https://github.com/PACHAKUTlQ/ThreatCheck)
- [GoCheck](https://github.com/gatariee/gocheck)
