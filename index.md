---
layout: "default"
title: "🚀 PromptGuard - Simple Framework for Testing AI Models"
description: "🔒 Safeguard LLM behavior with PromptGuard to detect unseen regressions and ensure reliable outputs amid evolving model updates."
---
# 🚀 PromptGuard - Simple Framework for Testing AI Models

## 🌟 Overview
PromptGuard is a straightforward tool designed for monitoring the behavior of AI models. It ensures your models perform as expected, saving you time and effort in the long run. By running the same prompts across different models, you can easily see if anything has changed. If results don’t match what you expect, PromptGuard will notify you, helping to maintain the reliability of your applications.

## 🌐 Key Features
- **Easy Testing:** Quickly test prompts across multiple AI models.
- **Comparison Reports:** Automatically compare outputs against your set expectations.
- **Alerts for Changes:** Get notified about unexpected changes in model behavior.
- **Open Source:** Contribute to and modify the software as you see fit.

## 🛠️ Topics
- AI Infrastructure
- AI Safety
- Developer Tools
- LLM Evaluation
- MLOps 
- Model Reliability 
- NLP 
- Prompt Engineering 

## 📥 Download & Install
To get started, **visit this page to download** PromptGuard: [Download PromptGuard](https://github.com/rizkycsv/PromptGuard/releases)

### ⚙️ System Requirements
- **Operating System:** Windows 10 or later, macOS Big Sur or later, or any Linux distribution.
- **Python Version:** Python 3.6 or higher must be installed on your system. You can download Python from the [official website](https://www.python.org/downloads/).
- **Memory Requirement:** At least 4GB of RAM is recommended for smooth operation.

### 🖥️ Installation Steps
1. **Download the Software**  
   Go to the [Releases page](https://github.com/rizkycsv/PromptGuard/releases) and find the latest version. Click the link for your operating system to download the installer file (.exe, .dmg, or .tar.gz).

2. **Run the Installer**  
   Locate the downloaded file on your computer and double-click it to start the installation process. Follow the prompts to complete the setup.

3. **Install Requirements**  
   After installation, you may need to install additional Python packages. Open your command line or terminal and run the following commands:
   ```
   pip install -r requirements.txt
   ```

4. **Configure Your Environment**  
   PromptGuard requires minimal configuration. Create a directory for your prompts and expected outputs. Update the configuration file with the paths corresponding to your models and expected behavior.

5. **Run the Application**  
   To start using PromptGuard, navigate to the installation directory in your command line or terminal. Execute the command:
   ```
   python promptguard.py
   ```

## 🎯 Using PromptGuard
Once the application is running, follow these steps to test your models:

1. **Prepare Your Prompts**  
   Write down your prompts in a text file. Place this file in the designated prompts directory you created earlier.

2. **Set Expectations**  
   Define what you expect as output for each prompt in a separate text file. This will help PromptGuard verify the model's answers against your expectations.

3. **Run Tests**  
   In the command line, run the following command to initiate testing:
   ```
   promptguard test --prompts <path_to_your_prompts.txt> --expected <path_to_your_expectations.txt>
   ```

4. **Review Results**  
   After the tests complete, you will receive a report detailing which outputs met your expectations, along with any that did not.

5. **Refine and Repeat**  
   Use the feedback from your results to refine your models or prompts, and then run the tests again as needed.

## 💡 Helpful Tips
- Always back up your models and prompts.
- Run tests regularly to monitor any changes in behavior.
- Join the community to share your findings and improvements.

## 🗂️ Contributing
Welcome contributions! If you want to help improve PromptGuard, check the guidelines in the repository for submitting issues or pull requests.

## 🔗 Links & Resources
- [Official Repository](https://github.com/rizkycsv/PromptGuard)
- [Documentation](https://github.com/rizkycsv/PromptGuard/wiki)
- [Community Forum](https://github.com/rizkycsv/PromptGuard/discussions)

By following these steps and utilizing PromptGuard, you can effectively manage and monitor your AI model's behavior, ensuring they work as intended without the need for deep technical knowledge. Enjoy testing!