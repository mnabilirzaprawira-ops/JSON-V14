🧊 Changelog Magic Random Pro V14.0
[V14.0] - 2026-03-15 (Aether Core | Columbia Cryo)
🚀 Core & Logic Improvements

* Aether Logic 9.0 & AI Neural Scaling: Implemented smarter CPU scaling logic in service.sh. The system now dynamically toggles between performance mode during high loads and schedutil when idle for maximum efficiency.
* ART Compiler Turbo: Forced the system to use the speed filter for all app compilations (DEX2OAT). This makes app launches significantly faster compared to previous versions.
* Watchdog V14 (Anti-Bootloop): Added a new security feature in post-fs-data.sh. If the device fails to boot more than twice, the module will automatically disable itself.

🎮 Gaming & Display (SurfaceFlinger)

* SurfaceFlinger Enhancement: Eliminated VSync delay and improved refresh rate stability through debug.sf optimizations.
* Fatui Overclock V14: Gaming mode now includes the ability to disable CPU Throttling (msm_thermal) to prevent FPS drops when temperatures rise.
* Advanced HW Acceleration: The UI is now fully rendered by the GPU using OpenGL to eliminate stuttering in system animations.

🧹 System Maintenance

* Crystal Vacuum (SQLite Optimizer): A new feature in service.sh and functions.sh that automatically performs "vacuuming" on app databases to speed up Data I/O (read/write) processes.
* I/O Scheduler Tuning: Optimized data queuing on memory blocks by disabling add_random and setting read_ahead_kb to 256.

📱 Identity & UI

* Pixel 10 Pro Spoofing: Updated device identity and fingerprints to the latest Pixel model to unlock exclusive Google features.
* Columbia-Cryo Web UI: A total overhaul of the module dashboard for KernelSU/APatch users, featuring the "Liquid Glass Water Columbia" theme.
* Harmonic Sync: Added manual toggles via the UI for Boost, Gaming, Battery, and Vacuum modes.

🛠 Other Changes

* Updated customize.sh script with tributes to Android development legends.
* Integrated a QRIS donation system directly within the web dashboard.
* Optimized ZRAM using the LZ4 algorithm for lighter RAM management.

Note: Please reboot your device after installation to ensure all Aether Core logic runs perfectly in the background.

