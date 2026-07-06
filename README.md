# 畅言 App

基于 React Native + Expo 开发的移动应用，封装 web.rvtqh.com 网站。

## 开发

```bash
npm install
npx expo start
```

## 构建（由 Expo 云端完成）

- Android APK: `npx eas build --platform android --profile preview`
- iOS IPA (云端): `npx eas build --platform ios --profile preview`

## 配置

- `app.json` - Expo 项目配置
- `eas.json` - EAS Build 配置
- `App.js` - 主入口（WebView 封装）
