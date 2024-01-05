.before {
  position: relative;
}

.before::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100px; /* Thay đổi kích thước ảnh theo yêu cầu */
  height: 100px; /* Thay đổi kích thước ảnh theo yêu cầu */
  background-image: url("duong-dan-den-anh.jpg"); /* Thay đổi đường dẫn đến ảnh */
  background-size: cover; /* Tự động điều chỉnh kích thước ảnh để vừa với kích thước khung */
  /* Các thuộc tính khác để điều chỉnh vị trí và hiển thị của ảnh */
}
