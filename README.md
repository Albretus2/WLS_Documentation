# WSL ( Windos SubSytem Linux)
_versi menggunakan arch linux_

### basic command pertama kali menggunakan wsl

| Keymaps                            | deskripsi                          |
| ---------------------------------- | ---------------------------------- |
| `wsl -v` `wsl --version`           | menampilkan versi wsl              |
| `wsl -l -v` `wsl --list --verbose` | list distro yang terinstall di wsl |
| `wsl -l -o` `wsl --list --online`  | list distro yang bisa di install   |
| `wsl -d archlinux`                 | masuk ke distro arch               |
| `wsl -d archlinux -u <username>`   | masuk dengan user                  |
| `wsl -d archlinux -u root`         | masuk denga user root              |
| `wsl --install -d <distroname>`    | install distro di wsl              |
| `wsl --set-default <distroname>`   | default distro                     |
| `wsl --shutdown`                   | memamtiakan wsl                    |
