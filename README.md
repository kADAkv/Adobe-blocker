# Adobe-blocker
A modern, lightweight utility built with C# and WPF to automate Windows Firewall rules for Adobe products.

/// Key Features
/ Deep Scan Engine: Automatically identifies all Adobe installations across system directories (Program Files, Common Files, etc.).
/ One-Click Rule Enforcement: Simultaneously creates Inbound and Outbound block rules for every executable found.
/ Instant Cleanup: Removes all custom firewall rules created by the app in a single second.
/ Single Executable: Self-contained build (~80-100MB). No .NET installation or external DLLs required.
/ Modern UI/UX: Clean, dark-themed interface with fluid animations and real-time progress tracking.
///

/// Tech Stack
/ Language: C#
/ Framework: .NET 8.0 / WPF
/ Methodology: Native Windows Shell commands (netsh advfirewall)
/ Deployment: Single-file Publish (AOT-ready)
///
