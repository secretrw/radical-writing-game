# iPad Online Deploy

這個資料夾是可部署版。雲端平台請用：

- Build command: `npm install`
- Start command: `npm start`
- Environment variable: `TEACHER_KEY=你想設定的老師密碼`

部署完成後：

- 學生加入網址：`https://你的網域/join`
- 老師網址：`https://你的網域/teacher?key=你的老師密碼`

老師登入後，大廳會顯示學生加入 QR code。學生用 iPad 相機掃描 QR code，輸入姓名後即可加入。

注意：

- 老師與學生都要使用同一個線上網址，不要用 `localhost`。
- 若重新部署或改了 server，請重啟雲端服務。
- QR code 會依照老師目前開啟的網址自動產生，所以部署到正式網址後再給學生掃。
