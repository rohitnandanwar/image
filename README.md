sudo apt install libpcap-dev
g++ live_capture.cpp -o live_capture -lpcap
sudo ./live_capture
