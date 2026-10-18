# DevOps-Linux-Mastery-Pro

🐧 DevOps Linux Mastery Pro v6.0

Browser-Native Linux & SRE Interactive Simulator: Master 18 core Linux & DevOps command modules across 220+ progressive real-company production stages, featuring a real-time Virtual Filesystem (Inodes & Permissions), interactive Vi/Vim, GNU Nano, and top Process Monitor, a dedicated 14-Stage AWK Function & Alert Lab, Hinglish deep-dive guides with memory tricks, and an Infinite Procedural Challenge Generator — all in a zero-setup single HTML file.

Interactive browser-based Linux & DevOps simulator with 18 modules, 220+ real-company stages, live Vi/Vim, Nano, Top, Inode inspector & 14-stage AWK Alert Lab.

✨ Key Features1. 🖥️ Multi-Mode Interactive Linux TerminalNo Docker container, VM, or backend server required. Everything runs 100% client-side in your browser:Standard Bash Shell: Supports command chaining (|), output redirection (>, >>), command history (↑ / ↓ arrows), Tab auto-completion, and a Live Command Meaning Decoder that explains flags in real time as you type.Real-Time Modal vi / vim Editor: Practice switching between Normal Mode (dd delete line, yy yank, p paste), Insert Mode (i), and Command Mode (:w, :wq, :q!, :set nu, and global regex substitutions :%s/old/new/g).Real-Time GNU nano Editor: Edit files directly and practice keyboard/clickable shortcuts (^O WriteOut, ^X Exit, ^W Where Is, ^K Cut Line) — including live crontab -e editing.Live top Process Monitor: Spot high-CPU rogue processes (like a stuck crypto miner at 94.8% CPU on PID 4092) and press k to send SIGKILL in real time.2. 🗂️ Live Server Filesystem, Inodes & File InspectorInspect /home/devops, /var/log, and /etc in real time as your terminal commands mutate files on the virtual disk.Visualize Inode numbers (i:10424), link counts, octal/symbolic permissions (-rwxr-xr-x), and file ownership.See the difference between Hard Links (ln) sharing the exact same Inode and Symbolic/Soft Links (ln -s) using -> pointers.3. 🚨 Dedicated AWK Function & Alert Lab (14 Progressive Stages)Most tutorials stop at awk '{print $1}'. DevOps Linux Mastery Pro v6.0 teaches how SREs use AWK as a full programming language:4-Step Visual Architecture: BEGIN { } initialization $\rightarrow$ function trigger_alert() custom logic $\rightarrow$ { Main Loop } $\rightarrow$ END { } summary reports.3 Built-In Production .awk Scripts:alert_monitor.awk — PagerDuty High-CPU (>85%) detector using custom AWK functions.sla_audit.awk — API Gateway HTTP 500 & latency SLA breach auditor on /var/log/nginx_access.log.ddos_shield.awk — Security rate-limit & DDoS IP blocker using AWK associative arrays (hits[$1]++).

🚀 Quick Start (Zero Installation)

Because this project is engineered as a self-contained client-side application, you can run it immediately:

Clone the repository:

git clone https://github.com/YOUR_USERNAME/devops-linux-mastery-pro.git
cd devops-linux-mastery-pro


Launch in your browser:

Double-click devops_linux_mastery_pro.html to launch the Interactive Linux & SRE Simulator.

Double-click devops_linux_mastery_demo_video.html to watch the 12-Shot Cinematic Product Demo Film.

Deploy to GitHub Pages / Vercel / Netlify:

Rename devops_linux_mastery_pro.html to index.html and enable GitHub Pages in your repository settings for instant hosting.

🤝 Contributing

Contributions, new production incident stages, and additional .awk alert templates are welcome!

Fork the repository.

Create your feature branch (git checkout -b feature/new-sre-module).

Commit your changes (git commit -m 'Add journalctl & lsof troubleshooting stages').

Push to the branch (git push origin feature/new-sre-module) and open a Pull Request.

📄 License

Distributed under the MIT License. Free to use for self-study, DevOps bootcamps, university labs, and SRE interview preparation.
