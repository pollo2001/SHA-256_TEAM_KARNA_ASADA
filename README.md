# 🪙 Bitcoin Hash Accelerator - Team **KARNA_ASADA**

This project is a hardware-accelerated Bitcoin miner implemented on an FPGA, featuring an optimized SHA-256 hashing core and a multi-phase mining module.

## 👥 Team Members & Contributions
* **Genaro Salazar Ruiz & Jay Paek:** Developed the SHA-256 hashing module, optimizing message scheduling and hash computation.
* **Hussein Alramadan & Preston Le:** Designed the Bitcoin miner, integrating nonce iteration, multi-phase hashing, and final hash validation.

---

## 🛠️ Project Components

### 1. SHA-256 Hashing Core
* ✅ Implements hardware-accelerated SHA-256, processing 512-bit message blocks.
* ✅ Optimized bitwise operations and message expansion for FPGA efficiency.
* ✅ FSM-based control logic ensures smooth data flow and computation.

### 2. Bitcoin Mining Module
* ✅ Iterates through multiple nonces to test different hashes in parallel.
* ✅ Three-phase hashing pipeline for double SHA-256 (required for Bitcoin mining).
* ✅ Efficient write-back system for storing computed hashes.

---

## ⚙️ System Workflow
1.  **SHA-256 Core:** Computes the initial hash of the message.
2.  **Nonce Processing:** Miner module appends a nonce and recomputes the hash.
3.  **Double SHA-256:** The hash is processed a second time for final validation.
4.  **Write-back:** Stores all computed hashes for evaluation.

---

## 🧪 Testbench Results
* ✅ Fully testbenched and passed all functional tests.
* ✅ Correct outputs verified for all tested nonces.
* ✅ Ready for FPGA implementation and further optimization.

### 🌟 Final Result: A+!
Good job team!

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
