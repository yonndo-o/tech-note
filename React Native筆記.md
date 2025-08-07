# 📱 React Native 前言介紹


React Native 是由 Facebook 推出的開源框架，用來打造 **跨平台的行動應用程式**，也就是同一套程式碼可同時在 iOS 和 Android 上運行。它的最大特色就是使用 **JavaScript（或 TypeScript）** 來開發原生 App，並依賴 React 的組件式架構。


## 🧠 開發語言與核心技術


- 使用 **JavaScript/TypeScript）** 為主要程式語言

- 建立於 **React** 的基礎上，採用元件化的 UI 架構

- 通過 **橋接（Bridge）機制** 與原生平台溝通（例如 iOS 的 Swift/Objective-C、Android 的 Kotlin/Java）


## 🧩 是否可使用 HTML 元件？


- React Native 並**不使用 HTML 或 CSS 本身**

- 它提供一套類似 HTML 樣式的元件，例如：

- `<View>` 類似 `<div>`

- `<Text>` 類似 `<p>` 或 `<span>`

- `<Image>` 類似 `<img>`

- 樣式設定使用 **CSS-like 的語法**（稱作 `StyleSheet`），但功能上與網頁 CSS 有些不同

- 雖然語法概念相近，但 React Native 的元件是直接轉譯成原生 UI 元件，不會渲染成 HTML 網頁內容


---


✨ 簡單來說，React Native 是用熟悉的 JavaScript 技術，寫出能跑在手機上的原生 App，而不是網站。所以如果你有 Web 前端的背景，學習 React Native 會覺得很親切，但也需要適應它與網頁開發之間的差異。


<br>

<br>

<br>


# 🧩 React Native 常用元件介紹


React Native 提供一系列「核心元件（Core Components）」可直接使用，這些元件是建構 UI 的基礎。除此之外，還有許多來自社群的「第三方套件元件」，可擴充功能與設計。


## 📦 常用核心元件（Core Components）


以下是 React Native 中最常見、最常用的元件：


| 元件名稱 | 功能簡介 |
|----------------|------------------------------------------|
| `View` | 最基本的容器元件，類似 HTML 的 `<div>` |
| `Text` | 顯示文字內容，類似 `<p>` 或 `<span>` |
| `Image` | 顯示圖片，類似 `<img>` |
| `TextInput` | 文字輸入框，類似 `<input type="text">` |
| `ScrollView` | 可滾動的容器，適合少量資料 |
| `FlatList` | 高效能列表元件，適合大量資料 |
| `SectionList` | 分組列表元件，適合分類資料 |
| `Button` | 基本按鈕元件 |
| `Modal` | 顯示彈出視窗 |
| `StyleSheet` | 定義樣式的工具，類似 CSS |


這些元件會直接轉譯成原生 UI 元件，因此效能與外觀都非常接近原生 App。


## 📚 官方元件與 API 文件


你可以在 React Native 官方網站查看完整的元件與 API 清單：


👉 [React Native 官方元件與 API 文件](https://reactnative.dev/docs/components-and-apis)


這裡會依照分類列出所有元件，包括：

- 基本元件

- UI 控制元件

- 平台專屬元件（Android / iOS）

- 其他輔助元件與 API


## 🧰 第三方元件與套件


除了官方元件，React Native 社群也提供了大量的第三方元件套件，例如：


| 套件名稱 | 功能簡介 |
|---------------------------|------------------------------------------|
| `react-native-vector-icons` | 提供大量圖示支援 |
| `react-native-paper` | Material Design UI 元件庫 |
| `react-native-elements` | 通用 UI 元件庫，支援主題與樣式客製化 |
| `react-native-maps` | 地圖元件，支援標記、路線等功能 |
| `react-native-gesture-handler` | 手勢操作支援 |


你可以在以下網站搜尋並探索所有可用的 React Native 套件：


👉 [React Native Directory](https://reactnative.directory/)


這個網站會列出所有熱門、最新、分類清楚的元件與套件，並提供安裝方式與範例。


---


✨ 如果你正在開發 App，可以先從核心元件開始，再根據需求選擇合適的第三方套件。需要我幫你推薦某類型的元件嗎？例如 UI 套件、動畫、地圖、聊天元件等等？


<br>

<br>

<br>


# 🧠 TypeScript 是什麼？


TypeScript 是由 Microsoft 開發的 **開源程式語言**，它是 JavaScript 的「超集」，也就是說所有合法的 JavaScript 程式碼在 TypeScript 中都能正常運作，但 TypeScript 增加了許多強大的功能，最重要的是 **靜態型別檢查**。


## 🔍 TypeScript 的核心特色


- **靜態型別系統**：可在編譯階段發現錯誤，提升程式碼安全性與可維護性。

- **型別推斷**：即使不明確指定型別，TypeScript 也能根據上下文自動判斷。

- **介面（Interface）與類別（Class）**：支援物件導向程式設計。

- **泛型（Generics）**：讓函式與類別更具彈性與可重用性。

- **模組化支援**：使用 `import` / `export` 來組織程式碼。

- **與 JavaScript 完全相容**：可逐步導入 TypeScript 到現有的 JS 專案中。


## 📚 官方學習資源


你可以在 TypeScript 官方網站找到完整的教學與文件：


👉 [TypeScript 官方文件](https://www.typescriptlang.org/docs/)

👉 [TypeScript 中文手冊](https://www.tslang.com.cn/docs/)


這些資源包含：

- 語法手冊

- 型別系統介紹

- 編譯器設定（tsconfig.json）

- 與 React、Node.js 等框架整合教學


---


✨ TypeScript 的設計理念是「讓 JavaScript 更安全、更強大」，特別適合中大型專案或多人協作的開發環境。接下來，我們將進一步探索 TypeScript 的 **基本語法與型別使用方式**，幫助你快速上手並理解它的實際應用。


<br>

<br>

<br>


# ⚓ React Hooks 總覽


React Hooks 讓函式型元件也能使用 React 的核心功能，包括狀態管理、生命週期、Context、Refs、效能優化等。


---


## ⛓ 內建 Hooks 分類


以下表格列出所有內建 Hooks 與其主要用途：


| 分類 | Hooks | 說明 |
|----------------|----------------------------------------------------------------|----------------------------------------------|
| 狀態 Hooks | `useState`、`useReducer` | 管理元件的可變資料；`useReducer` 適合複雜更新邏輯 |
| Context Hooks | `useContext` | 從上層 Context 取得並訂閱資料 |
| Refs Hooks | `useRef`、`useImperativeHandle` | 儲存不會觸發渲染的值（如 DOM 節點、計時器 ID） |
| Effect Hooks | `useEffect`、`useLayoutEffect`、`useInsertionEffect` | 處理副作用：網路請求、DOM 操作、外部 API 呼叫 |
| 效能 Hooks | `useMemo`、`useCallback`、`useTransition`、`useDeferredValue` | 緩存計算結果、優化函式、分流非同步更新優先級 |
| 其他 Hooks | `useDebugValue`、`useId`、`useSyncExternalStore`、`useActionState` | 主要供函式庫作者使用，調試或訂閱外部狀態 |


---


## 📚 官方文件連結


若要查看每個 Hook 的完整參考與範例，請前往官方 API 文件：

https://react.dev/reference/react/hooks


---


✨ 接下來，我們將從最常用的 `useState`、`useEffect` 開始，以範例實作帶你深入掌握各種 Hooks 的正確使用方式。


<br>

<br>

<br>


# 🌱 React Native 的 `useState` Hook


React Native 中的 `useState` Hook 提供了一種在函式元件內管理本地化狀態的簡易方式。

它允許你宣告一個狀態變數並取得對應的更新函式，隨時在元件中讀寫此值。


---


## 🧠 核心概念


`useState` 在初次呼叫時，為該元件建立一個專屬的狀態槽。

每次渲染時，`useState` 都會回傳當前的狀態值與更新函式。

當你使用更新函式並傳入新值後，React 會觸發重新渲染並反映最新狀態。


---


## ✅ `useState` 的優勢


- 簡易宣告：在函式元件中一次性完成狀態變數與更新函式的宣告

- 局部狀態：狀態只屬於該元件，避免全域汙染與不必要的重新渲染

- 清晰直觀：透過解構賦值一目了然地拿到狀態與更新函式


---


## 🔍 適用情境


- 管理表單欄位輸入值

- 控制元件顯示／隱藏（如 modal、dropdown）

- 跟蹤使用者互動次數、切換標籤索引等元件級別資料


---


## 🛠️ 最佳實踐


- 僅在元件內部使用 `useState` 管理與此元件強相關的狀態

- 避免在同一元件中宣告過多 `useState`，可考慮合併成單一物件狀態

- 當新狀態值依賴舊狀態時，使用函式型更新以確保值正確


---


## ⚠️ 常見陷阱


- 直接修改物件或陣列狀態需先複製再更新，否則無法觸發重新渲染

- 在迴圈或條件式內使用 Hook 會破壞呼叫順序，必須保證每次渲染都一致

- 誤將初始化值寫在函式內以為每次都會重新計算，實際僅首次渲染時計算


---


## 🔚 小結


`useState` 是 React Native 中最基礎的狀態管理工具，適合處理元件級別的簡單狀態。

掌握 Hook 規則並遵循最佳實踐，能讓函式元件既簡潔又高效。

在需求更複雜時，可考慮與 `useReducer`、Context 或第三方狀態管理工具結合使用。


<br>


```typescript

import React, { useState } from 'react';

import {

SafeAreaView,

StatusBar,

StyleSheet,

useColorScheme,

View,

Text,

TouchableOpacity,

} from 'react-native';


function App() {

const isDarkMode = useColorScheme() === 'dark';

const [showText, setShowText] = useState(false);

// showText 👉 目前的狀態值（這裡是布林值：是否顯示）

// setShowText 👉 改變 showText 的函式（你用它來更新狀態）

// useState(false) 👉 初始值是 false，代表一開始「不顯示文字」


const backgroundStyle = {

backgroundColor: isDarkMode ? '#1c1c1e' : '#f5f5f5',

flex: 1,

};


const textColor = {

color: isDarkMode ? '#f5f5f5' : '#1c1c1e',

};


return (

<SafeAreaView style={backgroundStyle}>

<StatusBar barStyle={isDarkMode ? 'light-content' : 'dark-content'} />

<View style={styles.container}>

<TouchableOpacity

style={styles.button}

onPress={() => setShowText(!showText)}

>

<Text style={styles.buttonText}>

{showText ? '隱藏文字' : '顯示文字'}

</Text>

</TouchableOpacity>

<TouchableOpacity

style={styles.button}

onPress={() => setShowText(true)}

>

<Text style={styles.buttonText}>

{'顯示文字'}

</Text>

</TouchableOpacity>

<TouchableOpacity

style={styles.button}

onPress={() => setShowText(false)}

>

<Text style={styles.buttonText}>

{'隱藏文字'}

</Text>

</TouchableOpacity>

{showText && (

<Text style={[styles.text, textColor]}>

這是 useState 控制的文字！

</Text>

)}

</View>

</SafeAreaView>

);

}


const styles = StyleSheet.create({

container: {

flex: 1,

justifyContent: 'center',

alignItems: 'center',

padding: 20,

},

button: {

backgroundColor: '#4a90e2',

paddingVertical: 12,

paddingHorizontal: 24,

borderRadius: 8,

marginBottom: 12,

},

buttonText: {

color: '#fff',

fontSize: 16,

fontWeight: '600',

},

text: {

marginTop: 20,

fontSize: 18,

},

});


export default App;


```


<br>

<br>

<br>


# 🌟 React Native 的 `useContext` Hook


React Native 中的 `useContext` Hook 提供了一種在元件樹中共享資料與狀態的簡潔機制。

它消除了多層 `props` 傳遞的繁瑣，讓開發者能專注於核心邏輯與 UI 呈現。


---


## 🧠 核心概念


`useContext` 透過一個全域的 Context 物件，將值注入到元件樹中。

元件只要訂閱此 Context，就能即時取得並更新共享資料。

這一機制不經過中間元件便能讓任意深度的子孫元件存取相同狀態。


---


## ✅ `useContext` 的優勢


- 單一來源：集中管理共享資料，避免多處同步問題

- 簡化結構：去除不必要的 `props` 鍊式傳遞，程式碼更清爽

- 即時更新：狀態改變時，自動觸發訂閱元件的重新渲染


---


## 🔍 適用情境


- 全域主題切換（如淺色 / 深色模式）

- 使用者認證資訊在多處元件中顯示或檢查

- 跨多個頁面或元件共享設定與偏好


---


## 🛠️ 最佳實踐


- 只在真正需要跨層級存取時使用，不要將所有狀態都搬到 Context

- 以功能劃分 Context，避免一個 Context 承載過多職責

- 搭配 `useMemo` 或 `useCallback` 降低不必要的重新渲染


---


## ⚠️ 常見陷阱


- 過度使用 Context 會造成元件更新範圍過大，影響效能

- 直接在 Context 中存放複雜物件，可能導致參考位址頻繁改變

- 忘記拆分 Context，導致某些狀態改變時，無關元件也被重渲染


---


## 🔚 小結


`useContext` 是 React Native 中管理跨元件資料的輕量解法。

妥善規劃與使用能大幅改善程式結構與維護性，卻也需留意效能和責任邊界。

當你的應用需要多個元件共享相同狀態時，`useContext` 絕對值得一試！


<br>


```typescript

import React, { createContext, useContext, useState } from 'react';

import {

StatusBar,

StyleSheet,

View,

Text,

Button,

} from 'react-native';


// 🎯 建立 Context

const ThemeContext = createContext({

isDarkMode: false,

toggleTheme: () => {},

});

// createContext(...) 👉 建立一個全域狀態容器（主題用）

// isDarkMode: false 👉 預設值是「淺色模式」

// toggleTheme: () => {} 👉 預設是個空函式，日後你會提供一個「切換模式」的功能


// 🚀 提供者組件

const ThemeProvider = ({ children }: { children: React.ReactNode }) => {

const [isDarkMode, setIsDarkMode] = useState(false);

const toggleTheme = () => setIsDarkMode((prev) => !prev);


return (

<ThemeContext.Provider value={{ isDarkMode, toggleTheme }}>

{children}

</ThemeContext.Provider>

);

};


function AppContent() {

const { isDarkMode, toggleTheme } = useContext(ThemeContext);


// 🎨 根據主題設定背景與文字顏色

const backgroundColor = isDarkMode ? '#1c1c1e' : '#f2f2f7';

const textColor = isDarkMode ? '#ffffff' : '#000000';


return (

<View style={[styles.container, { backgroundColor }]}>

<StatusBar barStyle={isDarkMode ? 'light-content' : 'dark-content'} />

<Text style={[styles.text, { color: textColor }]}>

當前模式：{isDarkMode ? '🌙 暗色模式' : '☀️ 亮色模式'}

</Text>

<Button title="切換主題" onPress={toggleTheme} color={isDarkMode ? '#ff9500' : '#007aff'} />

</View>

);

}


function App() {

return (

<ThemeProvider>

<AppContent />

</ThemeProvider>

);

}


const styles = StyleSheet.create({

container: {

flex: 1,

paddingHorizontal: 24,

paddingVertical: 40,

justifyContent: 'center',

alignItems: 'center',

},

text: {

fontSize: 20,

marginBottom: 20,

fontWeight: '600',

},

});


export default App;

```


<br>

<br>

<br>


# 📱 React Native + TypeScript 樣式套用方式指南


在使用 React Native + TypeScript 時，套用樣式有幾種常見且好用的方式。以下整理各種方式及其適用情境。


---


## ✅ 使用 `StyleSheet.create` 搭配型別定義


```tsx

import React from 'react';

import { StyleSheet, Text, View, StyleProp, TextStyle, ViewStyle } from 'react-native';


const styles = StyleSheet.create({

container: {

padding: 12,

backgroundColor: '#eef',

} as ViewStyle,

title: {

fontSize: 18,

color: '#333',

} as TextStyle,

});


const App = () => (

<View style={styles.container}>

<Text style={styles.title}>Hello TypeScript</Text>

</View>

);


export default App;

// ✅ 優點：有型別提示，IDE 支援佳。

```


<br>


## 🧾 使用內嵌樣式（Inline Style）

```typescript

<View style={{ padding: 10, backgroundColor: 'lightgray' }}>

<Text style={{ fontSize: 20, color: 'teal' }}>Inline Style</Text>

</View>

// ✅ 適用：小範圍樣式或動態樣式。

```


<br>


## 🧩 使用陣列組合樣式

```typescript

const baseText: TextStyle = {

fontSize: 16,

color: 'black',

};


const emphasized: TextStyle = {

fontWeight: 'bold',

};


<Text style={[baseText, emphasized]}>Array Merged Style</Text>

// ✅ 適用：重複樣式組合、多條件樣式。

```


<br>


## 🎯 根據條件套用樣式

```typescript

const isDarkMode: boolean = true;


<Text style={isDarkMode ? { color: 'white' } : { color: 'black' }}>

Conditional Style

</Text>

// ✅ 適用：主題切換、狀態控制樣式。

```


<br>


## 🌀 搭配 styled-components（第三方樣式工具）

```typescript

import styled from 'styled-components/native';


const Container = styled.View`

padding: 16px;

background-color: papayawhip;

`;


const StyledText = styled.Text`

font-size: 18px;

color: navy;

`;


const App = () => (

<Container>

<StyledText>Styled Components</StyledText>

</Container>

);

// ✅ 優點：CSS-like 語法，支援動態 props。

```


<br>


## 🌪️ 使用 Tailwind 風格工具（如 NativeWind）

```typescript

import { View, Text } from 'react-native';

import { tw } from 'nativewind';


<View style={tw`p-4 bg-indigo-200`}>

<Text style={tw`text-xl text-indigo-900`}>Tailwind with NativeWind</Text>

</View>

// ✅ 優點：簡潔語法，類似網頁開發體驗。

```


<br>


## 🔐 類型安全建議

```typescript

type Props = {

style?: StyleProp<ViewStyle>;

};

// 這樣可以讓元件在傳遞 style 時具有完整的型別安全。

```
