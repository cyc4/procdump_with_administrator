# procdump_with_administrator 
### [Winnie Chen 11/1 MS 2019/11/1]

Collect Procdump with administrator authentication
使用管理員權限蒐集ProcDump資料

## [Preparation　ＩＴ事前準備]

### 1. Please close all the Excel documents and Excel application

請先關閉所有的"Excel"文件及Excel應用程式

### 2. Copy the downloaded files to D Drive under Test Directory

複製本Repo下載的檔案到D槽下的Test資料夾
![](https://i.imgur.com/y2eFUSZ.png)

### 3. Open command line and execute the run_after_reboot.bat file. Please use "command line" to execute the batch file. Not to double click the file or you will not able to check the error message.
![](https://i.imgur.com/83AM8mX.png)

打開命令提示字元，並執行run_after_reboot.bat檔案。切記請勿直接雙擊開啟該檔案，否則可能無法查看到錯誤訊息（錯誤的話僅會彈出一個視窗後很快地消失）

### 4. If you input the corrct account and password, you have successfully set up the procdump collection batch.

若輸入正確的帳號密碼，看到黃框處的指令，就代表成功設定好Procdump蒐集的指令

![](https://i.imgur.com/7Ptj4Az.png)

確認前面步驟都成功的話，就可以將檔案放到使用者的D槽的Test資料夾

## [End User Execution　使用者執行]

### 1. Confirmed all the excel documents are closed as well as the Excel application 

確認所有的"Excel"文件及Excel應用程式都關閉

### 2. Double click the run_after_reboot.bat file. 

雙擊run_after_reboot.bat檔案，第一次執行時可能會需要輸入管理員密碼

### 3. If you input the corrct account and password, you have successfully set up the procdump collection batch.

若輸入正確的帳號密碼，看到黃框處的指令，就代表成功設定好Procdump蒐集的指令

![](https://i.imgur.com/7Ptj4Az.png)

### 4. Start to repro the issues until the application crashes. The batch file will start to collect dump file at D:\Test

開始Repro問題直到Excel Crash，Crash的當下會產生Dump檔案到D:\Test

![](https://i.imgur.com/oC7a2n3.png)






