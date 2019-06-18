Adding OpenWRT support for Mojo Networks C-75 (Airtight C-75)
Airtight C-75 (Mojo Networks C-75) Dual radio, Dual concurrent 3x3 MIMO 802.11ac access point based on Qualcomm Atheros QCA9550.

Specification:
* SoC	: Qualcomm Atheros QCA9550-AT4A
* RAM	: DDR2 128 MiB
* Flash	: SPI-NOR 2*16 MiB
* WLAN	: 2.4/5 GHz 3T3R
* 2.4 GHz: QCA9550 (SoC)
* 5 GHz : QCA9890-BR4A
* Ethernet	: 2x 10/100/1000 Mbps
* Switch : AR8034-AL3C
* LEDs/keys	: 8x/1x
* UART: Standart RJ45 wired (with level shifter) to TTL J3 unpopulated on PCB
* RJ45: standart Cisco cable
* J3: 1=3.3v 2=TX 3=RX 4=GND
* Settings: 115200 bps, no flow control
* JTag: Unpopulated J1

Known limitations in this release:
 * This board has QCA9550-AT4A CPU but identified as QCA9558.
 * LEDs "2.4Ghz WiFi" and "Power Green" do not work, power is always orange and 2.4G is always off.
 * Reset Button does nothing.
