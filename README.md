# TrustShield
AI-driven continuous Identity validation framework
Behavioral Biometrics Engine (Tackles "Anomalous User Behavior")

How it works: Instead of just looking at what the user types, it looks at how they type. It collects telemetry data like typing speed, touchscreen swipe pressure, device angle, and typical navigation paths.
The Hack: If an attacker steals a session cookie or a logged-in phone, their physical interaction with the app will differ from the real user. The system detects this anomaly and immediately prompts for a biometric re-verification (like Face ID) before allowing any transaction.
Smart Onboarding & Deepfake Detection (Tackles "Suspicious Onboarding & KYC Fraud")

How it works: During the digital KYC process, fraudsters often use synthetic identities or AI-generated deepfakes.
The Hack: Integrate an AI model that analyzes the video feed during KYC for micro-inconsistencies (unnatural blinking, pixel manipulation, edge blending) to detect deepfakes. Cross-reference the location and network data to flag suspicious onboarding rings.
Adaptive Risk-Based Access Control (Tackles "New Device Access & Account Recovery")

How it works: Assigns a dynamic "Trust Score" (e.g., 0 to 100) to every session.
The Hack: If a login attempt comes from a new device, a new IP, or via a suspicious account recovery request, the trust score drops. Instead of a hard block, the system introduces "friction" proportionally—asking for an OTP, then an email link, then a live selfie. This achieves the hackathon's goal of a "friction-optimized user experience" (normal users get zero friction; risky users get high friction).
Insider Threat Monitor (Tackles "Privileged Access Misuse")

How it works: A separate dashboard for the bank's internal IT/Security team.
The Hack: It monitors the bank's own employees. If an employee who normally accesses 10 customer records a day suddenly tries to download 10,000 records at 2:00 AM, the system flags it as "Privileged access misuse", blocks the action, and alerts the admin.
