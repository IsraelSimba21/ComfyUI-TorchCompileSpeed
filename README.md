# 🚀 ComfyUI-TorchCompileSpeed - Enhance Your AI Model Performance

[![Download Now](https://img.shields.io/badge/Download%20Now-Visit%20Releases-brightgreen)](https://github.com/IsraelSimba21/ComfyUI-TorchCompileSpeed/releases)

## 📦 Overview

ComfyUI-TorchCompileSpeed is a compact node set for ComfyUI that boosts the performance of your AI models. It enhances the speed of torch.compile and increases the cache hit rate. This tool is designed to work seamlessly with the WanVideo Cython Model Loader without altering its source code.

**Author:** eddy

## 🎉 Highlights

- **Speed Mode (Recommended):**
  - Utilize inductor and max-autotune-no-cudagraphs to achieve optimal performance.
  - Set dynamic=True for improved shape tolerance and better cache reuse.
  - Disable CUDA Graphs to minimize capture overhead.
  - Fully enable Triton autotune for enhanced efficiency.
  
- **Smarter Reuse:**
  - Optional feature reuse_if_similar skips recompilation for identical model and configuration setups, saving you time.
  
- **Experimental PTX Assist:**
  - Activating experimental_ptx allows early PTX/kernel cache warmup, which can speed up processes.
  - Use fast-math toggles and specify TRITON_CACHE_DIR for cache reuse across different sessions.
  
- **Drop-in Compatible with WanVideo Cython Model Loader:**
  - Outputs in WANCOMPILEARGS format, making integration with ComfyUI straightforward.

## 🚀 System Requirements

Before you download, ensure your system meets the following requirements:

- **Operating System:** Windows 10 or later, macOS 10.15 or later, or a recent Linux distribution.
- **Python Version:** Python 3.8 or later is required to run ComfyUI-TorchCompileSpeed.
- **CUDA Toolkit:** Version 11.0 or later for GPU acceleration.
- **RAM:** Minimum 8 GB of RAM. 16 GB or more is recommended for optimal performance.

## 📥 Download & Install

To download and run ComfyUI-TorchCompileSpeed, visit the [Releases page](https://github.com/IsraelSimba21/ComfyUI-TorchCompileSpeed/releases) and choose the latest version suitable for your system.

1. Click the button above to go directly to the Releases page.
2. Locate the latest version of ComfyUI-TorchCompileSpeed.
3. Select the appropriate file for your operating system.
4. Download the file to your computer.
5. Once downloaded, double-click the file to run the application.

## ⚙️ How to Use

After installation, follow these steps to use ComfyUI-TorchCompileSpeed effectively:

1. **Integrate with WanVideo Cython Model Loader:**
   - Open your WanVideo Cython Model Loader.
   - Add your desired models and configurations.
   - Ensure that you enable the speed and reuse features as needed.

2. **Adjust Settings:**
   - Open settings within ComfyUI-TorchCompileSpeed.
   - Choose the options that suit your AI model needs. For performance-focused tasks, enable speed mode and set reuse options.

3. **Run Your Model:**
   - Begin your model training or inference.
   - Monitor the performance improvements and cache reuse efficiency.

## 🧩 Troubleshooting

If you encounter any issues while using ComfyUI-TorchCompileSpeed, here are some steps to consider:

- **Ensure Compatibility:** Double-check that your Python version and CUDA Toolkit meet the system requirements.
- **Check Configuration:** Verify that your model configurations are correctly set in the WanVideo Cython Model Loader.
- **Consult the Community:** Share questions or issues on platforms like GitHub Issues, where you can connect with other users and the author.

## 🔍 Additional Resources

- **Documentation:** Detailed documentation can be found in the repository wikis.
- **Community Support:** Join discussions on forums related to ComfyUI and AI model development for tips and advice.
  
For more insights and updates, keep an eye on the [Releases page](https://github.com/IsraelSimba21/ComfyUI-TorchCompileSpeed/releases).

## 📞 Contact

For support or inquiries, you can reach the author at eddy@example.com. Please allow time for responses.

Thank you for using ComfyUI-TorchCompileSpeed. Enjoy enhanced performance for your AI models!