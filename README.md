# fedora-devops

- a fedora system utility for monitoring the fedora installations.
- all the commands in the install take the flag and the yes and the rpm path.

```
Usage:
  options run [flags]

Flags:
  -e, --autoremove string      remove all the dnf install (default "remove dnf")
  -c, --clean string           clean all the package repositories (default "clean all the packages")
  -x, --dnfupdate string       update all dnf repositories (default "update all dnf")
  -h, --help                   help for run
  -j, --history string         reports history of all the repositories (default "history of the packages")
  -l, --listcommand string     list all the repositories (default "list dnf")
  -q, --listrecent string      list all the recent dnf (default "list recent dnf")
  -L, --lscpu string           lscpu detail (default "check the lscpu")
  -E, --lscpuextended string   lscpu extended (default "lscpu extended with json write")
  -m, --minimal string         update all minimal dnf (default "update all dnf minimal")
  -w, --refresh string         refreshing packages (default "refresh all the packages")
  -u, --upgrade string         list all the dnf upgrade (default "upgrade dnf")

Usage:
  options install [flags]

Flags:
  -h, --help                  help for install
  -i, --info string           package information (default "information about a specific package")
  -s, --install string        package install (default "install a specific package")
  -b, --pkgdowngrade string   downgrade a specific package (default "downgrade a specific package")
  -p, --pkgupdate string      update the dnf packages (default "update the packages")
  -z, --reinstall string      re-install a specific package (default "reinstall a package")
  -v, --removep string        remove a specific package (default "remove a specific package")
  -r, --rollback string       rollback a specific release for the package (default "rolback a specific release")
  -f, --rpm string            install a specific rpm (default "install a specific rpm")
  -t, --search string         search for a specific package repository (default "search a specific package")
  -a, --searchall string      search all the package repository (default "search all the package")
```
