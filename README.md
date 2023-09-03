# mumate

음악이 맞는 사람들끼리 실시간 ws형식 채팅 웹을 만드는 프로젝트.(미완성이다)
채팅은 구현을 했고, db설계와 youtube api를 활용해 음악을 공유하긴 했지만 나중에 다시 업데이트 예정
## To start
```shell
cd client
npm i
npm start
```
```shell
cd server
npm i
npm start
```
<br/>
.env from server folder. DB settings or PORT settings. 
if you want to start this web, you need to insert those '.env's
```
NODE_ENV=development
PORT=8081
LOGGER_LEVEL=debug

DB_HOST=localhost
DB_PORT=3306
DB_DATABASE=332project
DB_ID=root
DB_PASS=a123
DB_DIALECT=mysql
```
<br/><br/><br/>
```
.env from client folder. you can get this key from youtube data API v3.👍
JWT_SECRET_KEY= {import your personal key}
```



<br/><br/>

## What We Used
| Front | Back |
| --- | --- |
| React | NodeJS |
| styled-components | express |
| react-cookie | jwt |
| react-router-dom | MySQL |

## Who We are
Kim HyeJi : leader(maybe reader) + Front-end(60%) + Back-end(15%)<br/>
Lee KangWoo: Front-end(15%) + Back-end(70%)<br/>
Yoon Taeyoung: Front(15%) + Back-end(15%) (only been learning for a week)<br/>

Front-end 10% is gone~!

## This Proj is ...
User + Song + Chat(yet)<br/>
We still develop Song Service..<br/>
User can SignUp and Login to our site.<br/>
And if you click a button "song", you can be recommended some songs.<br/>
You can also add it to your playlist or liked.<br/>
Whenevr you want to listen them, just press MyPage - liked or playlist.<br/>
Playlist is literally a playlist.<br/>
liked is a function that matches the chat room with someone who has the same preference as you.(yet)<br/>

### Next Time
We'll refactoring this code first, and then we have to rebuild the component structure.<br/>
We will try to achieve our goals(Chatting, connecting server without errors, etc...)<br/><br/>
If We handle all of these, i'll probably write this README....<br/>
