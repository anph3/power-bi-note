### power-bi-note

    1. Để sử dụng API Power BI REST, bạn cần đăng ký ứng dụng Azure Active Directory (Azure AD) trong Azure.
    
    2. Phạm vi không bắt buộc nếu bạn đang sử dụng dịch vụ chính . Sau khi bạn kích hoạt dịch vụ chính để sử dụng với Power BI, quyền AD của ứng dụng sẽ không còn hiệu lực nữa. Khi sử dụng dịch vụ chính, các quyền của ứng dụng sẽ được quản lý thông qua cổng quản trị Power BI. Để biết thêm thông tin, hãy xem Bật cài đặt quản trị viên dịch vụ Power BI .
    
    3. Để thêm quyền vào ứng dụng Azure AD của bạn, hãy làm theo các bước sau:
      - Mở ứng dụng của bạn trong Azure.
      - Ở bên trái, trong phần Quản lý , chọn quyền API .
      - Chọn Thêm quyền .
      - Trong cửa sổ Yêu cầu quyền API , chọn Dịch vụ Power BI .
      - Chọn Quyền được ủy quyền . Một danh sách các API được hiển thị.
      - Mở rộng API bạn muốn thêm quyền và chọn các quyền bạn muốn thêm vào đó.
      - Chọn Thêm quyền .
