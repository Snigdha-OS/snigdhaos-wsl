# Snigdha OS | Win-Kex
Credit: 
 - Author: [Kali Linux](https://kali.org)
 - Source Code: [Kali Linux - Gitlab](https://gitlab.com/kalilinux/packages/kali-win-kex/-/tree/kali/master?ref_type=heads)

> I have adopted this code for Snigdha OS WSL

# Snigdha OS WSL Distribution 🌐  

Welcome to the **Snigdha OS WSL** repository! This project provides the tools and configuration needed to build and distribute Snigdha OS for the Windows Subsystem for Linux (WSL).  



## 📖 What is Snigdha OS WSL?

Snigdha OS WSL enables users to run Snigdha OS seamlessly within Windows using WSL. With this, you can enjoy the power of Snigdha OS without leaving the comfort of your Windows environment.



## 🚀 Features  

- **Lightweight and Fast**: Enjoy the efficiency of Snigdha OS on your Windows system.  
- **Customizable**: Modify and enhance the WSL distribution to fit your needs.  
- **Seamless Integration**: Access Snigdha OS utilities alongside Windows tools.  



## 📂 Repository Structure  

- **`scripts/`**  
  Contains scripts to automate the build and configuration process.  

- **`config/`**  
  Configuration files for the WSL environment.  

- **`dist/`**  
  Generated WSL files and distributions.  

- **`docs/`**  
  Documentation and guides related to Snigdha OS WSL.  



## 🔧 How to Use  

### 1. Clone the Repository  
```bash
git clone https://github.com/snigdha-os/snigdhaos-wsl.git
cd snigdhaos-wsl
```

### 2. Build the WSL Distribution  
Run the build script to create the WSL root filesystem:  
```bash
bash scripts/build.sh
```

This will generate a `.tar.gz` file in the `dist/` directory.

### 3. Import into WSL  
Use the following command to import Snigdha OS into WSL:  
```bash
wsl --import SnigdhaOS <install-location> dist/snigdhaos-wsl.tar.gz
```

Example:
```bash
wsl --import SnigdhaOS "C:\WSL\SnigdhaOS" dist/snigdhaos-wsl.tar.gz
```

### 4. Launch Snigdha OS in WSL  
Start Snigdha OS by running:  
```bash
wsl -d SnigdhaOS
```



## 🤝 Contributing  

We welcome contributions from the community! To get started:  

1. Fork the repository.  
2. Create a feature branch.  
3. Submit a pull request with your changes.  

Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.



## 🛠️ Issues  

Found a bug or have a feature request? Open an issue [here](https://github.com/snigdha-os/snigdhaos-wsl/issues).  



## 📄 License  

This project is licensed under the [MIT License](LICENSE).  



## 🌟 Join the Community  

- **Website**: [Snigdha OS](https://snigdha-os.org)  
- **Open Collective**: [Support Us](https://opencollective.com/snigdha-os)  
- **Forums**: [Community Discussions](https://community.snigdha-os.org)  



Thank you for choosing Snigdha OS for WSL! 🐧✨