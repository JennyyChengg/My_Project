---
mode: edit
---
# 目的 
建立一個使用者註冊的 stored procedure

# 資料庫 schema
-[參考] (../instructions/sqlserver.instructions.md)
- AddressBook 資料庫已經建立完成，不需要產生 DDL 指令


# stored procedure 名稱
login

# 輸入參數
--uid  
--cname  
--password 
以上三個參數資料型態參考資料庫 schema 中的UserInfo 資料表所對映的三個欄位
# 錯誤處理
不要進行任何錯誤處理

# 執行結果
以資料集方式傳回執行結果
1:表示註冊成功
0:表示註冊失敗
資料集欄位名稱為 result