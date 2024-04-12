# Opti Taco Feeder

Try this at: https://lightning-goats.github.io/Opti_Taco_Feeder/

This HTML file is a template for an Obs-Studio overlay that interacts with the Lightning Network through LNBits, allowing for Lightning payments to be received and displayed dynamically on the page.

## Features

- Displays a container (`#container`) with a fixed size of 1280px by 720px, positioned in the center of the screen.
- Includes a QR code container (`#qr-code-container`) at the bottom left of the container, with a fixed size of 120px by 120px, for displaying QR codes related to Lightning payments.
- Shows the amount of received sats (`#sats_left`) at the bottom center of the container.
- Utilizes WebSocket to listen for updates on received payments and dynamically updates the UI accordingly.

## Setup

1. Set the `wallet` variable to your LNBits wallet ID.
2. Set the `LNURL` variable to your LNURL from LNBits LNURLP extension.
3. Set the `server` variable to your LNBits server URL (`legend.lnbits.com` by default).
4. Set the `christine` variable to your desired limit in sats.  (Easter Egg)

## Usage

- Open the HTML file as an overlay in your video broadcast software. Ex: Obs-Studio.
- Users feed Opti tacos by scanning the QR code displayed in the `#qr-code` container with a Lightning wallet.

## Note

- The page is designed to work with an LNBits install.

