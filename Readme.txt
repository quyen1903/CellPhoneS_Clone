// bài này em nộp cuối kỳ môn khác nhưng gấp quá em upload tạm lên github luôn nha thầy :((
//tên sinh viên: Nguyễn Quang Quyền
// mã sinh viên AT150840
//lớp:AT15N02 /(hay còn gọi là AT15I)



This project created base on someone project on the internet :v
(I suggest to use gitbash)

your computer must have nodejs and npm to deploy&run this project

First inside server folder and client folder(separate them!!) we use command type command
npm install --force
Wait about one minute(depend on your computer)

Next in server folder, we use command 
npm run start

then open another git process on client folder(do not cd because it can interrupt our server)
and use this command
export NODE_OPTIONS=--openssl-legacy-provider
this command to create env for node to run(we use gitbash, if we use windows we can change to)
set NODE_OPTIONS=--openssl-legacy-provider

now in client folder use command
npm run start

browser automatically open our web
or we can open up manually by type:
localhost:3000

enjoy, have fun!!!!!!!
