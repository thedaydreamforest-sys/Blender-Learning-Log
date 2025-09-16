# Blender Learning Log — Day 1: Interface, Basic Operations, and Core Concepts

**Updated:** 2025-09-16  
**Study Duration:** 2h  

---

## 1. Introduction to Blender Interface
1. **Startup Interface**  
   When opening Blender, the welcome screen appears, allowing you to create a new file, open an existing file, or click outside to close it.  

2. **Main Work Areas**  
   - **Menu Bar**: Located at the top, similar to other software.  
   - **Tabs**: Such as Layout, Modeling, representing different work modes or scenes.  
   - **Tool Shelf**: On the left, contains tools for moving, rotating, and scaling objects.  
   - **3D Viewport**: The large central area, used for building and observing the scene.  
   - **Outliner**: Top-right corner, lists all objects in the scene (e.g., camera, cube, lights).  
   - **Properties Editor**: Right side, displays detailed settings for the selected object or tool.  
   - **Timeline**: Bottom, used for animation.  

3. **Interface Management & Customization**  
   - Panels are **replaceable**: Click the top-left icon of any panel to switch its function.  
   - Panels can be **split or merged**: Drag panel edges, and when a white plus appears, split or merge.  
   - **Maximize Panel**: `Ctrl + Space`  
   - **Reset Default Layout**: Create a new Layout and delete the previous one.  

---

## 2. Core Elements of 3D Creation
Blender’s default scene contains three essential elements:  
- **Model**: e.g., Cube, representing the physical object in the scene.  
- **Light**: Illuminates the scene, creating shadows and highlights.  
- **Camera**: Determines the final rendered view and framing.  

---

## 3. Basic 3D Workflow
No matter how complex the project is, the core workflow follows:  
1. **Modeling**: Create and shape 3D objects.  
2. **Shading & Lighting**: Apply materials and set up lights; these two steps often influence each other.  
3. **Rendering**: Convert the 3D scene into a 2D image or animation.  

---

## 4. View Navigation (Essential Foundation)
- **Rotate View**: Middle mouse button drag  
- **Pan View**: Shift + Middle mouse button drag / Use “Hand” tool in toolbar  
- **Zoom View**: Mouse wheel / Use “Magnifier” tool  
- **Switch Perspective/Orthographic**: Numpad `5` or the top-right viewport button  
- **Camera View**: Numpad `0`  

---

## 5. Object (Model) Control
### 1. Selecting Objects
- Box Select: Drag to select multiple objects  
- Cursor Tool: Click to select a single object  
- Circle Select: `C`  
- Lasso Select: Draw custom selection area  

### 2. Transforming Objects
- **Move**: `G` → Constrain to axis: `G + X/Y/Z`  
- **Rotate**: `R` → Constrain to axis: `R + X/Y/Z`  
- **Scale**: `S` → Constrain to axis: `S + X/Y/Z`  
- **Reset Transform**: `Alt + G` (position), `Alt + R` (rotation), `Alt + S` (scale)  

### 3. Other Operations
- **Delete**: `Delete` or `X`  
- **Add New Object**: `Shift + A`  
- **Hide/Show Objects**: `H` / `Alt + H` / `Shift + H`  
- **Outliner Visibility**: Click the eye icon  
- **Duplicate Object**: `Shift + D`  

---

## 6. View Switching (Multi-angle Observation)
- **Gizmo**: Click axes to quickly switch views  
- **Numpad Views**:  
  - `1` Front  
  - `3` Right  
  - `7` Top  
  - `9` Opposite of current view  
  - `2/4/6/8` Rotate view 15° increments  
- **Tilde (~) Menu**: Opens view shortcut menu  

---

## 7. Four Core Concepts
### 1. 3D Cursor
- Red-and-white circle in the scene  
- **Functions**: Object creation point, quick positioning, pivot for transforms  
- **Operations**:  
  - Move: Shift + Right-click  
  - Reset: Shift + C  
  - Snap: Shift + S menu (Object to Cursor / Cursor to Object)  

### 2. Object Origin
- Yellow dot representing an object’s transform (position, rotation, scale)  
- Rotation and scaling occur around the origin by default  
- Can edit in **“Affect Only Origin”** mode  

### 3. Pivot Point
- Center of rotation or scaling  
- Modes: Bounding Box Center / Median Point / Individual Origins / 3D Cursor / Active Element  

### 4. Transform Orientations
- **Global**: World-fixed axes (X/Y/Z directions constant)  
- **Local**: Object’s axes, rotate with object  
- **Switching**: Double-tap axis key during transform (e.g., Z → Z)  

---

## 8. Core Shortcut Reference
| Function                | Shortcut |
|-------------------------|----------|
| Move View               | Shift + Middle Mouse |
| Rotate View             | Middle Mouse |
| Zoom View               | Mouse Wheel |
| Move Object             | G |
| Rotate Object           | R |
| Scale Object            | S |
| Constrain Axis          | G/R/S + X/Y/Z |
| Delete Object           | Delete / X |
| Add New Object          | Shift + A |
| Duplicate Object        | Shift + D |
| Hide Object             | H |
| Show Hidden Objects     | Alt + H |
| Switch Perspective      | Numpad 5 |
| Camera View             | Numpad 0 |
| Front View              | Numpad 1 |
| Right View              | Numpad 3 |
| Top View                | Numpad 7 |

---

## Summary
The focus of today’s learning: **interface familiarization + basic operations + four key concepts (3D Cursor, Origin, Pivot Point, Transform Orientation)**.  
Practice view navigation and object manipulation frequently to internalize these concepts in real operations.

---

## Chinese Version
# Blender 学习日志 Day1 — 界面、基础操作与核心概念

**更新于:** 2025-09-16  
**学习时长:** 2h  


## 一、Blender 界面初识
1. **初始界面**  
   打开 Blender 后的欢迎界面，可以新建文件、打开旧文件或点击空白处关闭。

2. **主要工作区**
   - **菜单栏 (Menu Bar)**：顶部，与其他软件类似  
   - **标签页 (Tabs)**：如 Layout, Modeling 等，代表不同的工作模式  
   - **工具架 (Tool Shelf)**：左侧，包含移动、旋转、缩放等工具  
   - **3D 视图 (3D Viewport)**：中间大区域，用于搭建和观察场景  
   - **场景集合 (Outliner)**：右上角，以列表显示场景中的对象  
   - **属性编辑器 (Properties Editor)**：右侧，显示对象的详细参数  
   - **时间轴 (Timeline)**：底部，用于制作动画  

---

## 二、三维创作的基本要素
Blender 默认场景包含 3 个核心要素：
- **模型 (Model)**：如立方体，是场景中的实体  
- **灯光 (Light)**：照亮场景，产生明暗和阴影  
- **摄像机 (Camera)**：决定最终渲染输出的视角和画面  

---

## 三、3D 创作的基本工作流程 (Workflow)
无论复杂项目还是简单练习，核心流程都是：
1. **建模 (Modeling)**：创建和塑造物体  
2. **材质与灯光 (Shading & Lighting)**：赋予外观和照明效果  
3. **渲染 (Rendering)**：输出为 2D 图像或动画  

---

## 四、视角控制（核心基础）
- **旋转视角**：鼠标中键拖动  
- **平移视角**：Shift + 中键拖动 / 工具栏“小手”  
- **缩放视角**：鼠标滚轮 / 工具栏“放大镜”  
- **切换正交/透视**：小键盘 `5` 或视图右上角按钮  
- **摄像机视图**：小键盘 `0`  

---

## 五、物体 (模型) 控制
### 1. 选择物体
- 框选：拖动选择多个物体  
- 光标工具：单击选择  
- 刷选：`C`  
- 套索：自由绘制选择区域  

### 2. 变换物体
- 移动：`G` → 轴向限制 `G+X/Y/Z`  
- 旋转：`R` → 轴向限制 `R+X/Y/Z`  
- 缩放：`S` → 轴向限制 `S+X/Y/Z`    
- 重置：`Alt+G` (位置), `Alt+R` (旋转), `Alt+S` (缩放)  

### 3. 其他操作
- 删除：`Delete` 或 `X`  
- 新建：`Shift+A`  
- 隐藏/显示：`H` / `Alt+H` / `Shift+H`  
- Outliner 显隐：小眼睛图标  
- 复制：`Shift+D`    

---

## 六、视图切换（多角度观察）
- **Gizmo 控件**：点击坐标轴快速切换  
- **小键盘**
  - `1` 正视图  
  - `3` 右视图  
  - `7` 顶视图  
  - `9` 反转当前视图  
  - `2/4/6/8` 旋转视角 15°  
- **波浪键菜单**：`~` 打开视图菜单  

---

## 七、四个核心概念
### 1. 游标 (3D Cursor)
- 红白相间的圆圈  
- **作用**：新物体生成点、快速定位、变换轴心点  
- **操作**：  
  - 移动：Shift+右键  
  - 重置：Shift+C  
  - 吸附：Shift+S 菜单（物体到游标 / 游标到物体）  

### 2. 原点 (Origin)
- 每个物体的黄色小点，存储位置/旋转/缩放信息  
- 旋转和缩放默认绕原点  
- 可切换“仅影响原点”模式编辑  

### 3. 轴心点 (Pivot Point)
- 旋转和缩放的中心点  
- 模式：边界框中心 / 质心 / 各自原点 / 3D 游标 / 活动元素  

### 4. 坐标系 (Transform Orientations)
- **全局 (Global)**：世界坐标，固定方向  
- **局部 (Local)**：物体自身方向，随旋转改变  
- **切换技巧**：变换时双击轴向键（Z→Z）  

---

## 八、核心快捷键速查表
| 功能             | 快捷键 |
|------------------|--------|
| 移动视角         | Shift + 中键拖动 |
| 旋转视角         | 中键拖动 |
| 缩放视角         | 滚轮 |
| 移动物体         | G |
| 旋转物体         | R |
| 缩放物体         | S |
| 轴向锁定         | G/R/S 后 + X/Y/Z |
| 删除物体         | Delete 或 X |
| 新建物体         | Shift + A |
| 复制物体         | Shift + D |
| 隐藏物体         | H |
| 显示隐藏物体     | Alt + H |
| 正交/透视切换    | 小键盘 5 |
| 摄像机视图       | 小键盘 0 |
| 正视图           | 小键盘 1 |
| 右视图           | 小键盘 3 |
| 顶视图           | 小键盘 7 |

---

## 总结
这一阶段学习的核心是 **界面熟悉 + 基础操作 + 四大概念（游标、原点、轴心点、坐标系）**。  
建议多练习视角控制和物体移动，在操作中体会这些概念。
