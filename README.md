# 🛡️ DEEPTRUTH
**Multi-Layer AI Verification System**

Combat deepfakes and AI-generated misinformation with cryptographic hashing and frame-by-frame pattern matching directly in the browser.

🔗 **[Click here to view the Live App](https://anjali-iitm.github.io/DEEPTRUTH/)**

## 🧪 How to Test the Live Demo (Important!)

Since DeepTruth uses a **Privacy-First Local Ledger**, the database starts empty in new browser sessions (like Incognito). To see the AI Verification in action, please follow these steps:

REGISTER: Go to the VERIFIED DATABASE tab, upload a video, and click Save to Secure Cloud.

VERIFY: Go to the FORENSICS LAB tab, upload the SAME video, and scan it. It will show AUTHENTIC MATCH (Green).

TEST FAKE: Upload any OTHER video. It will show DEEPFAKE (Red) because it's not in our registry.

---

## 🚀 Key Features

* **System Architecture:** Built-in multi-modal AI engine combining Perceptual Hashing, Audio Extraction, and Face Analysis concepts.
* **Verified Database:** Authorized users can upload original media. The system hashes the video frames (generating cryptographic fingerprints) and stores them securely. Includes simulated biometric author verification.
* **Forensics Lab:** Upload a suspect video to run a frame-by-frame pattern match against the trusted database. The system calculates a Hamming Distance to detect manipulated frames, outputting a definitive Anomaly Score and Authenticity Verdict.
* **Persistent Storage:** Uses local browser storage to ensure your verified database records remain intact even after a page refresh.

## 💻 Tech Stack
* **Frontend:** React.js, Tailwind CSS
* **Icons:** Lucide React
* **Architecture:** Single-file component using Babel and ESM Import Maps for instant browser compilation without a build step.

## ⚙️ How to Run Locally
Because this project utilizes Babel standalone and ESM imports, it requires zero installation or node modules. 
1. Clone this repository or download the code.
2. Open the `index.html` file in any modern web browser.
3. The React app will compile and run instantly!

## 👥 Team Members
* **Varad Aphale** (Technical documentation & Research)
* **Saloni Sharma** (Design & Documentation)
* **Mahima R** (Research & Analysis)
* **Raulo Netrananda**(Research & Analysis)
* **Priyanshu Raj** (Design & Product Strategic)
* **Anjali Yadav** (Developer & Product Strategic) 
