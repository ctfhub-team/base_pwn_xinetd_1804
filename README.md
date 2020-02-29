# 基础镜像 PWN Xinetd - Ubuntu 1804

A docker image to hold pwn challenges in ctf war

## Usage

Please check *.Dockerfile

## Example

[challenge_bctf_2018_pwn_begentle](https://github.com/ctfhub-team/challenge_bctf_2018_pwn_begentle)

## Env Vars

| Key                | Default Value    | Description                                                |
| ------------------ | ---------------- | ---------------------------------------------------------- |
| TCPDUMP_ENABLE     | (empty)          | Whether enable tcpdump or not                              |
| TCPDUMP_DIR        | /var/lib/tcpdump | Directory to write dump files (name=capture-$timestr.pcap) |
| TCPDUMP_ROTATE_SEC | 600              | Rotate time interval of capture file                       |
| FLAG               | (empty)          | Flag save in /flag                                         |
