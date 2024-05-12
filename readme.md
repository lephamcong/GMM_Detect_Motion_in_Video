# Phát hiện đối tượng chuyển động trong video bằng GMM (Gaussian Mixture Models)

Đây là một dự án nghiên cứu áp dụng thuật toán phân cụm GMM để phát hiện đối tượng chuyển động trong video  

## Mô tả

Dự án này sử dụng thuật toán GMM để phát hiện đối tượng chuyển động dựa trên phép trừ nền.

## Cấu trúc thư mục

- `answer/`: Kết quả sau khi thực hiện phép trừ nền trên các frame
- `frame/`: Frame được tách từ video đầu vào 
- `frames_for_comparison/`: Tương tự thư mục `answer/`, nhưng các kết quả này được thực hiện bằng thư viện hỗ trợ dùng để so sánh
- `references/`: Source tham khảo về Gaussian Mixture Models từ [1]
- `report/`: Thư mục chứa source báo cáo latex
- `result/`: Thư mục chứa video kết quả
- `video/`: Thư mục chứa video đầu vào
- `GMM_Detect_Motion_in_Video.ipynb`: Tệp mã nguồn của dự án
- `MSE.csv`: Tệp giá trị Mean Square Error 
- `requirements.txt`: File liệt kê các thư viện Python cần thiết
- `README.md`: Tệp này

## Cách sử dụng

1. Clone repo:

```
git clone https://github.com/lephamcong/GMM_Detect_Motion_in_Video.git
```

2. Cài đặt các thư viện cần thiết:

```
pip install -r requirements.txt
```

3. Đặt ảnh đầu vào trong thư mục `iamge/`.

4. Chạy các code trong file GMM_Detect_Motion_in_Video.ipynb

Kết quả đầu ra sẽ được lưu trong thư mục `result/`.

## Tài liệu tham khảo

1. [Gaussian Mixture Models from Scratch in Python](https://towardsdatascience.com/how-to-code-gaussian-mixture-models-from-scratchin-python-9e7975df5252)
2. [Mean Squared Error (MSE)](https://statisticsbyjim.com/regression/mean-squared-error-mse/)
3. [Background Extraction from Videos Using Gaussian Mixture Models](https://medium.com/@prantiksen4/background-extraction-from-videos-usinggaussian-mixture-models-6e11d743f932) 


## Thông tin liên hệ

- Lê Phạm Công
- Email: lpc051002@gmail.com


Tệp README này cung cấp một tổng quan về dự án, cách sử dụng, cấu trúc thư mục, tài liệu liên quan và thông tin đóng góp. Nó giúp người dùng hiểu rõ hơn về mục đích, chức năng và cách triển khai dự án phát hiện đối tượng chuyển động trong video bằng GMM.