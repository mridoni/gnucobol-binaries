## GnuCOBOL binaries

This repository is used to generate the Windows x86/x64 [GnuCOBOL](https://gnucobol.sourceforge.io/) compiler packages included with [Gix-IDE](https://github.com/mridoni/gix). Should they suit your usage, they can also obviously be used as "standalone" installs, without Gix-IDE.

The most recent binary packages are in the "Releases" page. All of them are signed with my GPG private key. The corresponding public key (m.ridoni@gmail.com, fingerprint
70E4 08CF B89B 5FA8 32E4 5292 EFDC 94BD 5260 B939) has been published on pgp.mit.edu and keyserver.ubuntu.com and is available at https://github.com/mridoni.gpg

**Available packages**

- GnuCOBOL 3.1.2 Windows x86+x64 (MSVC, build options included: BDB, MPIR, PDcurses, XML2, JSON)
- GnuCOBOL 3.1.2 Windows x86 (MinGW32, GCC 11.2.0, build options included: BDB, GMP, ncursesw, XML2, JSON)
- GnuCOBOL 3.1.2 Windows x64 (MinGW64, GCC 11.2.0, build options included: BDB, GMP, ncursesw, XML2, JSON)

**Licenses**

- The GnuCOBOL compiler is licensed under the GNU General Public License
- The GnuCOBOL run-time library is licensed under GNU Lesser General Public License
- Gix-IDE is licensed under GPL3/LGPL3
- The workflow files in this repository are dually licensed under GPL3 or LGPL3
