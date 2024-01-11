# Customer-Segmentation-by-RFMB

![](https://user-images.githubusercontent.com/96748659/155264097-23d03566-2c27-4aff-805e-731dfb595cd2.png)

## Overview

Trong project này tiến hành phân nhóm khách hàng (KH) của một ngân hàng thương mại dựa vào dữ liệu giao dịch và thông tin cá nhân KH.

Phương pháp thực hiện là RFMB:
- Recency (R): chênh lệch thời gian tính bằng ngày giữa ngày giao dịch cuối cùng của KH đến hôm sau ngày giao dịch cuối cùng trong data.
- Frequency (F): Tổng số lần giao dịch của KH.
- Monetary (M): Tổng số tiền giao dịch của KH.
- Balance (B): Số dư tài khoản trung bình hằng tháng vào cuối tháng.

Qua đó đạt được các mục tiêu sau:

- Nắm tình hình hoạt động chung của ngân hàng.
- Xác định các nhóm KH chính, nhóm KH chủ lực và đặc điểm của họ.
- Đưa ra cách tiếp cận, sản phẩm và dịch vụ thích hợp cho từng nhóm.
 
## Dataset

Dataset sử dụng trong bài là “Retail Banking Demo Data” lấy từ website [data.world](https://data.world/lpetrocelli/retail-banking-demo-data).

Bao gồm dữ liệu của hơn **1,000,000** giao dịch, , thông tin của **5,369** khách hàng, **682** khoản vay, thẻ tín dụng ...

Các file dataraw được sử dụng trong dataset này gồm có:
- completedtrans.
- completedclient.
- completedcard.
- completedloan.
- completeddisposition.
- completeddistrict.

## Tool

Trong bài sử dụng Power Query để thực hiện xử lý sơ bộ dữ liệu và load dữ liệu vào model.
Sau đó là Microsoft Power BI tạo model/schema, viết DAX và vẽ dashboard để thực hiện Descriptive Analysis.

## Sample Visualization

1. Tổng quan tình hình hoạt động Ngân hàng:

   ![image](https://github.com/dthcong/Customer-Segmentation-by-RFMB/assets/156085700/0b97993c-5f69-4e94-a803-1edce12fae9f)
   
2. Chi tiết về Khách hàng:

   ![image](https://github.com/dthcong/Customer-Segmentation-by-RFMB/assets/156085700/bc46d269-66bf-4e87-8356-c2f3df778ec0)

3. Chi tiết các Nhóm KH:

   ![image](https://github.com/dthcong/Customer-Segmentation-by-RFMB/assets/156085700/d2efbf8b-4100-4586-8a1b-ba8b74ae2d99)

## Result
- [File BPI dashboard](https://onedrive.live.com/?authkey=%21ACS6ieU16%2DwSoDg&cid=3F7295C15D4D67F4&id=3F7295C15D4D67F4%21109&parId=3F7295C15D4D67F4%21108&o=OneUp)
- [Insight](https://github.com/dthcong/Customer-Segmentation-RFMB/blob/main/Customer%20Segmentation%20RFMB%20-%20Insight.pdf)
