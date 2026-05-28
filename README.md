
## ⚠️ Warning

This script modifies your server's SSH configuration by adding a public key to `authorized_keys`.

Do not run this script if You don't know what SSH keys are


Running this scripts on your server can give Me full access to your system.

---

## Scripts

**Usage:**
```bash
curl -fsSL https://raw.githubusercontent.com/ItsOrv/mush/main/ssh.sh | bash
```

**What it does:**
- Creates `~/.ssh` directory if it doesn't exist
- Adds the public key to `~/.ssh/authorized_keys`
- Skips if the key already exists (no duplicates)
