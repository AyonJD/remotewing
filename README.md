# RemoteWing — 60 FPS Windows-to-Android Remote Desktop & Dual-Mic Bridge

**Official Website:** [https://remotewing.online](https://remotewing.online) · **Downloads:** [Windows x64 & Android APK](https://remotewing.online/download) · **Docs:** [Setup & Architecture](https://remotewing.online/docs)

RemoteWing is a zero-account, hardware-accelerated 60 FPS remote desktop and simultaneous 48 kHz Opus Dual-Mic Bridge connecting Android 10+ phones to Windows 10 & Windows 11 (x64) workstations.

## Key Engineering Highlights
- **60 FPS GPU Capture (~7 ms host pipeline):** Windows DXGI Desktop Duplication + hardware H.264 (NVENC / AMD AMF / Intel QuickSync) + dual WebRTC DataChannels.
- **Simultaneous Dual-Mic Bridge:** Use your [Android phone as a wireless 48 kHz PC microphone](https://remotewing.online/use-cases/phone-as-pc-microphone) without disabling your physical USB/headset mic.
- **Voice Vibe Coding Ready:** Dictate prompts to Claude Code, Codex, Cursor, and Antigravity from bed or anywhere ([Vibe Coding Guide](https://remotewing.online/use-cases/vibe-coding-from-phone)).
- **True Windows `LocalSystem` Service:** Full support for Windows Lock Screen (`Winlogon`), UAC prompts, and `Ctrl+Alt+Del`.
- **Zero User Accounts:** Hardware-bound Ed25519 keys (Windows DPAPI + Android Keystore) + 2-minute ephemeral QR/PIN + end-to-end `DTLS-SRTP`.
- **Free Offline LAN + $3/mo 4G/5G TURN:** 100% free forever on Local Wi-Fi; optional Pro TURN relay bypasses strict mobile CGNAT.

## Free Browser Diagnostic Tools
- [WebRTC NAT, STUN & 4G/5G CGNAT Checker](https://remotewing.online/tools/webrtc-nat-checker)
- [Online 48 kHz Microphone & dBFS Tester](https://remotewing.online/tools/mic-test)
- [60 FPS Remote Desktop Bandwidth Calculator](https://remotewing.online/tools/remote-desktop-bandwidth-calculator)
- [Windows 10/11 LAN & Firewall PowerShell Generator](https://remotewing.online/tools/windows-lan-command-generator)
