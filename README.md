RF433 Telnet Chat for M5StickC Plus

Description

RF433 Telnet Chat is an innovative tool designed for the M5StickC Plus to transmit text messages over 433 MHz RF signals. This application operates as a one-way messaging system, allowing the user to send concise text messages from the transmitter to a receiver.

Character Limits

The application is optimized to handle messages up to 30 characters in length. When crafting messages to be transmitted, it is essential to consider this limitation to ensure the reliable and accurate delivery of the information.

Applications

Instructional Messages:

Useful for disseminating brief instructional or informational messages in various settings like workshops, classes, or guided tours.

Clandestine Communications:

Suitable for transmitting covert or confidential messages in a secure manner.

Teleprompter Script Basis:

Ideal for sending short, real-time cues or lines to speakers, presenters, or performers discreetly.

Modes

Transmitter Mode: // #define RF433RX and enable Wi-Fi for Telnet messaging capability.
Receiver Mode: #define RF433RX and disable Wi-Fi, converting the device into a dedicated message receiver that displays the messages on the M5StickCPlus.

Configuration

Transmitter:

Uncomment // #define RF433RX
Set wifiHotspotEnabled to true.

Receiver:

Uncomment #define RF433RX
Set wifiHotspotEnabled to false.

Usage

Transmitter Mode:

Send a test message using Button A on the device or via Telnet where you can send messages up to 30 characters in length.

Receiver Mode:

The device will listen for incoming messages and display them upon receipt.

Contributions

Feel free to contribute, improve, or suggest enhancements to this project!

Note: Due to the 30-character limitation, users should craft messages concisely to ensure they are transmitted and received accurately and effectively. Longer messages may be truncated or not transmitted correctly.
