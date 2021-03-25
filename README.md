# cra_webpack_optimization

记录create-react-app webpack打包优化过程

1. 覆盖配置，使用customize-cra

2. 添加gzip压缩，使用compression-webpack-plugin

3. 关闭source-map，使用cross-env，react-app-rewired，在package.json中使用cross-env GENERATE_SOURCEMAP=false关闭

4. 添加antd按需加载，使用fixBabelImports

5. 添加编译进度条，使用process-bar-webpack-plugin

6. 添加查看包大小插件，使用webpack-boundle-analyzer