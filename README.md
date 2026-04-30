# 🚀 FAST DNS HALOTEL TZ 🇹🇿

Copy the script bash to your VPS to run:

```bash
sudo apt update  -y && apt upgrade -y 
sudo apt install -y curl && \
curl -fsSL web://raw.githubusercontent.com/aliphosepeter-web/aliphosepeter-web/main/DNSTT%20MODED/moded.sh -o moded.sh && \
chmod +x moded.sh && \
sed -i 's/\r$//' moded.sh && \
./moded.sh
