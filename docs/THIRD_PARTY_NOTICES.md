# Third-party components

AnyPatcher's original source is proprietary. Dependencies retain their original licenses.
Exact Python and JavaScript versions are recorded in `requirements-lock.txt` and `package-lock.json`; Rust versions are in `src-tauri/Cargo.lock`.

Principal runtime components:

- Tauri / Wry / Tao — MIT or Apache-2.0.
- React / React DOM — MIT.
- Lucide — ISC, with applicable icon attribution.
- Python — PSF license.
- PyInstaller — GPL-2.0-or-later with the bootloader distribution exception.
- UnityPy — MIT.
- LIEF — Apache-2.0.
- Capstone — BSD-3-Clause, with component notices.
- cryptography — Apache-2.0 or BSD-3-Clause.
- defusedxml — PSF license.
- HTTPX — BSD-3-Clause.
- keyring — MIT.
- Pillow — HPND.
- SQLite — public domain.
- Official OpenAI Codex CLI 0.163.0 — Apache-2.0, with upstream NOTICE. Only the architecture-matched CLI binary is bundled; optional voice and code-mode host components are not included.

License texts available in the installed packages are collected into the application's `notices` resources during packaging. Build-only dependencies may also appear in that collection.

Ghidra, JADX, Apktool, Android SDK tools and Ollama are not redistributed in the DMG. Users obtain them from their respective upstream projects. FMOD toolkit and pyfmodex modules are excluded from the bundled analyzer; audio decoding is not offered in this release.

The generated educational fixtures and logo are original AnyPatcher materials. No commercial application resources, private keys or external AI models are included.
