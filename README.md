# Srihari Kanakaraj

CS undergrad at VIT Chennai ('27). I work on GPU compilers and ML systems, from the PTX a kernel compiles to up to the platforms that serve models.

**Now:** contributing to LLVM's NVPTX backend
- [[NVPTX] Lower atomics on local memory to non-atomic operations](https://github.com/llvm/llvm-project/pull/236376)
- [[NVPTX] Use target nodes for clz.b64 and popc.b64](https://github.com/llvm/llvm-project/pull/236435): fixes a 64-bit `ctlz` miscompile

**Before:** software engineering intern at HPE (cloud infrastructure and AI platforms) · generative AI intern at MedxAI (chest X-ray AI deployed at Apollo Hospitals) · quantum ML research intern at VIT

## Projects

- **[kc-ptx-compiler](https://github.com/sriharinmn/kc-ptx-compiler)**: a GPU kernel compiler written from scratch in C++17 that emits NVIDIA PTX. It matches nvcc on 7 benchmark kernels, its random tester found a ptxas `-O3` miscompile, and it runs in the browser through WebAssembly.
- **[veritas](https://github.com/sriharinmn/veritas)**: extracts grounded facts from financial PDFs, links each one to the exact words on its source page, and works out whether facts across documents corroborate, contradict, or only appear to disagree.
- **[business-entity-resolution](https://github.com/sriharinmn/business-entity-resolution)**: our Amazon ML Challenge 2026 entry. It links about 10M noisy business records to a 2M-business reference across three countries, one of them unseen in training, and scored 0.983 macro F0.5 on the public leaderboard.
- **[securewipe](https://github.com/sriharinmn/securewipe)**: a disk wiper for Linux and Windows using NIST SP 800-88 and DoD 5220.22-M passes, with HPA/DCO handling and JSON/PDF wipe certificates.
- **[LogAin](https://github.com/sriharinmn/LogAin)**: an incident assistant for telecom NOCs. A classifier predicts the root cause, and RAG writes the remediation report.

[LinkedIn](https://www.linkedin.com/in/srihari-kanakaraj)
