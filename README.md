Bitcoin Hash Accelerator - Team KARNA_ASADA

👥 Team Members & Contributions
🛠 Genaro Salazar Ruiz & Jay Paek – Developed the SHA-256 hashing module, optimizing message scheduling and hash computation.
⚡ Hussein Alramadan & Preston Le – Designed the Bitcoin miner, integrating nonce iteration, multi-phase hashing, and final hash validation.
🛠 Project Components
1️⃣ SHA-256 Hashing Core
✅ Implements hardware-accelerated SHA-256, processing 512-bit message blocks.
✅ Optimized bitwise operations and message expansion for FPGA efficiency.
✅ FSM-based control logic ensures smooth data flow and computation.

2️⃣ Bitcoin Mining Module
✅ Iterates through multiple nonces to test different hashes in parallel.
✅ Three-phase hashing pipeline for double SHA-256, required for Bitcoin mining.
✅ Efficient write-back system for storing computed hashes.

⚙️ How It Works
1️⃣ SHA-256 Core: Computes the initial hash of the message.
2️⃣ Nonce Processing: Miner module appends a nonce and recomputes the hash.
3️⃣ Double SHA-256: Hash is processed again for final validation.
4️⃣ Write-back: Stores all computed hashes for evaluation.

🧪 Testbench Results
✅ Fully testbenched and passed all functional tests.
✅ Correct outputs verified for all tested nonces.
✅ Ready for FPGA implementation and further optimization.

Final Result: A+ !!!!, good job team!
