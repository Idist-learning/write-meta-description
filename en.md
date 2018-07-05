# Làm thế nào để viết được những thẻ Meta để mô tả trong một thế giới thay đổi liên tục (AKA Google Giveth, Google Taketh Away)

```
Tóm tắt: khoảng giữa tháng 5 năm 2018, Google đã quay lại việc sử dụng các đoạn trích ngắn. Dữ liệu của chúng tôi cho thấy việc này đang lan rộng ra và hầu hết các thẻ meta dùng để mô tả đều được cắt bớt về độ dài nằm trong khoảng 155-160 kí tự.
```

Quay trở lại tháng 12, Google đã thực hiện một thay đổi đáng kể trong việc hiển thị các đoạn trích ngắn khi tìm kiếm, công trình nghiên cứu của chúng tôi đã chỉ ra rằng có rất nhiều các đoạn trích vượt quá 300 kí tự. Cuối tuần qua, họ dường như đã quay lại thay đổi đó (Danny Sullivanđã xác nhận một phần điều này trên Twitter ngày May 14). Bên cạnh các câu hỏi hiển nhiên — Giới hạn mới là gì? — Nó khiến bạn tự hỏi phải làm gì để đối phó với các quy tắc khi nó tiếp tục thay đổi.Không ai trong chúng ta có một quả cầu tiên tri, Nhưng tôi sẽ cố gắng trả lời các câu hỏi trên dựa vào những gì chúng a biết hôm nay.

## Dối trá, dối trá trắng trợn, và thống kê...

Tôi đã lấy tất cả các đoạn trích tìm kiếm có sẵn từ MozCast 10K (trang kết quả của Google cho 10.000 từ khóa), vì đó là tập dữ liệu chúng tôi thu thập hàng ngày và có lịch sử phong phú. Có 89.383 đoạn mã hiển thị trên tập dữ liệu đó vào sáng ngày 15 tháng 5.

Tôi có thể nói với bạn rằng, trên toàn bộ tập dữ liệu, độ dài tối thiểu là 6 ký tự, độ dài tối đa là 386, và trung bình là khoảng 159. Điều đó không hữu ích lắm, vì một vài lý do. Đầu tiên, nói với bạn để viết mô tả meta giữa 6–386 ký tự không phải là lời khuyên hữu ích. Thứ hai, chúng ta đang đối phó với rất nhiều trường hợp. Ví dụ: đây là đoạn trích trên tìm kiếm "USMC":

![](https://d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-1-4065.png)

Marine Corps Community Services có thể là một tổ chức tuyệt vời, nhưng tôi xin lỗi khi nói rằng phần meta description của họ, thực ra là "vẻ bề ngoài" (Google đánh dấu theo mốc thời gian, theo tôi đó là tiêu chí cuối cùng). Dưới đây là một đoạn trích cho tìm kiếm trên cửa hàng bách hóa "Younkers":

![](https://d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-2-4999.png)

Bỏ qua sự nhầm lẫn các thương hiệu nghiêm trọng của họ, tôi nghĩ tất cả chúng ta có thể đồng ý rằng "BER Meta TAG1" không phải là tối ưu. Nếu những trường hợp này dạy cho bạn bất cứ điều gì, nó chỉ là về những gì bạn không nên làm. Điều gì xảy ra khi bạn làm ngược lại? Dưới đây là một đoạn trích có 386 ký tự, từ tìm kiếm "thỏa thuận không cạnh tranh" - "non-compete agreement":

![](https://d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-3-12620.png)

Vì vậy, chúng tôi biết rằng các đoạn mô tả dài hơn vẫn tồn tại. Tuy nhiên, lưu ý rằng cả hai đoạn mô tả này đều đến từ Wikipedia, đây là ngoại lệ đối với nhiều quy tắc SEO. Những mô tả dài này liệu chỉ có các trường hợp ngoại lệ không? Nhìn vào giá trị trên trung bình (hoặc thậm chí là trung bình, trong trường hợp này) không thực sự cho chúng ta biết.

## bức tranh toàn cảnh phần 1

Đôi khi, bạn phải để cho dữ liệu cố gắng để nói về chính nó, với tối thiểu là dỗ dành. Hãy xem xét tất cả các đoạn trích được cắt bỏ (kết thúc bằng "...") và xóa kết quả video (chúng tôi biết từ nghiên cứu trước rằng những đoạn này ngắn hơn một chút). Điều này để lại 42,863 đoạn trích (chỉ bằng một nửa bộ dữ liệu của chúng tôi). Dưới đây là một đồ thị của tất cả các độ dài cắt, thu thập thành 25 thùng ký tự (0-25, 26-50, vv):

![](https://d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-5-4779.png)

This looks very different from our data back in December, and is clearly clustered in the 150–175 character range. We see a few Google display snippets cut off after the 300+ range, but those are dwarfed by the shorter cut-offs.

## bức tranh toàn cảnh phần 2 

Điều này trông rất khác với dữ liệu của chúng tôi vào tháng 12 và được phân cụm rõ ràng trong phạm vi ký tự 150–175. Chúng tôi thấy một vài đoạn mã hiển thị của Google bị cắt sau phạm vi 300+, nhưng những đoạn mã này bị thu hẹp bởi các lần cắt ngắn hơn.

![](https://d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-6-4992.png)

Chúng ta có thể thấy khá rõ ràng rằng phần lớn các lần cắt giảm xảy ra trong phạm vi ký tự 145–165. Trước tháng 12, các nguyên tắc mô tả meta trước đây của chúng tôi là giữ chúng dưới 155 ký tự, vì vậy dường như Google đã hoàn nguyên nhiều hơn hoặc ít hơn cho các quy tắc cũ.

Hãy nhớ rằng Google sử dụng phông chữ tỷ lệ thuận, vì vậy không có giới hạn ký tự chính xác. Một số người đã đưa ra giả thuyết một giới hạn chiều rộng pixel, giống như với thẻ tiêu đề, nhưng tôi thấy rằng khó khăn hơn để ghim xuống với các đoạn mã nhiều dòng (tình huống thậm chí còn khó khăn hơn trên kết quả di động). Thực tế, cũng khó để viết tới giới hạn pixel. Các dữ liệu cho thấy rằng 155 ký tự là một xấp xỉ hợp lý.

## To the Wayback Machine... ?!

Chúng ta có nên quay trở lại với 155 ký tự không? Nếu bạn đã viết mô tả meta dài hơn, bạn có nên xóa công việc đó và bắt đầu lại không? Sự thật đơn giản là không ai trong chúng ta biết điều gì sẽ xảy ra vào tuần tới. Cách tôi nhìn thấy nó, chúng tôi có bốn lựa chọn khả thi:

### (1) để google xử lý chúng

Một số trang web không có mô tả meta. Wikipedia là một trong số chúng. Bây giờ, sự hiểu biết của Google về nội dung của Wikipedia sâu sắc hơn nhiều so với hầu hết các trang web (một phần, nhờ Wikidata), nhưng nhiều trang web làm tốt tiền phạt mà không có thẻ. Nếu lựa chọn của bạn là viết thẻ không hợp lệ, lặp lại hoặc để trống, thì tôi sẽ nói để trống chúng và để Google sắp xếp.

### (2) hãy để ... tự rơi vào nơi nó có thể

Bạn chỉ có thể viết cho độ dài bạn nghĩ là lý tưởng cho bất kỳ trang nào (trong lý do), và nếu đoạn trích bị cắt bỏ, đừng lo lắng về nó. Có lẽ dấu ba chấm (...) thêm âm mưu. Tôi đang nói đùa một nửa, nhưng thực tế là việc cắt bỏ không phải là nụ hôn của cái chết. Một mô tả hay nên lôi kéo mọi người muốn đọc thêm.

### (3) Cắt bỏ mọi thứ ở 155 kí tự

Bạn có thể quay trở lại và tàn nhẫn hack tất cả các công việc khó khăn của bạn trở lại 155 ký tự. Tôi nghĩ rằng điều này thường sẽ mất nhiều thời gian và có thể dẫn đến các đoạn tìm kiếm thậm chí tệ hơn. Nếu bạn muốn viết lại mô tả Meta ngắn hơn cho các trang quan trọng nhất của mình, điều đó hoàn toàn hợp lý, nhưng hãy nhớ rằng một số kết quả vẫn hiển thị các đoạn mã dài hơn và tình trạng này sẽ tiếp tục phát triển.

### (4) Viết mô tả thích ứng với độ dài

Có thể viết mô tả hoạt động tốt ở cả hai độ dài không? Tôi nghĩ rằng có, với một số chăm sóc và lập kế hoạch. Tôi sẽ không nhất thiết phải đề nghị điều này cho mỗi trang, nhưng có lẽ có một cách để có bánh của chúng tôi và ăn ít nhất một nửa của nó, quá ...

## Cách tiếp cận 150/150

Tôi đã bị ám ảnh một chút với phong cách "kim tự tháp ngược" của văn bản gần đây. Đây là một phong cách báo chí nơi bạn bắt đầu với chì hoặc tóm tắt điểm chính của bạn và sau đó chia nhỏ chi tiết, dữ liệu và ngữ cảnh. Mặc dù cách tiếp cận này rất phù hợp với web, nguồn gốc của nó xuất phát từ các giới hạn bố cục trong bản in. Bạn không bao giờ biết khi nào trình soạn thảo của bạn sẽ phải cắt ngắn bài viết của bạn để vừa với không gian sẵn có, do đó, phong cách kim tự tháp ngược giúp đảm bảo rằng phần quan trọng nhất thường được tha.

Điều gì sẽ xảy ra nếu chúng tôi thực hiện phương pháp này để mô tả meta? Nói cách khác, tại sao không viết 150 ký tự "dẫn" tóm tắt trang, và sau đó thêm 150 ký tự chi tiết hữu ích nhưng ít cần thiết (khi thêm chi tiết đó có ý nghĩa và cung cấp giá trị)? 150/150 không phải là số ma thuật - thậm chí bạn có thể làm 100/100 hoặc 100/200. Điều quan trọng là để đảm bảo rằng văn bản trước khi cắt có thể tự đứng vững.

Hãy suy nghĩ về nó một chút giống như một quảng cáo, với hai dòng riêng biệt của bản sao. Hãy lấy bài đăng trên blog này:

### Dòng 1 (145 chars.)

Vào tháng 12, chúng tôi đã báo cáo rằng Google đã tăng đoạn trích tìm kiếm lên hơn 300 ký tự. Thật không may, có vẻ như các quy tắc đã thay đổi một lần nữa.

### dòng 2 (122 chars.)

Theo nghiên cứu mới của chúng tôi (tháng 5 năm 2018), giới hạn này là 155-160 ký tự. SEO nên thích ứng với những thay đổi này như thế nào?
Dòng 1 có phiên bản ngắn của câu chuyện và hy vọng người tìm kiếm biết họ đang đi đúng hướng. Dòng 2 đi sâu vào một vài chi tiết và cho đi chỉ đủ dữ liệu (hy vọng) là hấp dẫn. Nếu Google sử dụng mô tả dài hơn, nó sẽ hoạt động tốt, nhưng nếu không, chúng ta không nên tệ hơn khi mặc.

## Bạn có cần bận tâm không?

Đây có phải là nỗ lực đáng giá không? Tôi nghĩ rằng viết mô tả hiệu quả thu hút khách truy cập tìm kiếm vẫn rất quan trọng, theo lý thuyết (và điều này ảnh hưởng gián tiếp đến xếp hạng), nhưng bạn có thể thấy bạn có thể viết hoàn toàn tốt trong giới hạn 155 ký tự. Chúng ta cũng phải đối mặt với thực tế rằng Google dường như đang viết lại các mô tả ngày càng nhiều. Điều này rất khó để đo lường, vì nhiều lần viết lại là một phần, nhưng không đảm bảo rằng mô tả meta của bạn sẽ được sử dụng như được viết.

Có cách nào để biết khi nào một đoạn mã dài hơn (> 300 ký tự) sẽ vẫn được sử dụng? Một số SEO đã đưa ra giả thuyết một liên kết giữa các đoạn mã dài hơn và các đoạn trích nổi bật ở đầu trang. Trong tập dữ liệu tổng thể của chúng tôi, 13,3% trong tổng số SERP có đoạn trích nổi bật. Nếu chúng ta chỉ xem SERP có độ dài đoạn mã hiển thị tối đa là 160 ký tự (tức là không có kết quả nào dài hơn 160 ký tự), thì đoạn mã nổi bật xuất hiện là 11,4%. Nếu chúng ta xem xét SERP với ít nhất một đoạn mã hiển thị trên 300 ký tự, các đoạn trích nổi bật xảy ra với tỷ lệ 41,8%. Trong khi tập dữ liệu thứ hai là khá nhỏ, nó là một sự khác biệt nổi bật. Dường như có một số kết nối giữa khả năng trích xuất câu trả lời của tôi dưới dạng các đoạn trích nổi bật và khả năng hoặc sự sẵn lòng của họ để hiển thị các đoạn trích tìm kiếm dài hơn. Tuy nhiên, trong nhiều trường hợp, các đoạn mã dài hơn này được viết lại hoặc được lấy trực tiếp từ trang, vì vậy ngay cả khi đó, không có gì đảm bảo rằng Google sẽ sử dụng mô tả meta dài hơn của bạn.

Hiện tại, có vẻ như hướng dẫn 155 ký tự đang hoạt động trở lại. Nếu bạn đã tăng một số mô tả meta của mình, tôi không nghĩ có bất kỳ lý do gì để hoảng sợ. Nó có thể có ý nghĩa để viết lại các mô tả quá dài trên các trang quan trọng, đặc biệt là nếu các phần cắt giảm dẫn đến kết quả xấu. Nếu bạn chọn viết lại một số trong số chúng, hãy xem xét cách tiếp cận 150/150 - ít nhất thì bạn sẽ được kiểm chứng một chút trong tương lai.
