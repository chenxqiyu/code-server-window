Node v16 or higher
run:

.bin/code-server.cmd

code-server: v4.12.0

版本: 1.77.3

提交: 704ed70d4fd1c6bd6342c436f1ede30d1cff4710

日期: 2023-04-13T18:36:32.554Z

浏览器: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36
## 如何在window编译最新版本步骤如下

根据您提供的步骤，以下是在 Windows 上编译最新版本的 `code-server` 的步骤：

1. **下载 Node.js 18 编译版本**：
   下载 Node.js 18 编译版本的压缩文件，您提供的链接为：
   [Node.js 18.19.1 Windows x64](https://cdn.npmmirror.com/binaries/node/v18.19.1/node-v18.19.1-win-x64.zip)

2. **安装 Git**：
   在您的系统上安装 Git。您可以从 [Git 官网](https://git-scm.com/) 下载并安装。

3. **打开 Git Bash**：
   在下载的 Node.js 18 编译版本的解压目录下，通过鼠标右键点击空白处，选择 "Open Git Bash Here"。

4. **设置代理（可选）**：
   如果您需要通过代理加快下载速度，可以在 Git Bash 中执行以下命令：
   ```bash
   ./npm.cmd config set proxy http://127.0.0.1:10809
   ```

5. **安装 code-server**：
   在 Git Bash 中执行以下命令来安装 code-server：
   ```bash
   ./npm.cmd install code-server --unsafe-perm
   ```

6. **安装完成**：
   安装完成后，您可以在程序目录路径 `node-v18.19.1-win-x64\node_modules\.bin` 找到 code-server 的可执行文件。

7. **启动 code-server**：
   您可以通过命令行启动 code-server，例如：
   ```bash
   ./node-v18.19.1-win-x64/node_modules/.bin/code-server.cmd
   ```

8. **访问 code-server**：
   打开浏览器，并在地址栏输入 `http://localhost:8080`，即可访问 code-server 的 Web 页面。

![Snipaste_2024-03-11_17-25-13](https://github.com/chenxqiyu/code-server-window/assets/10222853/3aa48494-a819-44bd-94e1-3a67e830b6cf)
