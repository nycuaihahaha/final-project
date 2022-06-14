# Artificial-Intelligence-final-project
## Main approach
### 架構
- application
   - mask_detector
      - mian_approach_train.py
      - main_approach_test.py
- dataset
   - mask_person
      - with_mask
      - without_mask
### python環境需求
- tensorflow == 2.0.4
- imutils
- matplotlib
### 執行方法
開啟terminal，切換到mian_approach_train.py檔案的目錄下，執行python train.py -d {你的mask_person資料集目錄}
### 測試
main_approach_test.py
其中的wm是有戴口罩的照片數，而wom是沒有的，withmask是有戴口罩且判斷對的，without是沒戴口罩且判斷對的
### 實際應用
如果要應用在實際影像上（有可能有許多張人臉或是沒有人臉），需要用main_approach_detect.py的程式碼。