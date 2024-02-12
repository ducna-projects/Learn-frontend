# Tổng hợp kiến thức của chủ đề - Introduction about HTML (Giới thiệu về ngôn ngữ HTML)
## 1. What is HTML? (HTML là gì?)
- HTML là viết tắt của Ngôn ngữ đánh dấu siêu văn bản.
- HTML là ngôn ngữ đánh dấu tiêu chuẩn để tạo ra các trang Web.
- HTML miêu tả cấu trúc của một trang Web.
- HTML bao gồm một loạt các phần tử.
- Các phần tử HTML cho trình duyệt biết cách hiển thị nội dung.
- Các phần tử HTML gắn nhãn cho các phần nội dung như "đây là tiêu đề", "đây là một đoạn văn", "đây là một liên kết", v.v.
**Lưu ý:**
HTML không phải là một ngôn ngữ lập trình vì nó không có cấu trúc logic…

## 2. Example of a simple html document (Ví dụ 1 tài liệu HTML đơn giản)
  <!DOCTYPE html>
    <html>
      <head>
        <title>Page Title</title>
      </head>
    <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
    </body>
  </html> 

#### Giải thích code trong ví dụ:
- Khai báo <!DOCTYPE html> xác định rằng tài liệu này là tài liệu HTML5.
- Phần tử <html> là phần tử gốc của trang HTML.
- Phần tử <head> chứa thông tin meta về trang HTML
- Phần tử <title> chỉ định tiêu đề cho trang HTML (được hiển thị trên thanh tiêu đề của trình duyệt hoặc trong tab của trang)
- Phần tử <body> xác định nội dung của tài liệu và là nơi chứa tất cả nội dung hiển thị, chẳng hạn như tiêu đề, đoạn văn, hình ảnh, siêu liên kết, bảng, danh sách, v.v.
- Phần tử <h1> xác định một tiêu đề lớn
- Phần tử <p> định nghĩa một đoạn văn
## 3. HTML tags? (Thẻ HTML là gì?)
Vì HTML xác định đánh dấu cho một trang web cụ thể nên bạn sẽ muốn văn bản, hình ảnh hoặc các nội dung nhúng khác xuất hiện theo những cách nhất định.

Ví dụ: bạn có thể muốn một số văn bản có kích thước lớn, văn bản khác có kích thước nhỏ và một số văn bản được in đậm, in nghiêng hoặc ở dạng dấu đầu dòng.

HTML có các "thẻ" cho phép bạn thực hiện việc này. Vì vậy, có các thẻ để tạo tiêu đề, đoạn văn, từ in đậm, từ in nghiêng, v.v.

Hình ảnh bên dưới mô tả giải phẫu của thẻ HTML:

![image](https://github.com/BlackEye-DucNA/Learn-frontend/assets/121158760/b3004233-a550-4d9d-854b-4ce6694b0682)

### 4. HTML element (Phần tử HTML)
An HTML element is defined by a start tag, some content, and an end tag:
Một phần tử HTML được xác định bởi thẻ bắt đầu, một số nội dung và thẻ kết thúc:
<tagname> Content goes here... </tagname> 
The HTML element is everything from the start tag to the end tag:
Phần tử HTML là mọi thứ từ thẻ bắt đầu đến thẻ kết thúc:
<h1>My First Heading</h1> 
<p>My first paragraph.</p> 
Start tag 
(Thẻ mở, thẻ bắt đầu)	Element content 
(Nội dung phần tử)	End tag 
(Thẻ đóng, thẻ kết thúc)
<h1>	My First Heading	</h1>
<p>	My first paragraph.	</p>
<br>	none	none

Note: Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!
Lưu ý: Một số phần tử HTML không có nội dung (như phần tử <br>). Những phần tử này được gọi là phần tử trống. Các phần tử trống không có thẻ kết thúc!
Every HTML element can have attributes.
Mọi phần tử HTML đều có thể có thuộc tính.
 


### 5. HTML Attributes (Thuộc tính HTML là gì?)
	Giải thích HTML attributes là gì, gồm các ý sau:
1. HTML elements can have attributes
- Phần tử HTML có thể có thuộc tính.

2. Attributes provide additional information about the element.
- Thuộc tính cung cấp thông tin bổ sung về phần tử.

3. Attributes come in name/value pairs like charset="utf-8".
- Các thuộc tính có cặp tên/giá trị như charset="utf-8".

 

### 6. HTML semantic? (HTML ngữ nghĩa là gì?)
Semantic HTML means that your HTML tags convey the actual meaning of what they are used for.
HTML ngữ nghĩa có nghĩa là các thẻ HTML của bạn truyền tải ý nghĩa thực sự của mục đích sử dụng chúng.
Semantics has been an integral part of HTML since its inception in the early 90s. But it never gained particular relevance until the late 90s when CSS started working in most browsers.
Ngữ nghĩa đã là một phần không thể thiếu của HTML kể từ khi nó ra đời vào đầu những năm 90. Nhưng nó chưa bao giờ đạt được sự liên quan đặc biệt cho đến cuối những năm 90 khi CSS bắt đầu hoạt động trong hầu hết các trình duyệt.
With semantic HTML, semantically-neutral tags such as <div> and <span> are frowned upon since semantically more descriptive tags such as <header>, <nav>, <main>, <section>, <footer> and <article> can do the same thing they do.
Với HTML ngữ nghĩa, các thẻ trung lập về mặt ngữ nghĩa như <div> và <span> không được tán thành vì các thẻ mang tính mô tả nhiều hơn về mặt ngữ nghĩa như <header>, <nav>, <main>, <section>, <footer> và <article> có thể làm điều tương tự như họ làm.
A noticeable advantage of using semantic tags is that web crawlers are able to index the web page or website easily, improving SEO in return.
Một lợi thế đáng chú ý của việc sử dụng thẻ ngữ nghĩa là trình thu thập dữ liệu web có thể lập chỉ mục trang web hoặc trang web một cách dễ dàng, cải thiện SEO.
In addition, a website that uses semantics becomes more informative, adaptable, and accessible to those who use screen readers to access websites.
Ngoài ra, một trang web sử dụng ngữ nghĩa sẽ trở nên giàu thông tin hơn, dễ thích ứng hơn và dễ tiếp cận hơn đối với những người sử dụng trình đọc màn hình để truy cập trang web.

### 7. HTML History (Lịch sử HTML)
Since the early days of the World Wide Web, there have been many versions of HTML:
Kể từ những ngày đầu của World Wide Web, đã có nhiều phiên bản HTML:
Year	Version
1989	Tim Berners-Lee invented www
Tim Berners-Lee đã phát minh ra www
1991	Tim Berners-Lee invented HTML
Tim Berners-Lee đã phát minh ra HTML
1993	Dave Raggett drafted HTML+
Dave Raggett đã soạn thảo HTML+
1995	HTML Working Group defined HTML 2.0
Nhóm làm việc HTML đã xác định HTML 2.0
1997	W3C Recommendation: HTML 3.2
Khuyến nghị của W3C: HTML 3.2
1999	W3C Recommendation: HTML 4.01
Khuyến nghị của W3C: HTML 4.01
2000	W3C Recommendation: XHTML 1.0
Khuyến nghị của W3C: XHTML 1.0
2008	WHATWG HTML5 First Public Draft
WHATWG HTML5 Bản thảo công khai đầu tiên
2012	WHATWG HTML5 Living Standard
Tiêu chuẩn sống HTML5 WHATWG
2014	W3C Recommendation: HTML5
Khuyến nghị của W3C: HTML5
2016	W3C Candidate Recommendation: HTML 5.1
Khuyến nghị của ứng viên W3C: HTML 5.1
2017	W3C Recommendation: HTML5.1 2nd Edition
Khuyến nghị của W3C: HTML5.1 Phiên bản thứ 2

### 8. Application of HTML (Ứng dụng, vận dụng của HTML)
HTML được sử dụng cho nhiều mục đích. Các mục đích, ứng dụng được liệt kê như dưới đây:
Web Pages Development (Phát triển trang Web)
HTML is famously used for creating web pages on the world wide web. Every web page contains a set of HTML tags and hyperlinks which are used to connect other pages. Every page on the internet is written using HTML.
HTML được sử dụng nổi tiếng để tạo các trang web trên world wide web. Mỗi trang web đều chứa một tập hợp các thẻ HTML và siêu liên kết được sử dụng để kết nối các trang khác. Mọi trang trên internet đều được viết bằng HTML.

Navigating the Internet (Điều hướng Internet)
Navigating on the internet would have been quite a tedious task without HTML. The anchor tags of HTML allows us to link pages and navigate easily. Imagine our life without anchor tags, you would literally have to enter URL everytime. Using achor tags, you can also navigate within a webpage.
Điều hướng trên internet sẽ là một công việc khá tẻ nhạt nếu không có HTML. Các thẻ neo của HTML cho phép chúng ta liên kết các trang và điều hướng dễ dàng. Hãy tưởng tượng cuộc sống của chúng ta không có thẻ neo, bạn sẽ phải nhập URL mọi lúc. Sử dụng thẻ achor, bạn cũng có thể điều hướng trong trang web.

Embedding Images and Videos (Nhúng ảnh & video)
HTML allows us to embed images and videos with ease and gives us features to adjust height, position and even rendering type. You can adjust controls, thumbnails, timestamps and much more for videos. Earlier this was done using Flash and HTML has made it easier with the help of <video> tag.
HTML cho phép chúng ta nhúng hình ảnh và video một cách dễ dàng đồng thời cung cấp cho chúng ta các tính năng để điều chỉnh độ cao, vị trí và thậm chí cả kiểu hiển thị. Bạn có thể điều chỉnh các điều khiển, hình thu nhỏ, dấu thời gian và nhiều thứ khác cho video. Trước đây việc này được thực hiện bằng Flash và HTML đã khiến việc này trở nên dễ dàng hơn nhờ sự trợ giúp của thẻ <video>.

Clinet-side storage (Lưu trữ phía máy khách)
HTML5 has made client-side storage possible using localStorage and IndexD due to which we no longer need to reply on Cookies. Both of these tactics have their own set of rules and characteristics. String-based hash-table storage is provided by localStorage. Its API is straightforward, with setItem, getItem, and removeItem functions available to developers. On the other hand, IndexDB is a larger and more capable client-side data store. With the user’s permission, the IndexDB database can be enlarged.
HTML5 đã giúp khả năng lưu trữ phía máy khách có thể sử dụng localStorage và IndexD do đó chúng tôi không cần phải trả lời trên Cookies nữa. Cả hai chiến thuật này đều có những quy tắc và đặc điểm riêng. Lưu trữ bảng băm dựa trên chuỗi được cung cấp bởi localStorage. API của nó rất đơn giản, với các hàm setItem, getItem và RemoveItem có sẵn cho các nhà phát triển. Mặt khác, IndexDB là kho lưu trữ dữ liệu phía máy khách lớn hơn và có khả năng cao hơn. Với sự cho phép của người dùng, cơ sở dữ liệu IndexDB có thể được mở rộng.

Game development (Phát triển game)
Although you cannot create complex high-end video games with HTML, the <canvas> element of HTML can be used to make 2D and 3D games using CSS and JavaScript which can be run on browsers.
Mặc dù bạn không thể tạo các trò chơi điện tử cao cấp phức tạp bằng HTML, nhưng phần tử <canvas> của HTML có thể được sử dụng để tạo các trò chơi 2D và 3D bằng CSS và JavaScript có thể chạy trên trình duyệt.

Data entry support (Hỗ trợ nhập dữ liệu)
With the usage of new HTML5 standards in all the latest browsers, developers can simply add the tags for required fields, text, data format, etc. and get the data. HTML5 now has several new attributes for data-entry and validation purposes.
Với việc sử dụng các tiêu chuẩn HTML5 mới trong tất cả các trình duyệt mới nhất, nhà phát triển có thể chỉ cần thêm thẻ cho các trường, văn bản, định dạng dữ liệu, v.v. bắt buộc và lấy dữ liệu. HTML5 hiện có một số thuộc tính mới cho mục đích xác thực và nhập dữ liệu.
Interacting with Native APIs (Tương tác với APIs gốc)
With the help of HTML, you can interact with your Operating system. With this feature, you can easily drag files onto a web page to upload, full-screen a video, and much more.
Với sự trợ giúp của HTML, bạn có thể tương tác với Hệ điều hành của mình. Với tính năng này, bạn có thể dễ dàng kéo tệp vào trang web để tải lên, xem video ở chế độ toàn màn hình và hơn thế nữa.
### 9. Benefits of HTML (Lợi ích của HTML)
•	The learning curve is very easy (easy to modify)
•	Đường cong học tập rất dễ dàng (dễ sửa đổi)
•	Creating effective presentations
•	Tạo bài thuyết trình hiệu quả
•	Adding Links wherein we can add references
•	Thêm liên kết trong đó chúng tôi có thể thêm tài liệu tham khảo
•	Can display documents on platforms like Mac, Windows, Linux, etc
•	Có thể hiển thị tài liệu trên các nền tảng như Mac, Windows, Linux, v.v.
•	Adding videos, graphics, and audios making it more attractive
•	Thêm video, đồ họa và âm thanh để hấp dẫn hơn
•	Case insensitive language
•	Ngôn ngữ không phân biệt chữ hoa chữ thường

### 10. Advantages & Disadvantages of HTML (Ưu và Nhược điểm của HTML)
#### 10.1. Ưu điểm của HTML
•	Ngôn ngữ này được sử dụng rộng rãi với rất nhiều nguồn tài nguyên hỗ trợ cùng một cộng đồng sử dụng vô cùng lớn đằng sau nó.
•	Có thể hoạt động mượt mà trên hầu hết mọi trình duyệt hiện hành.
•	Quá trình học HTML khá đơn giản.
•	Mã nguồn mở và hoàn toàn miễn phí.
•	Các Markup sử dụng trong HTML thường ngắn gọn và đồng nhất.
•	Chuẩn chính của web được vận hành bởi World Wide Web Consortium (W3C).
•	Dễ dàng tích hợp với các ngôn ngữ backend như PHP, Node.js,...
#### 10.2. Nhược điểm của HTML
•	Ngôn ngữ này chỉ được áp dụng chủ yếu cho trang web tĩnh. Đối với các tính năng động, bạn cần sử dụng JavaScript hoặc ngôn ngữ backend bên thứ 3 ví dụ như PHP.
•	Người dùng phải tạo các trang web riêng lẻ cho HTML, ngay cả khi các phần tử giống nhau.
•	Một số trình duyệt chấp nhận các tính năng mới một cách chậm chạp. Đôi khi các trình duyệt cũ hơn không phải lúc nào cũng hiển thị các thẻ mới hơn.

