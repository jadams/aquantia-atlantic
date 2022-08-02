# intel-atlantic
Linux 5.4 kernel driver for  atlantic driver for the Aquantia AQtion AQC107 10 Gigabit Ethernet Controller

## Installation

Install it from source with:

```
git clone https://github.com/jadams/intel-atlantic.git
cd intel-atlantic

sudo dkms add .
sudo dkms build atlantic -v 5.4
sudo dkms install --force atlantic -v 5.4
```
