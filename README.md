# Gaming-Testcase
Performed QA testing for multiplayer mobile game (BGMI), covering gameplay, cross-platform sync, voice chat, network latency (30ms–200ms), FPS stability, UI/UX, error handling, and accessibility. Validated revive, event modes, payments, and replay systems.

Features Explained:

🎯 BGMI Testing
1.Account/Login Tests:
Validated user registration, login workflows, password recovery, and session management to ensure secure access.

2.Anti-Cheat Checks:
Tested detection of unauthorized tools (speed hacks, aimbots) and verified server-side cheat prevention mechanisms.

3.Device Compatibility:
Tested on 20+ Android/iOS devices to ensure consistent performance across screen sizes, OS versions, and hardware specs.

4.Network Stability:
Simulated 3G/4G/Wi-Fi conditions to validate lag tolerance, reconnection workflows, and packet-loss handling.

5.In-App Purchases:
Verified UC (Unknown Cash) transactions, reward delivery, and Google Play/App Store compliance.

🏃♂ Temple Run Testing

1.Core Gameplay (Swipe Controls):
Tested swipe gestures (left/right/up/down) for responsiveness, collision detection, and edge-of-path handling.

2.Power-Up Validation:
Ensured Magnet, Shield, and Coin Multiplier abilities functioned with correct durations and visual effects.

3.Performance Metrics:
Monitored FPS stability (target: 60 FPS), RAM usage, and battery drain across devices.

4.Edge Cases:
Tested extreme scenarios like max coin overflow, 8+ hour play sessions, and low-storage installations.

🛠️ Tools Used
Jira/TestRail: For defect tracking and test case management.
ADB/Xcode: To interact with Android/iOS devices/emulators for log analysis and debugging.
Postman: API testing for login, purchases, and leaderboard integrations.
Charles Proxy: Monitored encrypted network traffic to validate data integrity and latency.
