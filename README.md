`	`THÔNG TIN DỮ LIỆU THU THẬP

\# Information Data: Thu thập dữ liệu các thông số yêu tố ảnh hưởng tới tim của một nhóm người.

\# Số cột, hàng: 14 cột và 1025 hàng

\# Giải thích tên biến:

- age: tuổi tính theo năm ( độ tuổi từ 29 - 56)

- sex: giới tính (1: nam, 0: nữ)

- cp - 'check\_pain\_type': các loại đau thắt ngực:

\+ Giá trị 0 - đau điển hình: (1) đau dưới ngực

`				`(2) sự khó chịu khi bị kích động

`			        `(3) căng thẳng cảm xúc

`				`=> Giảm triệu chứng bằng cách nghỉ ngơi hoặc sử dụng thuốc nitroglycerine (hoặc cả hai).

\+ Giá trị 1 - đau không điển hình: khi có 2 trong 3 triệu chứng của đau điển hình.

\+ Giá trị 2 - đau ngực không đặc hiệu: có ≤ 1 trong các triệu chứng của đau điển hình, triệu chứng không rõ ràng.

\+ Giá trị 3 : Không có triệu chứng.

- trestbps - 'resting\_bool\_pressure': huyết áp lúc nghỉ (mm Hg)

\+ Huyết áp bình thường: Đối với người lớn, huyết áp tâm thu dưới 120mmHg và huyết áp tâm trương dưới 80mmHg thì được gọi là huyết áp bình thường.

\+ Huyết áp cao: Khi huyết áp tâm thu từ 140 mmHg trở lên hoặc huyết áp tâm trương từ 90 mmHg trở lên thì chẩn đoán là cao huyết áp.

\+ Tiền cao huyết áp: Giá trị nằm giữa huyết áp bình thường và cao huyết áp (Huyết áp tâm thu từ 120-139 mmHg

`			`hoặc huyết áp tâm trương từ 80-89 mmHg) thì được gọi là tiền cao huyết áp.

\+ Huyết áp thấp: (Hạ huyết áp) huyết áp thấp được chẩn đoán khi huyết áp tâm thu dưới 100 mmHg.

- chol - 'cholesterol': cholestoral trong huyết thanh tính bằng (mg / dl)

- fbs - 'fasting\_blood\_sugar': đường huyết lúc đói

\+ ≤ 120: bình thường (0 : false)

\+ > 120: có nguy cơ bị tiểu đường có thể dẫn đến bị bệnh tim mạch gây ra các cơn đau thắt ngực (1: true)

- restecg - 'rest\_electrocardiographic': kết quả điện tâm đồ lúc nghỉ ngơi

\+ Giá trị 0: bình thường

\+ Giá trị 1: Có bất thường sóng ST ST-T (phắc phẫu sóng T và / hoặc độ cao hoặc trầm cảm của ST> 0,05 MV)

\+ Giá trị 2: hiển thị phì đại thất trái có thể xảy ra hoặc xác định bởi các tiêu chí của Estes

- thalach:  nhịp tim tối đa đạt được (BPM: nhịp trên phút)

- exang - 'exercise\_included\_angina': đau thắt ngực do vận động (chỉ xảy ra do vận động) (1: có, 0: không)

- oldpeak: độ chênh lệch của đoạn ST gây ra do tập thể dục liên quan đến nghỉ ngơi (mm)

Đoạn ST bình thường khi 75% đoạn ST nằm trên đường đẳng điện, nếu chênh lên thì không quá 0.1 mV và chênh xuống không quá 0.05 mV.

Nói chung là đoạn ST không uống cong mà đi thẳng và tiếp một cách mềm mại vào T, cũng không bao giờ đi xuống dốc mà chỉ đi ngang hoặc hơi dốc lên.

- slope - 'ST-slope': độ dốc của đoạn ST tập thể dục đỉnh cao

\+ Giá trị 0: dốc lên

\+ Giá trị 1: phẳng

\+ Giá trị 2: dốc xuống

- ca: số lượng mạch chính quan sát được khi quang nội soi bằng huỳnh quang

- tha - 'thalassemia': bệnh tan máu bẩm sinh

\+ Giá trị 0: lỗi (trong bộ dữ liệu ban đầu 0 bản đồ đến Nan's)

\+ Giá trị 1: khiếm khuyết cố định (không có lưu lượng máu ở một số phần của tim)

\+ Giá trị 2: lưu lượng máu bình thường

\+ Giá trị 3: khiếm khuyết có thể hồi phục (quan sát thấy dòng máu chảy nhưng không bình thường)

- target: chẩn đoán bệnh tim (0: không bệnh, 1: bệnh)

