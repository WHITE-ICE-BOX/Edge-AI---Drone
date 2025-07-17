與印度學生共同合作執行邊緣式AI + 無人機專案計畫，全程利用英文溝通協作，在 NVIDIA Jetson Orin NX 邊緣裝置上部署語意分割模型，並開發即時影像洪水偵測轉換為 GPS 座標自動化飛控系統

1.開發語義分割演算法 - 將前端相機畫面與 GPS/IMU 感測數據融合，透過坐標轉換將像素級淹水區域映射至真實地理座標，支援精準定位。



2.規劃與執行完整 AI 模型訓練及量化 - 包含資料採集與標註、網路架構挑選與超參數優化，以及後續量化與剪枝，以滿足邊緣運算的計算資源與功耗需求。

3. NVIDIA Jetson Orin NX 邊緣裝置上部署  -  經 TensorRT 優化的影像分割與物件偵測深度學習推論服務，確保在嵌入式環境中達成即時反應。


4.建構自動化判斷與航點更新機制 - 當推論結果標示「淹水」區域時，系統立即回傳該座標並觸發動態航跡產生模組，引導無人機自動飛往並搜尋指定災情點。


5.精通 MAVROS 並結合Mission Planner、MAVProxy 等開源工具 - 實現六旋翼無人機的自動起飛、航點導航、精準返航與安全降落等全流程任務控制。





Technologies Used:

Hardware:NVIDIA Jetson Orin Nano、六旋翼 UAV 平臺、相機模組、GPS/IMU 感測器

Software:、Mission Planner、MAVProxy 、ROS2 (MAVROS)、TensorRT、OpenCV、TensorFlow / PyTorch、C++、Python
