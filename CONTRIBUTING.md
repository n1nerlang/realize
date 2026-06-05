# Contributing to Realize

Thank you for your interest in improving **Realize**. To keep this project performant and minimalist, please follow these guidelines when submitting pull requests.

## Code Standards
*   **No Legacy Anchors:** Do not use `anchor_from` or `anchor_to` in UI JSON files. Use `offset` and `size` relative positioning only.
*   **Minimalist Aesthetic:** All new textures must adhere to the 4-tone flat ramp rule. No noise, no dithering, and no compression.
*   **Performance First:** Avoid excessive UI layering. If a change increases draw calls, please document why it is necessary.
*   **Clean JSON:** Ensure your JSON is formatted correctly with 2-space indentation. No trailing commas.

## How to Contribute
1.  **Fork the repository** to your own GitHub account.
2.  **Create a feature branch** for your specific change (e.g., `fix/inventory-spacing` or `feat/hotbar-cleanup`).
3.  **Test your changes:** Ensure the UI scales correctly on both mobile and PC environments.
4.  **Submit a Pull Request (PR):** Describe exactly which UI element you are modifying and why the current approach is inefficient.

## License
By contributing to Realize, you agree that your contributions will be licensed under the [MIT License](LICENSE).

---
*Questions? Open an issue and let's discuss.*
