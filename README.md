# Extract Meta & Google Inc. Stock Sentiment from News Headlines
## Brief
Ý tưởng thực hiện của dự án bắt nguồn bằng việc phân tích ngữ nghĩa sắc thái tình cảm của các dòng tiêu đề của tin tức về cổ phiếu của các công ty, qua đó đo lường độ tích cực/ tiêu cực nhằm đưa ra được lời khuyên về tài chính và đầu tư.
Ở đây phạm vi phân tích của dự án đó là công ty Meta Platforms (công ty chủ quản của Facebook) và công ty Alphabet Inc. (công ty chủ quản của Google).
## News Headline
Các dòng tin tức đều được thu thập realtime từ trang [Finviz] (Finviz.com), đây là trang tin tức tài chính tổng hợp từ nhiều nguồn tin khác nhau, được cập nhật liên tục và đa dạng nội dung.

<img width="681" alt="msedge_A1X86VG9m8" src="https://github.com/hiepm94/Extract-Stock-Sentiment-from-News-Headlines/assets/96098339/44b5b895-47e1-433a-9123-272c3b06c650">

## Sentiment Analysis
Việc phân tích sắc thái được thực hiện bằng cách sử dựng thư viện NLTK/VADER với một số điều chỉnh về từ điển, đưa ra độ đo về 3 sắc thái: tích cự, trung hòa và tiêu cực.
## Visualization result
Ta đưa ra được kết quả phân tích trực quan về tình trạng cổ phiếu của META và GOOGL tại thời gian nghiên cứu:
![image](https://github.com/hiepm94/Extract-Stock-Sentiment-from-News-Headlines/assets/96098339/147bf5fd-3ad6-4fda-b0b7-28a9ce508510)
Và cả nội dung phân tích cố phiếu công ty META trong một ngày:
![image](https://github.com/hiepm94/Extract-Stock-Sentiment-from-News-Headlines/assets/96098339/b2ca5734-5226-4542-8f84-19de4cbcb9b2)
