# DFS / BFS 迷宮搜尋視覺化

這是一個使用 **PyQt6** 製作的互動式教學工具，用動畫呈現深度優先搜尋（DFS）與廣度優先搜尋（BFS）在迷宮網格中尋找路徑的過程。

## 功能

- 以逐步動畫顯示 DFS 與 BFS 的搜尋流程
- 顯示已拜訪節點、待探索節點、目前節點與最終路徑
- 比較 DFS 的堆疊（LIFO）與 BFS 的佇列（FIFO）行為
- 使用固定迷宮地圖，方便觀察兩種演算法的差異

## 環境需求

- Python 3.9 或更新版本
- PyQt6

## 安裝與執行

在專案根目錄執行：

```powershell
python -m pip install PyQt6
python .\dfs_bfs_pyqt6_STEP.py
```

若系統將 Python 指令命名為 `py`，可改用：

```powershell
py -m pip install PyQt6
py .\dfs_bfs_pyqt6_STEP.py
```

## 專案結構

```text
.
├── dfs_bfs_pyqt6_STEP.py  # PyQt6 視覺化應用程式
└── README.md              # 專案說明
```

## 演算法簡介

- **DFS（深度優先搜尋）**：優先沿著單一路徑往深處探索，使用堆疊管理待處理節點。
- **BFS（廣度優先搜尋）**：逐層向外探索，使用佇列管理待處理節點；在無權重圖中可找到最短步數路徑。
<<<<<<< HEAD
=======

## Contributor
- 楊皓翔
>>>>>>> 0a2d4f6ff7548d5cc47687acd47aa1211d7a873d
