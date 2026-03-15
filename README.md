# Yaver APT Repository

Install Yaver CLI on Debian/Ubuntu:

```bash
curl -fsSL https://kivanccakmak.github.io/apt-yaver/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/yaver.gpg
echo "deb [signed-by=/usr/share/keyrings/yaver.gpg] https://kivanccakmak.github.io/apt-yaver stable main" | sudo tee /etc/apt/sources.list.d/yaver.list
sudo apt update
sudo apt install yaver
```
