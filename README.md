![seclists.png](SecLists.png "seclists.png")

### About SecLists-Express

Seclists-Express is the security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. The goal is to enable a security tester to pull this repository onto a new testing box and have access to every type of list that may be needed.

Seclists-Express is a frequently-updated fork of Seclists maintained by [ItsIgnacioPortal](https://github.com/ItsIgnacioPortal).

- - -

<!--- details anchor -->

### Repository details

Size of a complete clone of SecLists is currently at `1.5 GB`

Cloning this repository should take 4-5 minutes at 5MB/s speeds.

<!--- details anchor -->

- - -

### Install

**Zip**

```
wget -c https://github.com/ItsIgnacioPortal/SecLists-Express/archive/master.zip -O SecList.zip \
  && unzip SecList.zip \
  && rm -f SecList.zip
```

**Git (Small)**

```
git clone --depth 1 \
  https://github.com/ItsIgnacioPortal/SecLists-Express.git
```

**Git (Complete)**

```
git clone https://github.com/ItsIgnacioPortal/SecLists-Express.git
```

- - -

### Attribution

See [CONTRIBUTORS.md](CONTRIBUTORS.md)

- - -

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

- - -

### Similar Projects

- [Assetnote Wordlists](https://wordlists.assetnote.io/)
- [fuzz.txt](https://github.com/Bo0oM/fuzz.txt)
- [FuzzDB](https://github.com/fuzzdb-project/fuzzdb)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [Cook](https://github.com/giteshnxtlvl/cook)
- [SamLists](https://github.com/the-xentropy/samlists)

- - -

### Licensing

This project is licensed under the [MIT license](LICENSE).

[![MIT License](https://img.shields.io/badge/license-MIT_License-blue)](https://opensource.org/licenses/MIT)
—

<sup>NOTE: Downloading this repository is likely to cause a false-positive alarm by your anti-virus or anti-malware software, the filepath should be whitelisted. There is nothing in SecLists that can harm your computer as-is, however it's not recommended to store these files on a server or other important system due to the risk of local file include attacks.</sup>
