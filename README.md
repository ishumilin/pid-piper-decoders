# PID Piper Decoders

This repository contains the standalone `blackbox_decode` binaries required for **PID Piper** to parse Blackbox logs from Betaflight and INAV.

Due to licensing requirements (GNU GPLv3), these tools are distributed separately from the main PID Piper application. The PID Piper application will automatically download the correct version for your system on first use.

## Available Binaries

This repository includes pre-compiled binaries for:

| Platform | Architecture | Betaflight Binary | INAV Binary |
|----------|--------------|-------------------|-------------|
| **macOS** | Universal (Intel & Apple Silicon) | `blackbox_decode_mac` | `blackbox_decode_INAV_mac` |
| **Windows** | x64 | `blackbox_decode_win.exe` | `blackbox_decode_INAV_win.exe` |
| **Linux** | x64 | `blackbox_decode_linux` | `blackbox_decode_INAV_linux` |

## Usage with PID Piper

1.  Open PID Piper.
2.  The application will detect missing decoders and prompt you to download them.
3.  Click **Download** to automatically fetch and install the correct tools for your system.

**Manual Installation:**
If you prefer to install manually, download the files for your OS listed above and place them in your PID Piper data directory:
*   **macOS:** `~/Library/Application Support/PID Piper/bin/`
*   **Windows:** `%APPDATA%\PID Piper\bin\`
*   **Linux:** `~/.config/PID Piper/bin/`

(Note: Rename the files to `blackbox_decode` and `blackbox_decode_INAV` / `.exe` after downloading if installing manually).

## Source Code

These binaries are compiled from the open-source projects:
*   [betaflight/blackbox-log-viewer](https://github.com/betaflight/blackbox-log-viewer)
*   [iNavFlight/blackbox-log-viewer](https://github.com/iNavFlight/blackbox-log-viewer)

## License

These tools are licensed under the **GNU General Public License v3.0 (GPLv3)**. See the [LICENSE](LICENSE) file for details.
