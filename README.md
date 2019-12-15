### 桌面端生成容器

#### 安装
- 1. npm install / yarn install / cnpm install(推荐使用cnpm  比较快)

#### 使用
- 1. 把打包好的 dist 文件夹 或者 build 文件夹放到根目录
- 2. 修改 main.js (找到 '修改这里') 更换路径
- 3. 预览 npm run start （如果出现白屏，请查看你打包的项目路径是否正确）


#### 打包生成 桌面端
- mac: npm run build:mac
- win: npm run build:win
- 你也可以直接运行 npm run build，但是命令会自动查看你的系统，例如使用的是macOS,打包出来的就只有 dmg
- 如果运行 打包win时候遇到报错，而且你用的 mac 运行，请把项目移到 windows 系统里运行。