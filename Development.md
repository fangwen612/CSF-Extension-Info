# 安裝編譯器/直譯器

| 程式語言 | 環境建置       | CJ目前使用版本 | 檢查安裝版本指令 |
| ------- | -------------  | ----- | ---|
| C       | 需安裝 [GCC](https://sourceforge.net/projects/mingw/) | gcc 9.4 | gcc -v |
| C++     | 需安裝 [G++](https://sourceforge.net/projects/mingw/) | g++ 9.4 | gcc -v |
| C#      | 需安裝 [.Net](https://dotnet.microsoft.com/en-us/download) | .Net 6 | dotnet --list-runtimes |
| Go      | 需安裝 [Go](https://go.dev/) | go 1.13.8 | go version |
| Java    | 需安裝 [JDK](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) | java 17.0.1 | java -version |
| Python  | 需安裝 [Python](https://www.python.org/downloads/windows/) | python 3.8.8 | python -V 或<br /> python --version |

如在終端機或命令提示字元(cmd)，輸入表格中「檢查安裝版本指令」，有出現相關說明或version版本等訊息，即為安裝成功且可查看安裝版本資訊。

## MinGW安裝GCC說明

1. 開啟MinGW，進入介面，選擇安裝C語言及C++編輯環境，並點擊「Installation」開始安裝。

    ![gcc-1](<image/gcc-1.png>)

2. 安裝完成後，需手動配置Path環境變數，進入【控制台】>【系統】>【關於】>【進階系統設定】，在「系統內容」中選擇設定「環境變數」。並在當前用戶下的Path新增「C:\MinGW\bin」路徑，即完成GCC編輯環境建置。

    ![gcc-1](<image/gcc-2.png>)