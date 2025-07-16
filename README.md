# LoRa_Secure_Chat
an Implementation security for LoRa Communication (Chat app) by Adding Diffie-Hellman key exchanges and AES encryption.

<p align="center">
  <img src="https://github.com/YD1RUH/LoRa_Secure_Chat/blob/main/LoRa.jpg?raw=true" alt="LoRa Chat System" width="60%">
</p>

## How to install
- clone this repository: `git clone https://github.com/YD1RUH/LoRa_Secure_Chat.git`
- get in to directory: `cd LoRa_Secure_Chat`
- install ESP driver, download from [here](https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads), choose `CP210x Windows Drivers`
- open ESP-Flasher, you can download form [here](https://github.com/Jason2866/ESP_Flasher/releases)
- choose .bin then select port serial for `TTGO LoRa32-OLED`
- clik `FLASH ESP`

## How to use
- access serial.
- for initiaion, input `callsign` `p` `g`, separated by `space`. then hit enter.
- enjoy secure chatting over LoRa.

## Feature
- reset Diffie-Hellman process if there's no response.
- on the air change bandwidth. just type `BW 125` for 125kHz, `BW 250` for 250kHz, and `BW 500` for 500kHz.
- maximum messages 1024 Character.

<div align="center">
  <a href="https://youtu.be/ow_Cv7KYM3o">
    <img src="https://img.youtube.com/vi/ow_Cv7KYM3o/0.jpg" alt="Watch on YouTube" width="480">
  </a>
</div>

