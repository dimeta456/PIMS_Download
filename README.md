# PIMS 後台下載

按 **App 版本號** 下載對應後台。版本號必須一致，例如 App 2.9.21 使用 Release `2.9.21`。

打開 [Releases](https://github.com/dimeta456/PIMS_Download/releases)，選擇和自己 App 相同的版本，下載 `public_Manage_*.zip`。

版本對照也寫在 [`versions.json`](versions.json)。以後每發一個後台，就新增一個同名 Release，並在這個檔案裡加一行。

| App 版本 | 後台包 | 下載 |
|---|---|---|
| 2.9.21 | public_Manage_1106 | [public_Manage_1106.zip](https://github.com/dimeta456/PIMS_Download/releases/download/2.9.21/public_Manage_1106.zip) |

壓縮包裡有 SQL Server 版和 SQLite 版。用哪種資料庫，就進哪個目錄。

## SQL Server 通用安裝

SQL Server 與 SSMS 不隨 App 版本改變，所有後台版本共用，下載一次即可。

| 檔案 | 用途 | 下載 |
|---|---|---|
| SQL2022-SSEI-Dev.exe | SQL Server 2022 | [下載](https://github.com/dimeta456/PIMS_Download/releases/download/mssql/SQL2022-SSEI-Dev.exe) |
| SSMS-Setup-CHS.exe | SQL Server Management Studio 中文版 | [下載](https://github.com/dimeta456/PIMS_Download/releases/download/mssql/SSMS-Setup-CHS.exe) |
