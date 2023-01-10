# VSCode 套件安裝與執行方法

請先安裝 [CSF Extension](https://marketplace.visualstudio.com/items?itemName=skes4126.CSF-Extension) 擴充套件包

![csf-extension](<image/csf-extension-2.png>)

## 套件與設定

1. 中文介面（【Chinese (Traditional) Language Pack for Visual Studio Code】套件）：
    
    * 按下「Ctrl+Shift+P」，以顯示「命令選擇區」
    * 輸入「display」以篩選「Display Language」命令。點擊後會顯示已安裝的語言清單 
    * 選擇「中文(繁體)」並重新開啟 VSCode ，即完成中文介面設定！

    ![language](<image/language.png>)

2. 終端機輸出（【Code Runner】套件）：

    * 找到Code Runner套件，點擊設定icon進入「擴充設定」介面
    * 勾選「Code-runner: Run In Terminal」，使執行結果可於終端機顯示！

    ![codeRunner](<image/code-runner.png>)

3. 相對路徑設定（Python）：
    
    * 點擊畫面左下角設定按鈕，進入「設定」介面
    * 輸入「execute」以篩選及顯示執行的相關設定
    * 勾選「Python > Terminal: Execute in File Dir」，使Python檔案可直接讀取相對路徑資料！

    ![path](<image/path.png>)

## 各語言執行方法

以下說明各程式語言於 VSCode 編輯器中的執行方法：

| 程式語言 | 執行方法 | 
| ------- | -------  |
| C       | 【方法1】 滑鼠右鍵 > Run Code，即可執行程式<br /> 【方法2】點擊VSCode畫面右上角箭頭![](<image/arrow.png>)，即可執行程式（Run Code） | 
| C++     | 【方法1】 滑鼠右鍵 > Run Code，即可執行程式<br /> 【方法2】點擊VSCode畫面右上角箭頭![](<image/arrow.png>)，即可執行程式（Run Code） | 
| C#      | 終端機輸入「dotnet new console」建立專案並在內建的「Program.cs」中撰寫程式碼，於終端機輸入「dotnet run」即可執行程式 | 
| Go      | 【方法1】 滑鼠右鍵 > Run Code，即可執行程式<br /> 【方法2】點擊VSCode畫面右上角箭頭![](<image/arrow.png>)，即可執行程式（Run Code） <br /> 【方法3】終端機中輸入「go run xxx.go」 | 
| Java    | 【方法1】 滑鼠右鍵 > Run Code，即可執行程式<br /> 【方法2】點擊VSCode畫面右上角箭頭![](<image/arrow.png>)，即可執行程式（Run Code） | 
| Python  | 【方法1】 滑鼠右鍵 > Run Code，即可執行程式<br /> 【方法2】點擊VSCode畫面右上角箭頭![](<image/arrow.png>)，即可執行程式（Run Python File） | 