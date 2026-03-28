# Ứng Dụng Look & Tell Chính Thức
![Java](https://img.shields.io/badge/Language-Java-ed8217?logo=java)
![Android Studio](https://img.shields.io/badge/IDE-Android%20Studio-3DDC84.svg?logo=androidstudio)
![Tensorflow](https://img.shields.io/badge/Framework-Tensorflow-important?logo=tensorflow)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/khooinguyeen/Sign-Language-Translation/blob/main/Sign%20Language%20Translator/Demo/lookandtell.png">
    <img src="https://github.com/khooinguyeen/Sign-Language-Translator/blob/main/Sign%20Language%20Translator/Demo/lookandtell.png" width="400">
  </a>

  <h3 align="center">Look & Tell - Nhìn Và Kể</h3>

  <p align="center">
    Ứng dụng hỗ trợ dịch ngôn ngữ ký hiệu Việt Nam 
    <br />
    <a href="https://github.com/khooinguyeen/LookandTell-OfficialApp"><strong>Khám phá tài liệu »</strong></a>
    <br />
    <br />
    <a href="https://github.com/khooinguyeen/LookandTell-OfficialApp">Xem Demo</a>
    ·
    <a href="https://github.com/khooinguyeen/LookandTell-OfficialApp/issues">Báo cáo Lỗi</a>
    ·
    <a href="https://github.com/khooinguyeen/LookandTell-OfficialApp/issues">Yêu cầu Tính năng</a>
  </p>
</div>

<details>
  <summary>Mục lục</summary>
  <ol>
    <li>
      <a href="#về-dự-án">Về Dự Án</a>
      <ul>
        <li><a href="#công-nghệ-sử-dụng">Công Nghệ Sử Dụng</a></li>
      </ul>
    </li>
    <li>
      <a href="#bắt-đầu">Bắt Đầu</a>
      <ul>
        <li><a href="#mô-hình">Mô Hình</a></li>
        <li><a href="#yêu-cầu-cần-thiết">Yêu Cầu Cần Thiết</a></li>
        <li><a href="#cài-đặt">Cài Đặt</a></li>
      </ul>
    </li>
    <li><a href="#liên-hệ">Liên Hệ</a></li>
    <li><a href="#ghi-nhận">Ghi Nhận</a></li>
  </ol>
</details>

## Về Dự Án

Câu chuyện bắt đầu khi Kiệt (hàng xóm của tôi) - một bé khiếc từ khi sinh ra, không thể nghe thấy tiếng mẹ. Trong 10 năm qua, tôi chứng kiến hàng ngày bé gái này gặp khó khăn trong việc biểu đạt những mong muốn đơn giản nhất của một đứa trẻ tiểu học.

Tìm hiểu về cộng đồng khiếc và khiếm thính, trên toàn thế giới có **1,5 tỷ** người bị mất hoặc suy giảm thính lực, và tại Việt Nam có **2,5 triệu** người - một cộng đồng rất lớn! Tuy nhiên, điều này tạo ra gánh nặng kinh tế khổng lồ cho các quốc gia. Theo báo cáo năm 2015 của WHO, chi phí điều trị mất hoặc suy giảm thính lực dao động từ 750 đến 790 tỷ USD. Đến năm 2019 sẽ vượt quá 981 tỷ USD (theo Global Burden Disease), chủ yếu do chi phí cộng đồng và xã hội. 

Ở Việt Nam, số lượng thông dịch viên ngôn ngữ ký hiệu có trình độ chỉ khoảng **20** người, và không có sản phẩm hỗ trợ giao tiếp hợp lý (chỉ có 1 sản phẩm được sản xuất bởi sinh viên Đại học Khoa học Tự nhiên TP.HCM nhưng cần thêm thiết bị có chi phí gần 1 triệu VND). Theo khảo sát **250** người bao gồm những người khiếc và khiếm thính, gần **100%** mong muốn có một cây cầu nối kết và thực sự cần một sản phẩm hỗ trợ giao tiếp.

Với mong muốn giao tiếp với Kiệt cũng như tất cả những người khiếc và khiếm thính trên thế giới, chúng tôi đã quyết định thực hiện dự án này - tạo ra một ứng dụng dịch ngôn ngữ ký hiệu.

<p align="right">(<a href="#top">về đầu trang</a>)</p>


### Công Nghệ Sử Dụng

* [Android Studio](https://developer.android.com/)
* [Tensorflow Lite](https://www.tensorflow.org/lite)
* [Mediapipe](https://mediapipe.dev/#!)

<p align="right">(<a href="#top">về đầu trang</a>)</p>

## Bắt Đầu

### Mô Hình
* Ứng dụng này bao gồm 3 mô hình: hand_landmark.tflite, palm_detection.tflite, model.tflite nằm trong thư mục `assets` và `ml`

* Truy cập [Sign Language Translation](https://github.com/khooinguyeen/Sign-Language-Translation) để tải xuống mô hình và xem cách chúng tôi xây dựng mô hình 

### Yêu Cầu Cần Thiết
* Android Studio 3.2 (được cài đặt trên máy tính Linux, Mac hoặc Windows)
* Thiết bị Android ở [chế độ nhà phát triển](https://developer.android.com/studio/debug/dev-options) với gỡ lỗi USB được bật
* Cáp USB (để kết nối thiết bị Android với máy tính của bạn)

### Cài Đặt

**Dưới đây là hướng dẫn cài đặt và thiết lập ứng dụng của bạn:**

**Bước 1: Clone kho lưu trữ**

Clone kho lưu trữ GitHub Look & Tell vào máy tính của bạn.
   ```sh
   git clone https://github.com/khooinguyeen/LookandTell-OfficialApp
   ```

Mở mã nguồn Look & Tell trong Android Studio. Để làm điều này, hãy mở Android Studio và chọn `Open`, đặt thư mục thành `../LookandTell-main/LookandTell/app`

<p align="right">(<a href="#top">về đầu trang</a>)</p>

**Bước 2: Xây dựng dự án Android Studio**

Chọn `Build -> Make Project` và kiểm tra xem dự án có xây dựng thành công không. Bạn sẽ cần cấu hình Android SDK trong cài đặt. Bạn cần ít nhất phiên bản SDK 23. Tệp `build.gradle` sẽ nhắc bạn tải xuống bất kỳ thư viện nào bị thiếu.

![](LookandTell/Demo/build.png)
  
**Bước 3: Cài đặt và chạy ứng dụng**

Kết nối thiết bị Android với máy tính và đảm bảo phê duyệt bất kỳ lời nhắc quyền ADB nào xuất hiện trên điện thoại của bạn. Chọn `Run -> Run app`. Chọn mục tiêu triển khai trên các thiết bị được kết nối với thiết bị trên đó ứng dụng sẽ được cài đặt. Điều này sẽ cài đặt ứng dụng trên thiết bị.

![](LookandTell/Demo/run.png)

<p align="right">(<a href="#top">về đầu trang</a>)</p>

## Liên Hệ

**Thông tin dự án:**

- **Họ và Tên:** Nguyễn Nhật Thiện
- **Lớp:** 9D4
- **Trường:** THCS Nguyễn Huệ
- **Email:** khoinguyenmai17102005@gmail.com

**Liên kết Dự án:**

- [Look & Tell App](https://github.com/khooinguyeen/LookandTell-OfficialApp)
- [Sign Language Translation](https://github.com/khooinguyeen/Sign-Language-Translation)

<p align="right">(<a href="#top">về đầu trang</a>)</p>

## Ghi Nhận

Cảm ơn tất cả những người đã hỗ trợ và cống hiến cho dự án này.
