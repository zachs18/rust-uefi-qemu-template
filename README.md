# Rust UEFI Template

Requirements:

* `uefi-run` (`cargo install uefi-run`; the snap version didn't work for me due to file permissions)
* `qemu-system-x86_64` (`sudo apt install qemu-system-x86`)
* `ovmf` (`sudo apt intall ovmf`)

All the package names and file paths are for Ubuntu. Change the relevant paths in `.cargo/config.toml` for other systems.
