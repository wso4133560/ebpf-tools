# ebpf-tools
用于做ebpf的功能脚本收集

https://tutorial.eunomia.dev/0-introduce/index.html

# 软件下载
wget https://aka.pw/bpf-ecli -O ecli && chmod +x ./ecli
wget https://github.com/eunomia-bpf/eunomia-bpf/releases/latest/download/ecc && chmod +x ./ecc
sudo apt install clang llvm

# 编译bpf
./ecc minimal.bpf.c

# 运行bpf
sudo ./ecli run package.json
