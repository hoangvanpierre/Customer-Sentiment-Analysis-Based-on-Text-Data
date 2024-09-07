# Customer-Sentiment-Analysis-Based-on-Text-Data

Được thu thập từ TeePublic - là một nền tảng in theo yêu cầu (POD) cho phép các nhà thiết kế sáng tạo và bán các sản phẩm tùy chỉnh, bao gồm áo thun, áo hoodie, ốp nịt điện thoại, cốc, v.v. Với tập dữ liệu Fashion_Retail_Sales.csv có chứa 3400 dòng dữ liệu, mỗi dòng 
tương ứng với một đơn hàng khác nhau và bao gồm cả những nhận xét của khách hàng về đơn hàng đó. Bộ dữ liệu gồm có các cột:

•	Purchase Amount (USD): Số tiền mua hàng (tính bằng USD)

•	Date Purchase: Ngày mua hàng, theo format yyyy/mm/dd.

•	Review Rating: Mức đánh giá sản phẩm, theo thang đánh giá từ 1 – 5.

•	Payment Method: Phương thức thanh toán (bao gồm thẻ tín dụng và tiền mặt)

•	Title: Tiêu đề của phần đánh giá sản phẩm

•	Review: Nội dung của phần đánh giá sản phẩm

Các đơn hàng này được thực hiện trong khoảng thời gian từ 11/2022 đến 08/2023. Số tiền mua hàng dao động trong khoảng 2.102 USD đến 4.771 USD. Đánh giá sản phẩm phần lớn tập trung xoay quanh từ mức 1 đến 5. Các phương thức thanh toán phổ biến là thẻ tín dụng và tiền mặt.
Nội dung đánh giá cung cấp phản hồi chi tiết chung về chất lượng sản phẩm, dịch vụ khách hàng, quy trình đặt hàng và vận chuyển. Một số đánh giá tích cực về chất lượng in hình và dịch vụ khách hàng tốt. Tuy nhiên, cũng có đánh giá tiêu cực về vấn đề kích thước sản phẩm và chất lượng của các loại sản phẩm khác nhau.

![image](https://github.com/user-attachments/assets/9d4c43f2-01a8-46d1-ac5f-918b39bdef8c)

                                      (Hình 1. Nội dung của bộ dữ liệu)

Để đảm bảo phân tích dữ liệu một cách tốt nhất thì nhóm đã sử dụng một số thư viện hỗ trợ để xử lý dữ liệu, có thể kể đến như:

• Numpy, Pandas: hai thư viện này giúp nhóm tương tác với dữ liệu trong dataframe 
một cách rõ ràng và nhanh chóng

• Các thư viện trực quan hóa dữ liệu phổ biến như matplotlib, seaborn, WordCloud hỗ
trợ mạnh mẽ cho vấn đề trực quan dữ liệu một cách đẹp mắt, dễ nhìn.

• Và hai thư viện tương tác với dữ liệu văn bản như nltk, re giúp nhóm có thể thực 
hiện các tác vụ xử lý ngôn ngữ tự nhiên, tokenization, phân tích cú pháp, tìm kiếm, 
thay thế văn bản theo mẫu nhất định.

Bằng các phương pháp kể trên đã rút ra được những kinh nghiệm như xác định cảm xúc chủ đạo của khách hàng (tích cực, tiêu cực hay trung tính) mà khách hàng thể hiện đối với mỗi sản phẩm. Ngoài ra, nhóm đã nhận ra được các yếu tố sản phẩm nào được khách hàng đánh giá cao hoặc không hài lòng. Từ đó trực quan hóa kết quả phân tích để làm rõ các vấn đề còn đang tồn đọng. Cuối cùng thì nhóm có thể tổng hợp những điểm mạnh, điểm yếu của sản phẩm theo góc nhìn của khách hàng, giúp nhà sản xuất hiểu rõ hơn nhu cầu và ra các quyết định cải tiến phù hợp cho các sản phẩm của mình.
