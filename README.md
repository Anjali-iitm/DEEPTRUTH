# 🛡️ DEEPTRUTH
**Multi-Layer AI Verification System**

Combat deepfakes and AI-generated misinformation with cryptographic hashing and frame-by-frame pattern matching directly in the browser.

🔗 **[Click here to view the Live App](https://anjali-iitm.github.io/DEEPTRUTH/)**

## 🧪 How to Test the Live Demo (Important!)

The DeepTruth database is already pre-loaded with an authentic, verified original video. To test the system's AI detection, please follow these simple steps:

1. **Download the Test Files:** Download the two short test videos from this Google Drive link: 
   * *Video 1* (Authentic) **(https://drive.google.com/file/d/1zbQAjrfdv-X9keON67EWr6ylI7cjpe8M/view?usp=drive_link)**
   * *Video 2* (Deepfake/Altered) **(https://drive.google.com/file/d/1lyeBdJrt8aCXW9xOlhps07tcpBWpl4lP/view?usp=drive_link)**
2. **Go to the Forensics Lab:** Open the Live App and click on the **FORENSICS LAB** tab.
3. **Test a Match:** Upload **Video 1**. Click "Scan Against Database Records." The system will cross-reference the hashes with the pre-loaded original video and output a **100% Authentic Match** (Green).
4. **Test an Anomaly:** Click the "Scan Another Video" button. Upload **Video 2**. The system will scan its frames, detect the manipulation, and correctly flag it as **NO MATCH / DEEPFAKE** (Red). 
5. **Try Your Own Video!** Want to test its limits? Upload any random video from your own computer. Since its cryptographic fingerprint isn't in our secure database, the system will instantly catch it and output a **NO MATCH**.
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
