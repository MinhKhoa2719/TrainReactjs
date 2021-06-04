# TrainReactjs

- React Js là một thư viện viết bằng javascript, dùng để xây dựng giao diện người dùng (UI).
- React Js là một thư viện javascript dùng để xây dựng UI, UI ở đây được dùng chính ở 2 nền tảng Web và Mobile
Ở lĩnh vực mobile ta có React Native
- React được sử dụng rộng rãi và có hệ sinh thái đa dạng phong phú. UI tất nhiên là quan trọng, nhưng không phải là tất cả. Để phát triển ứng dụng hoàn chỉnh phải cần thêm:

- Server side language: để xử lý logic và lưu trữ dữ liệu trên server.
- HTML/CSS làm ứng dụng web.
- Flux/Redux?: là một kiến trúc giúp tổ chức code rõ ràng và sạch sẽ.
- Objective C: xây dựng app cho iOS
### Lưu ý
- Nếu nắm vững React sẽ là rất dễ để tiếp cận với Node JS – javascript phía server
- Node JS và React thực sự rất hay ho và được tuyển dụng nhiều
- Javascript: Ngôn ngữ xây dựng nên React, yêu cầu mức độ trung bình: các khái niệm “object”, “prototype”, “callback” là bắt buộc
- HTML/CSS: yêu cầu mức độ cơ bản nhất.

## TẠO APP VỚI HELLO WORLD

Nếu trên máy đã có cài npm và node.js thì ta thực hiện lệnh để tạo một dự án React.js với cấu hình mặc định
```jsx
npm install –g create-react-app
```
![image](https://user-images.githubusercontent.com/54676091/120806267-d70e9c00-c570-11eb-81f7-190df1806e83.png)

### Tạo project

Để tạo một dự án khi các lệnh trên được thực thi, hãy chạy lệnh bên dưới
```jsx
npx create-react-app hello-world-example
```
![image](https://user-images.githubusercontent.com/54676091/120806130-afb7cf00-c570-11eb-980a-8c2ed7125caa.png)

Sau khi hoàn thành ta sẽ có 1 file hello-world-example cd đến file này bằng lệnh :
```jsx 
cd hello-world-example
```
Sau đó ta mở Web lên bằng lệnh 
```jsx
npm start
```

![image](https://user-images.githubusercontent.com/54676091/120806673-57350180-c571-11eb-933d-d572df416096.png)


##### Ta sẽ nhận được trình duyệt tại port 3000 mặc định

![image](https://user-images.githubusercontent.com/54676091/120806834-821f5580-c571-11eb-98e5-00d4c9ce0cfe.png)

#### Lệnh npm start sẽ cập nhật những thay đổi mới nhất và nó được hiển thị trên Web

### Mở Tệp App.js bằng bất cứ trình phiên dịch nào và ở đây tui dùng VSCODE
```jsx
import React from 'react';
import logo from './logo.svg';
import './App.css';
function App() {
   return (
      <div className="App">
         <header className="App-header">
            <img src={logo} className="App-logo" alt="logo" />
            <p>Edit <code>src/App.js</code> and save to reload.</p>
            <a
               className="App-link"
               href="https://reactjs.org"
               target="_blank"
               rel="noopener noreferrer">
               Learn React
            </a>
         </header>
      </div>
   );
}
export default App;
```
### Thay đổi nội dung của câu lệnh return thành văn bản hello World
```jsx
import React from 'react';
import logo from './logo.svg';
import './App.css';
function App() {
   return (
      <div className="App">
         Hello World !
      </div>
   );
}

export default App;
```

### Kết Quả

![image](https://user-images.githubusercontent.com/54676091/120808229-10480b80-c573-11eb-9146-85f99e98f1df.png)



