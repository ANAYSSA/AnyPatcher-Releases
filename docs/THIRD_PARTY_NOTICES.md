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
- Official OpenAI Codex CLI 0.163.0 — Apache-2.0, with upstream NOTICE. The architecture-matched CLI and its adjacent codex-code-mode-host runtime are bundled. Optional voice components and external host tools are not included.
- Dzip CLI 0.4.3 with dzip-archive 0.5.1 — AGPL-3.0-or-later. This is an independent command-line executable, invoked as a separate process; its code is not linked into AnyPatcher. The complete corresponding source, Cargo dependencies, license texts, documented extraction-limit changes and offline rebuild instructions accompany the executable in `notices/dzip/dzip-cli-0.4.3-anypatcher-sources.tar.gz`. The archive contains only Dzip and its dependencies. Upstream: [dzip-tools](https://github.com/LambdaEd1th/dzip-tools) at `8f782db7ebb7174d99332e23b0973ee55ac527a8`, [dzip-archive](https://github.com/LambdaEd1th/dzip-archive) at `8881b55eba64ad56c8430979227a591a72b925fb`. Users can select a different compatible CLI build in external-tool settings.

License texts available in the installed packages are collected into the application's `notices` resources during packaging. Build-only dependencies may also appear in that collection.

Ghidra, JADX, Apktool, Android SDK tools and Ollama are not redistributed in the DMG. Users obtain them from their respective upstream projects. FMOD toolkit and pyfmodex modules are excluded from the bundled analyzer; audio decoding is not offered in this release.

The generated educational fixtures and logo are original AnyPatcher materials. No commercial application resources, private keys or external AI models are included.
