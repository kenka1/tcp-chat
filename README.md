# Simple C++ TCP Chat-server (using `poll`)

### Build
```bash
git clone https://github.com/your-repo/tcp-chat.git  
cd tcp-chat  
mkdir build && cd build  
cmake .. && make
```

### Usage
```bash
./server <PORT> #Example: ./server 8080
telnet <IP> <PORT> #Example: telnet 127.0.0.1 8080
```
