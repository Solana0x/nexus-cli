# nexus-cli
Nexus CLI Phase 2

Node -> Manage nodes -> Add CLI node (wait or reload page if id is default)

![image](https://github.com/user-attachments/assets/ac4175b3-6758-4e39-aab2-333a0a89567f)

# Ubuntu

1.
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Input 1 -> Enter

2.
```
sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
```
Do you want to continue? [Y/n]  => y -> Enter

3.
```
sudo apt install -y protobuf-compiler
```

4.
```
curl https://cli.nexus.xyz/ | sh
```

5.
Out with: Ctrl + c

```
rm -rf $HOME/.nexus/prover-id
nano $HOME/.nexus/prover-id
```
Input your id -> Ctrl + x -> y -> Enter

6.

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
