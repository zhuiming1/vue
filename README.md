# vue
个人博客
# 克隆项目
git clone https://github.com/zhuiming1/vue

# 推荐使用 yarn, 安装依赖基本上一次过,npm 经常会卡在node-sass,如果npm安装node-sass 失败,单独多安装几次应该就可以了: npm i node-sass -D

# 设置淘宝镜像
yarn config set registry https://registry.npm.taobao.org/
or
npm config set registry https://registry.npm.taobao.org



# 安装依赖 (16版本及之上的node会报错，推荐14)
yarn  or  yarn install
or
npm install


# 启动项目 (已经配置好启动服务自动打开浏览器，如果没自动打开按照控制台输出的地址自己打开)
# 如果eslint语法检查报错，直接关掉eslint语法检查
yarn dev
or
npm run dev

# 启动单元测试
yarn  unit
or
npm run unit

# 启动端到端测试
yarn e2e
or
 npm run e2e

# 启动编译打包 生产环境
yarn build
or
 npm run build

# 启动编译打包 并生成打包结果 生产环境
yarn analyz
or
npm run analyz

# 抽取分离公共依赖
yarn startdll
or
npm run startdll
