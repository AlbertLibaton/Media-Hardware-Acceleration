<img width="855" height="800" alt="Screenshot 2026-06-03 at 6 19 36 AM" src="https://github.com/user-attachments/assets/33eeaa0c-b5e2-42a6-8d85-aad21715995a" />
<img width="1280" height="474" alt="Screenshot 2026-06-03 at 6 18 10 AM" src="https://github.com/user-attachments/assets/4c484102-3107-48a4-b88c-7a6ad2d6faff" />



# Media-Hardware-Acceleration

Control browser media codec usage by restricting VP9 (vp09) and AV1 (av01) codecs.

# Features
⚙️ Restricts VP9 (vp09) video codec playback
⚙️ Restricts AV1 (av01) video codec playback
🚀 Helps force websites to use alternative codecs such as H.264 when available
💻 Useful for systems with limited VP9 or AV1 hardware acceleration support
🔋 Can reduce CPU usage on some devices
🌐 Works automatically in the browser

# Description

Media Hardware Acceleration is a Chrome extension that modifies browser media capability detection to restrict VP9 (vp09) and AV1 (av01) codecs. This encourages websites and streaming platforms to select alternative codecs that may have better hardware acceleration support on certain systems.

The extension is designed for users, developers, and testers who want greater control over media codec selection and playback behavior.

# Why Use It?

Some devices have:

Better hardware decoding support for H.264
Higher CPU usage when decoding VP9 or AV1
Compatibility issues with specific codecs
Power efficiency differences between codecs

By restricting VP9 and AV1, websites may choose a codec that performs better on your hardware.

# Use Cases
Testing codec fallback behavior
Hardware acceleration troubleshooting
Browser media debugging
Performance analysis
Battery life optimization research
Privacy

This extension does not collect, store, or transmit user data. All processing occurs locally within the browser.

# Disclaimer

Codec selection ultimately depends on website implementation and browser behavior. Some websites may not offer alternative codecs and playback behavior can vary between platforms.

# Short GitHub Tagline

Restricts VP9 and AV1 codecs to influence browser media codec selection and hardware acceleration behavior.

# More Technical Tagline

A Chrome extension that limits VP9 (vp09) and AV1 (av01) codec support, allowing developers and users to test codec fallback paths and hardware-accelerated media playback.
