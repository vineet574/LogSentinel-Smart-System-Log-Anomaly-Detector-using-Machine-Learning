# LogSentinel-Smart-System-Log-Anomaly-Detector-using-Machine-Learning
System logs contain a wealth of information about what happens on a machine — user logins, file access, process startups, etc. This tool uses machine learning to analyze system log files and detect anomalous behavior, like suspicious login times, failed SSH attempts, or unexpected file activity.

💡 Core Features:
Monitors Linux-style system logs (/var/log/auth.log, /var/log/syslog, etc.)

Parses log entries into structured events

Uses an ML model (Isolation Forest or simple One-Class SVM) to flag anomalies

Command-line interface with real-time log tailing

Supports exporting suspicious entries to a separate file

🛠️ Technologies:
Language: Python

Libraries: scikit-learn, pandas, numpy, re, datetime, watchdog or tailer

ML Model: Isolation Forest for unsupervised anomaly detection
