# 欢迎使用你的 Expo 应用 👋

本项目基于 [`create-expo-app`](https://www.npmjs.com/package/create-expo-app) 创建，核心运行时为 [Expo](https://expo.dev)。

## 快速开始

1. 安装依赖

   ```bash
   npm install
   ```

2. 启动应用

   ```bash
   npx expo start
   ```

在启动输出中，你可以选择以下方式运行应用：

- [Development Build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android 模拟器](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS 模拟器](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go)：用于快速体验的官方沙盒

开始开发时，请直接修改 **app** 目录中的文件；项目已启用 [基于文件的路由](https://docs.expo.dev/router/introduction)。

## 项目技术栈

- **框架与运行时**：Expo 54、Expo Router 6、React 19、React Native 0.81、TypeScript 5.9
- **导航与动画**：React Navigation（bottom-tabs、elements、native 等）、React Native Gesture Handler、React Native Reanimated、Safe Area Context、Screens
- **系统能力**：Expo Image、Expo Haptics、Expo Splash Screen、Expo System UI、Expo Web Browser 等模块
- **UI 体系**：Gluestack Style + Gluestack UI Themed，支持主题化组件开发
- **开发工具**：ESLint（expo 配置）、expo lint、tsconfig 预设

## 选装 UI 组件包

项目默认集成 Gluestack UI，可按需安装官方 CLI 或包：

- `npm install @gluestack-ui/button`：安装 Gluestack UI Button 组件，用于快速复用按钮样式
- `npm install @gluestack-ui/input`：提供输入框组件，支持主题和状态管理
- `npm install @gluestack-ui/modal`：获取模态框组件，适合弹窗、确认框场景
- `npx gluestack-ui add checkbox`：通过 CLI 自动拉取 Checkbox 组件模板，包含依赖配置

更多组件可在 [Gluestack UI 文档](https://gluestack.io/ui/docs/components) 中查看并按需添加。

## 重置示例代码

若需要重新开始开发，可运行：

```bash
npm run reset-project
```

该脚本会将示例代码移动到 **app-example** 目录，并创建一个全新的 **app** 目录供你编写业务代码。

## 了解更多

想进一步提升 Expo 开发效率，可阅读：

- [Expo 官方文档](https://docs.expo.dev/)：包含基础概念与进阶指南
- [Expo 教程](https://docs.expo.dev/tutorial/introduction/)：手把手构建可运行于 Android、iOS、Web 的全平台应用

## 加入社区

欢迎加入社区，与全球开发者一起打造跨平台体验。

- [Expo GitHub](https://github.com/expo/expo)：关注开源进展或参与贡献
- [Expo Discord](https://chat.expo.dev)：与其他开发者交流、提问
