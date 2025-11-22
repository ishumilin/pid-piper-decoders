# PID Piper Decoders

This repository contains the standalone `blackbox_decode` binaries required for **PID Piper** to parse Blackbox logs from Betaflight and INAV.

Due to licensing requirements (GPLv3), these tools are distributed separately from the main PID Piper application.

## Usage with PID Piper

1.  Download the `blackbox_decode` tool for your operating system (macOS).
2.  Place the file in your PID Piper data directory:
    *   **macOS:** `~/Library/Application Support/PID Piper/bin/`
3.  Restart PID Piper.

## Source Code

These binaries are compiled from the open-source projects:
*   [betaflight/blackbox-log-viewer](https://github.com/betaflight/blackbox-log-viewer)
*   [iNavFlight/blackbox-log-viewer](https://github.com/iNavFlight/blackbox-log-viewer)

## License

These tools are licensed under the **GNU General Public License v3.0 (GPLv3)**. See the [LICENSE](LICENSE) file for details.
