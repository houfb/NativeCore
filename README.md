# NativeCore
一个轻量级、极简、高性能的前后端一体的开发框架，强调极简、统一、渐进、高效、原生、务实的设计理念。
A lightweight, Minimal, high-performance, native front-end and back-end framework emphasizing minimalism, semantic tags, and seamless integration for efficient web development.



 

---

## 概述 / Overview

NativeCore 拒绝黑盒与高大上，追求极简、统一、渐进、高效、原生、务实的设计理念。它推崇jQuery那种只做一个安静的工具库，不绑定你必须使用任何技术，你用我时，我是最锋利的利刃，你不用我时，我便毫不存在。它坚持原生的性能，这体现在方方面面，尤其是前端部分，它拒绝了vue与react，采用了原生HTML的开发范式，以及同样只安静做个工具库的jQuery做为默认技术栈，故而取名Native。它力求去除一切无实际价值的内容，保持本身的最小化和轻量化，只做最核心的工作，将自由留给开发者，故名Core，最终，我为他取名NativeCore,这名字很土，很技术范儿，但这质朴无华的名字与本身的风格也正好相映。




 
是一套基于极简编译器设计思想的前后端一体化框架，采用语义化组件和编程范式，专注于性能、结构清晰和代码易维护。它兼顾前端的灵活表达与后端的统一逻辑，适合全栈开发者使用。

NativeCore is a minimal full-stack framework driven by a compiler architecture that uses semantic components and programming paradigms focused on performance, clarity, and maintainability. It unifies frontend flexibility with backend consistency, designed for full-stack developers.

---

## Core Philosophy / 核心思想

- **编译器驱动**  
  通过静态编译实现代码精简，减少运行时开销，提高性能。  
  Compiler-driven: static compilation produces lean runtime code with minimal overhead.

- **语义化组件**  
  自定义语义标签与绑定，统一前后端表现，提升开发效率。  
  Semantic components: custom semantic tags with bindings unify frontend and backend behavior.

- **全栈一体**  
  前后端统一设计，减少前后不一致性与重复开发。  
  Full-stack integration: unified design reduces inconsistency and redundant work.

- **极简高效**  
  代码量小，依赖少，强调实用与易维护。  
  Minimal and efficient: small codebase, low dependencies, emphasizing practicality and maintainability.

- **渐近式无缝集成**  




它像jquery一样只安与任意无缝集成   原生Web语义与技术范式   重业务轻技术


---

## 编译器与编程范式 / Compiler and Programming Paradigm

- 静态分析与编译，将自定义语义标签转换为高效执行代码。  
  Static analysis and compilation transform semantic tags into efficient executable code.

- 支持声明式数据绑定、事件绑定和模板扩展。  
  Supports declarative data and event bindings, plus template extension.

- 组件化设计，支持组合和嵌套，便于构建复杂UI和逻辑。  
  Component-based design supports composition and nesting for complex UI and logic.

- 注重明确的语义表达，提升代码可读性与维护性。  
  Focus on clear semantic expression enhances readability and maintainability.

---

## 与其他框架对比 / Comparison with Other Frameworks

| 特性 / Feature             | NativeCore                                   | Vue.js                                   | React                                   | 原生JavaScript / Native JS               |
|--------------------------|---------------------------------------------|------------------------------------------|----------------------------------------|------------------------------------------|
| 设计理念 / Design         | 极简编译器驱动，语义组件，前后端一体化             | 渐进式框架，虚拟DOM，声明式数据绑定             | UI库，虚拟DOM，JSX组件                        | 原生API，命令式DOM操作                          |
| 运行时开销 / Runtime      | 极低，静态编译生成精简代码                         | 较高，依赖虚拟DOM和响应式系统                    | 较高，虚拟DOM差异和JSX运行时转译                   | 无框架开销，但开发复杂                            |
| 组件定义 / Component Def  | 语义化标签，内置行为与绑定                           | 单文件组件（模板+脚本+样式）                       | JSX组件                                    | 手写DOM及事件处理                                  |
| 前后端一致性 / Consistency | 前后端统一语义和组件模型                             | 主要前端框架，后端集成需额外工具                   | 主要前端库，需解决同构问题                          | 需自行设计架构                                    |
| 可扩展性 / Extensibility | 编译器可定制指令和模板，灵活扩展                         | 丰富插件生态                                   | 大型生态系统                                   | 灵活但需自行实现                                  |
| 体积大小 / Size          | 极小                                             | 较大                                        | 较大                                        | 无框架体积                                        |
| 学习曲线 / Learning Curve | 中等，需理解编译器与语义组件思想                         | 中等，易上手                                   | 中等，需掌握JSX和状态管理                            | 高，命令式开发繁琐                                  |
| 适用场景 / Use Cases     | 追求性能与结构简洁的全栈项目                           | 中大型SPA                                   | 复杂交互UI                                     | 简单页面或高性能底层需求                               |

---

## 主要功能 / Key Features

- 轻量级编译器，静态转换自定义标签  
- 统一的前后端语义组件模型  
- 声明式数据和事件绑定  
- 高性能、低运行时开销  
- 易于扩展和定制  
- 简洁且易维护的代码结构  

---

## 项目状态 / Project Status

当前处于初步稳定阶段，欢迎试用和反馈。示例和文档持续完善中。

Currently in a stable preliminary stage. Feedback and usage are welcome. Examples and documentation are under continuous improvement.

---

## 许可证 / License

采用 MIT 许可证，允许免费使用、修改和分发。

Licensed under MIT License, allowing free use, modification, and distribution.

