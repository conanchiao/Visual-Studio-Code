- **转换PDF失败**  
可能是**配置环境**的问题
```Extension Settings
markdown-pdf.executablePath
- Path to a Chromium or Chrome executable to run instead of the bundled Chromium
- All `\` need to be written as `\\` (Windows)
- To apply the settings, you need to restart Visual Studio Code
"markdown-pdf.executablePath": "C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe"
```
**解决办法**  
1. 在设置中搜索markdown-pdf.executablePath
2. 配置环境，添加  
```
"markdown-pdf.executablePath": "C:\\Users\\Conan\\AppData\\Local\\Google\\Chrome\\Application\\chrome.exe"
```  
*文件的路径获取*：`shift+右键`，`复制为路径`  
 3. 如果仍旧错误，则删去添加的内容

