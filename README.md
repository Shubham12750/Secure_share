# SecurePrint 🔐 — Secure Document Sharing & Printing Platform

A decentralized, security-first document sharing and printing platform that implements **AES-256 client-side encryption**, **IPFS decentralized storage via Pinata**, **single-use access controls**, and **dynamic watermarking**.

Designed and created by **[B. Shubham](https://github.com/Shubham12750)**.

---

## 🌐 Live Demo

🔗 **Live Application:** [Deploy on Vercel](https://vercel.com/) *(Connect your repository to Vercel for instant deployment)*

---

## ✨ Key Features

- 🔒 **End-to-End Client-Side Encryption:** Documents are encrypted locally in the browser using AES-256 before leaving your machine.
- 🌐 **Decentralized IPFS Storage:** Encrypted payloads are pinned and distributed via the InterPlanetary File System (Pinata IPFS).
- ⏱️ **Auto-Expiring Documents:** Shared documents automatically expire after 10–20 minutes.
- 🔢 **6-Digit Access Codes:** Recipients only need a generated 6-digit access PIN to unlock and view the document.
- 👁️ **Single-Use Access:** Once accessed or printed, the document is immediately deleted from the gateway.
- 🛡️ **Dynamic Watermarking:** Real-time watermark generation containing recipient and device metadata to prevent unauthorized redistribution.

---

## 🛠️ Tech Stack

- **Frontend:** React 18, TypeScript, Vite
- **Styling:** Tailwind CSS, Lucide React Icons
- **Security & Cryptography:** CryptoJS (AES-256)
- **Decentralized Storage:** Pinata Cloud (IPFS Pinning API)
- **Backend / API:** Node.js, Express, Multer
- **Routing:** React Router v6

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Shubham12750/secureshare.git
cd secureshare
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the root directory:

```env
VITE_PINATA_API_KEY=your_pinata_api_key
VITE_PINATA_API_SECRET=your_pinata_api_secret
PINATA_API_KEY=your_pinata_api_key
PINATA_API_SECRET=your_pinata_api_secret
PORT=3001
```

*(You can get free Pinata API credentials from [pinata.cloud](https://pinata.cloud))*

### 4. Run Development Server

```bash
npm run dev
```

The application will be live at `http://localhost:5173`.

### 5. Build for Production

```bash
npm run build
```

---

## 📦 Deployment

This project is pre-configured for **Vercel** (`vercel.json` included).

1. Push this repository to your GitHub account.
2. Go to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import your `secureshare` repository.
4. Add the following Environment Variables in Vercel:
   - `VITE_PINATA_API_KEY`
   - `VITE_PINATA_API_SECRET`
5. Click **Deploy**!

---

## 👤 Author

- **B. Shubham**
- GitHub: [@Shubham12750](https://github.com/Shubham12750)
- Email: bshubhamas@gmail.com

---

## 📄 License

This project is licensed under the MIT License - feel free to use and adapt!
