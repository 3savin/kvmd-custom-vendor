# KVMD (Custom)

[![CI](https://github.com/pikvm/kvmd/workflows/CI/badge.svg)](https://github.com/pikvm/kvmd/actions?query=workflow%3ACI)
[![Discord](https://img.shields.io/discord/580094191938437144?logo=discord)](https://discord.gg/bpmXfz5)

This is a custom fork of [KVMD](https://github.com/pikvm/kvmd), the main PiKVM daemon.

## Changes from upstream

### Pico HID firmware — Logitech device spoofing
I didn't like the fact the the firmware identified itself as a piKVM HID device. I forked this firmware 
to change it to identify itself as a logitech keyboard and mouse. The compiled firmware is available in the release section.

In the future, I may further modify this firmware to use UART mode by default to make my setup cleaner and eliminate the need for an extra cable.