<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.1011.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FReportsexe%2F32410110-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FReportsexe%2F32410110-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FReportsexe%2F32410110-NasDHSolutions.json)

- 🐛: Sửa lỗi `Bảng 3` XML4750 không hiển thị dữ liệu cột `[don_gia_bh]`. ![image](https://github.com/user-attachments/assets/de2c020d-8138-4079-b659-38eec065cb42)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/139
## [v.3.24.1010.3]()
- 🐛: **💼**: **_Lỗi - GHI NHẬN SAI THÁNG QUYẾT TOÁN KHI IN BẢNG KÊ BỆNH NHÂN THÁNG CŨ_**
- 🐛: Chỉnh lỗi liên quan tới xuất XML4750 trên báo cáo Admin, Reports ![](https://i.imgur.com/1DKpyWX.png) ![](https://i.imgur.com/bn684Rf.png)![](https://i.imgur.com/ryo2V1I.png)![](https://i.imgur.com/NUJNtfn.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/172
## [v.3.24.1010.2]()
- 🐛: **💼**: **_Lỗi - BA TRẢ VỀ ĐIỀU TRỊ KẾT THÚC TẠI THÁNG MỚI GHI NHẬN SAI THÔNG TIN TRÊN 4750_**
- 🐛: Kiểm soát hồ sơ XML trường hợp trả về điều trị, cho xuất viện, thay đổi tháng ra viện ![](https://i.imgur.com/gGSup0k.png) ![](https://i.imgur.com/pqBY5NR.png) ![](https://i.imgur.com/4tT8wcp.png)
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/276
## [v.3.24.1010.1]()
- 🐛: **💼**: **_Lỗi - BA TRẢ VỀ ĐIỀU TRỊ KẾT THÚC TẠI THÁNG MỚI GHI NHẬN SAI THÔNG TIN TRÊN 4750_**
- 🐛: Kiểm soát hồ sơ XML trường hợp trả về điều trị, cho xuất viện, thay đổi tháng ra viện ![](https://i.imgur.com/gGSup0k.png) ![](https://i.imgur.com/pqBY5NR.png) ![](https://i.imgur.com/4tT8wcp.png)
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/276
## [v.3.24.1010.0]()

- ✨: Form xuất XML130 (QĐ4750): Bổ sung chức năng click phải xuất Excel mẫu C79-HD. ![image](https://github.com/user-attachments/assets/ae2d6275-7da0-4328-bf43-83ebc586637c)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/689
## [v.3.24.1009.2]()
- 🐛: **💼**: **_Lỗi - BANT ĐỢT KẾT THÚC KHÔNG CÓ HỒ SƠ KHI XUẤT 4750 _**
- 🐛: ***Chỉnh lỗi lấy thiếu hồ sơ trên so với báo cáo QĐ130*** ![](https://i.imgur.com/Hwdlwxq.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/349
## [v.3.24.1009.1]()

- 🐛: Sửa lỗi `bang2.cach_dung` có chứa thẻ <![CDATA[......]]>. ![image](https://github.com/user-attachments/assets/00c1a449-de0d-41ba-a051-2b5bd5bda7a1)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/138
## [v.3.24.1009.0]()
- ✨: **💼**: **_Mô tả và thực hiện hỗ trợ gởi bệnh nhân BANT thanh toán ngày XML1.ma_loai_kcb_**
- ✨: Thực hiện theo mô tả tham số ***`ma_loai_kcb.ba_ngoai_ngay`*** ![](https://i.imgur.com/FuxGUHO.png) ![](https://i.imgur.com/24t6x0q.png)
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/84
## [v.3.24.1008.0]()
- 🐛: **💼**: **_Lỗi - Admin, Report XM3 4750 không lấy được mã DỊCH VỤ khi cho Vật tư kèm theo**
- 🐛: ***Chỉnh lỗi: XML03.MA_DICH_VU, XML03.TEN_DICH_VU thiếu đối với những VTYT đánh theo CLS,DV*** ![](https://i.imgur.com/SkH5ZCH.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/103
## [v.3.24.1007.0]()

- ✨: Form xuất XML4750: Bổ sung chức năng load dữ liệu theo danh sách mã liên kết từ file Excel. Lưu ý: File Excel phải chứa cột [ma_lk] hoặc [malk] hoặc [Mã liên kết].
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/679
## [v.3.24.1005.0]()

- ✨: Form xuất XML4750: Bổ sung chức năng load dữ liệu theo danh sách mã liên kết từ file Excel. ![image](https://github.com/user-attachments/assets/0b19c880-9fad-49c3-bd7b-49b8f1d71a83)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/679
## [v.3.24.1004.4]()
- 🐛: **💼**: **_Lỗi - Report XML130 bảng 2 double số lượng thuốc_**
- 🐛: Chỉnh lỗi XML4750.bang2,3 bị tăng số lượng thuốc. ![](https://i.imgur.com/QgoL17P.png)
- ✨: ***Bổ sung chức năng xóa Hồ sơ XML4750 thừa (không nằm trong danh sách của 4210, chỉ áp dụng khi chọn Combo `Tất cả`, và không tìm theo Mã bệnh nhân, và chọn tất cả đối tượng )***
- ✨: ***Bổ sung cảnh báo khi có xóa hồ sơ thừa*** ![](https://i.imgur.com/Ba106vn.png)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/135
## [v.3.24.1004.3]()
- 🐛: **💼**: **_Lỗi - Report XML130 bảng 2 double số lượng thuốc_**
- 🐛: Chỉnh lỗi XML4750.bang3 bị tăng số lượng CLS và VTYT. ![](https://i.imgur.com/X06MDoL.png)
- Lưu ý: nếu cập nhật bản mới vẫn còn, thì vào chức năng ***`Kiểm tra chi chí lại`***
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/135
## [v.3.24.1004.2]()
- 🐛: **💼**: **_Lỗi - Report XML130 bảng 2 double số lượng thuốc_**
- 🐛: Chỉnh lỗi XML4750.bang2 bị tăng số lượng thuốc. ![](https://i.imgur.com/QgoL17P.png)
- Lưu ý: nếu cập nhật bản mới vẫn còn, thì vào chức năng ***`Kiểm tra chi chí lại`***
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/135
## [v.3.24.1004.1]()
- ✨: **💼**: **_Lỗi - BANT theo ngày khi kết thúc bệnh án thì tạo thêm XML130 có mã bệnh án làm tăng số lượng XML Reports (trùng dữ liệu XML)_**
- ✨: ***Bổ sung chức năng xóa hồ sơ thừa so với danh sách hồ sơ 4210 trên chức năng kiểm tra chi phí***
- ![](https://i.imgur.com/diz3Crb.png) ![](https://i.imgur.com/Jvc3xOV.png) ![](https://i.imgur.com/yBv8fyT.png) ![](https://i.imgur.com/dV92tXP.png) ![](https://i.imgur.com/NM5DcTh.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/341
## [v.3.24.1004.0]()

- 🐛: Sửa lỗi xuất Excel 3360 (form xuất XML4750) sai chi phí cột `t_cdha`.
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/134
## [v.3.24.1003.0]()
- 🐛: **💼**: **_Lỗi - XML130 không cấn trừ được thuốc trả_**
- 🐛: Chỉnh lỗi cấn trừ sai thuốc trả trên XML03 ![](https://i.imgur.com/YQG3XVy.png)
- ***Lưu ý, phải thực hiện công cụ sai chi phí lại trên Reports thì XML4750 mới tính lại đúng.***
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/132
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/101
## [v.3.24.1002.0]()
- 🐛: **💼**: **_Lỗi - CLS thuộc loại thủ thuật vẫn load vào xml4 4750(bv Ung Bướu)_**
- 🐛: Loại bỏ những CLS thuộc kho TT, PT ra ngoài danh sách XML04 ![](https://i.imgur.com/yrSEyJW.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/100
## [v.3.24.0930.1]()
- ✨: **💼**: **_Yêu cầu - Bổ sung nội dung diễn biến vào XML5.dien_bien_ls đối với xml4750 (BV Châu Thành Đồng Tháp) _**
- ✨: Thay đổi DIEN_BIEN_LS theo mô tả ![](https://i.imgur.com/e1MAHv7.png)
- ![](https://i.imgur.com/J4qyYT1.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/658
## [v.3.24.0930.0]()
- 🐛: **💼**: **_Lỗi - XML4 4750 không lấy được MA_BS_DOC_KQ cls thủ thuật (BV Ung Bướu)_**
- 🐛: Chỉnh lỗi không lấy được MA_BS_DOC_KQ đối với các dịch vụ có thực hiện PT, TT ![](https://i.imgur.com/aVRnMUl.png)
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/99
## [v.3.24.0925.0]()

- 🐛: Sửa lỗi double số lượng hồ sơ từ lần click [Kiểm tra chi phí so với XML 130] (trên form xuất dữ liệu XML4210).
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/99
## [v.3.24.0924.0]()

- ✨: Bổ sung chức năng cho phép cập nhật chi phí đối với người bệnh có hồ sơ XML130 không hợp lệ (`ma_doituong_kcb = 3.5` mà có chi phí `t_bncct`).
![image](https://github.com/user-attachments/assets/06ef36ef-31c6-4555-9c13-b46e9d0358e8)
![image](https://github.com/user-attachments/assets/d4b25887-cc82-4c52-a09e-b973b3fa9e99)
Lưu ý: dữ liệu hiện tại Bệnh viện cung cấp không đầy đủ thông tin. Nên chạy trên dữ liệu thực tế tại bệnh viện để kiểm chứng.
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/99
## [v.3.24.0918.1]()
- 🐛: **💼**: **_CHỨC NĂNG: KIỂM TRA CHI PHÍ GIỮA 4210 VAD QĐ 130 LỖI_**
- 🐛:![](https://i.imgur.com/BK7ZoSw.png)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/132
## [v.3.24.0918.0]()
- 🐛: **💼**: **_Hỗ trợ khách hàng - Không cập nhật được XML4750_**
- 🐛: Chỉnh năng lưu lại XML4750 mới, không xóa được thông tin các XML cũ trước đó.
- ![](https://i.imgur.com/80JsJBI.png) ![](https://i.imgur.com/RH0z4TX.png) ![](https://i.imgur.com/0Hfyv5R.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/100
## [v.3.24.0915.0]()

- 🐛: Sửa lỗi mẫu 21 ngoại trú thiếu số liệu so với bảng 3 dữ liệu XML4210.
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/130
## [v.3.24.0914.0]()

- ✨: Bổ sung xuất Excel 3360 tại form XML4750 theo 4750 và 4210. ![image](https://github.com/user-attachments/assets/0b705eaf-3075-4bef-abbe-b6bec849f7ca)
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/292
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/127
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/95
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0913.0]()

- ✨: Bổ sung trường hợp xuất Excel 3360 người bệnh chỉ có năm sinh.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/126
## [v.3.24.0912.0]()

- ✨: Form xuất dữ liệu XML4750 - Bổ sung chức năng tùy chọn (trước khi load dữ liệu) cho phép người dùng chọn load chi phí. ![image](https://github.com/user-attachments/assets/b40a5077-4bf0-48a0-8a65-b70b51a724f0)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/129
## [v.3.24.0911.0]()
- 🐛: **💼**: **_Yêu cầu - Admin và Report thống nhất cách lấy XML để đơn vị đối chiếu số lượng hồ sơ_**
- 🐛: Thống nhất lấy THANG_QT, NAM_QT giống 4210 (nội trú, bệnh án ngoại trú theo đợt lấy theo thangrv, namrv trong bnnoitru)
- 🐛: Chức năng kiểm tra hồ sơ sai giữa 4210 và 4750 theo THANG_QT và NAM_QT. ![](https://i.imgur.com/5FrT7sv.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/627
## [v.3.24.0910.6]()
- ✨: **💼**: **_💼 Reports - Hỗ trợ lấy XML4750 mới nhất cho tất cả hồ sơ đã lấy theo danh sách 4210 ⏳Dự kiến : 2024-09-11_**
- ✨: Thêm chức năng kiểm tra sai chi chi phí đối với tất cả hồ sơ 4210 theo danh sách đã lấy lên ![](https://i.imgur.com/0Catr61.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/642 
## [v.3.24.0910.5]()
- ✨: Bổ sung chức năng cập nhật ngay_ttoan, thang_qt và nam_qt theo yêu cầu: 
> * Thực hiện 2 option cho việc cập nhật ngay_ttoan như sau:
> 1. Đặt tháng trong ngay_ttoan theo thang_qt đã đặt (theo danh sách hồ sơ đang thống kê).
> 2. Cho đặt lại ngay_ttoan (người dùng tự chọn) tương tự như chức năng đặt lại thang_qt hiện có (theo danh sách hồ sơ đang thống kê).
![image](https://github.com/user-attachments/assets/35f762c5-12fc-44c5-a8a3-842f134044c7)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/636
## [v.3.24.0910.4]()
- ✨: Bổ sung chức năng cập nhật ngay_ttoan, thang_qt và nam_qt theo yêu cầu: 
> * Thực hiện 2 option cho việc cập nhật ngay_ttoan như sau:
> 1. Đặt tháng trong ngay_ttoan theo thang_qt đã đặt (theo danh sách hồ sơ đang thống kê).
> 2. Cho đặt lại ngay_ttoan (người dùng tự chọn) tương tự như chức năng đặt lại thang_qt hiện có (theo danh sách hồ sơ đang thống kê).
![image](https://github.com/user-attachments/assets/35f762c5-12fc-44c5-a8a3-842f134044c7)
## [v.3.24.0910.3]()
- ✨: Bổ sung chức năng cập nhật ngay_ttoan, thang_qt và nam_qt theo yêu cầu: 
> * Thực hiện 2 option cho việc cập nhật ngay_ttoan như sau:
> 1. Đặt tháng trong ngay_ttoan theo thang_qt đã đặt (theo danh sách hồ sơ đang thống kê).
> 2. Cho đặt lại ngay_ttoan (người dùng tự chọn) tương tự như chức năng đặt lại thang_qt hiện có (theo danh sách hồ sơ đang thống kê).
![image](https://github.com/user-attachments/assets/35f762c5-12fc-44c5-a8a3-842f134044c7)
## [v.3.24.0910.2]()

- ✨: Bổ sung chức năng cập nhật ngay_ttoan, thang_qt và nam_qt theo yêu cầu: 
> * Thực hiện 2 option cho việc cập nhật ngay_ttoan như sau:
> 1. Đặt tháng trong ngay_ttoan theo thang_qt đã đặt (theo danh sách hồ sơ đang thống kê).
> 2. Cho đặt lại ngay_ttoan (người dùng tự chọn) tương tự như chức năng đặt lại thang_qt hiện có (theo danh sách hồ sơ đang thống kê).
![image](https://github.com/user-attachments/assets/35f762c5-12fc-44c5-a8a3-842f134044c7)

- ✨: ![](https://i.imgur.com/eS7uh4L.png)
- ✨: **Chức năng kiểm tra hồ sơ**: Thực hiện lấy XML4750 lưu vào schema xml130 để hỗ trợ Reports lấy báo cáo

- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/636
## [v.3.24.0910.1]()

- ✨: Bổ sung chức năng cho phép đặt lại `tháng/năm` của các cột `ngay_ttoan`, `thang_qt`, `nam_qt` với các tùy chọn như hình. ![](https://i.imgur.com/kpBF3AV.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/636
## [v.3.24.0910.0]()

- ✨: Bổ sung chức năng cho phép đặt lại `tháng/nă`m của các cột `ngay_ttoan`, `thang_qt`, `nam_qt` với các tùy chọn như hình. ![](https://i.imgur.com/kpBF3AV.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/636
## [v.3.24.0909.1]()

- ✨: Điều chỉnh cách load dữ liệu XML4210; Điều chỉnh cách kiểm tra chi phí giữa XML4210 và XML4750, bổ sung cột [Hồ sơ trùng] của XML4750 ![image](https://github.com/user-attachments/assets/d43adb83-7504-459f-b05f-2a2db1b9e6ab)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/630
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/627
## [v.3.24.0909.0]()

- ✨: Bổ sung điều kiện để loại bỏ các hồ sơ không có chi phí.
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/123
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/122
## [v.3.24.0906.0]()

- 🐛: Điều chỉnh điều kiện cột `ngay_sinh` khi xuất dữ liệu `Excel 3360`, chỉ lấy 8 ký tự bên trái cột `bang1.ngay_sinh`.
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/126
## [v.3.24.0830.1]()

- 🐛: Sửa lỗi xuất Excel 3360 thiếu cột `tinh_trang_rv`.
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/125
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0830.0]()

- ✨: Bổ sung chức năng load dữ liệu 4750 theo mã bệnh nhân. ![image](https://github.com/user-attachments/assets/a8378419-8594-4d20-a8bd-01afc44539fe)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577 
## [v.3.24.0826.0]()

- 🐛: Sửa lỗi xuất Excel 3360 (theo XML4750). ![image](https://private-user-images.githubusercontent.com/130281806/360785826-d8989015-914e-48e0-9519-94fa75d178e6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjQ2MzM5ODksIm5iZiI6MTcyNDYzMzY4OSwicGF0aCI6Ii8xMzAyODE4MDYvMzYwNzg1ODI2LWQ4OTg5MDE1LTkxNGUtNDhlMC05NTE5LTk0ZmE3NWQxNzhlNi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwODI2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDgyNlQwMDU0NDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mMjUxNzhlYjRmM2EzNzU3OGQ0YzhlNTcwZTRkMTFiODNmNjFjZDE1Njk2MGI4YjExMGM4MDkzODE4ZWE4ZDZlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.XLkcyrRsewFxdPXXkQ5TpWgyPs4JK-wTEsUguA3rbc8)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0822.0]()

- 🐛: Sửa lỗi không load được dữ liệu XML4750.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0821.0]()

- 🐛: Sửa lỗi không load được dữ liệu XML4750.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0818.0]()

- ✨: Bổ sung báo cáo xuất XML130, xuất dữ liệu Excel 3360 và mẫu C79-HD theo QĐ4750.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/580
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/577
## [v.3.24.0816.0]()

- 🐛: Sửa lỗi ghi nhận sai chi phí đối với thuốc nội trú có toa trả.
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/43
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/231
<<<<<<< HEAD
## [v.3.24.0816.2]()

- 🐛: Sửa lỗi ghi nhận sai chi phí đối với thuốc nội trú có toa trả.
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/43
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/231
## [v.3.24.0816.1]()

- 🐛: Sửa lỗi ghi nhận sai chi phí đối với thuốc nội trú có toa trả.
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/43
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/231
## [v.3.24.0816.0]()

- 🐛: Sửa lỗi ghi nhận sai chi phí đối với thuốc nội trú có toa trả.
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/43
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/231
=======
## [v.3.24.0811.0]()
- ✨: Yêu cầu - Hỗ trợ hàm kiểm tra thông tuyến theo Công văn 1923/BHXH-CNTT ngày 20/06/2024
- ✨: Mô tả thực hiện [Ham API tra cuu TT - theo CV 1923-BHXHVN.md
](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Ham%20API%20tra%20cuu%20TT%20-%20theo%20CV%201923-BHXHVN.md)
- ✨:  + Chuyển hàm sử dụng thông tuyến KQNhanLichSuKCB2024 (Không theo cấu hình trên Admin)
- ✨:  + Sử dụng tài khoản kiểm tra theo tài khoản đăng nhập, điều kiện cụ thể để tài khoản có thể sử dụng tra cứu là có tài khoản BHXH cung cấp khác rỗng, có họ lót và Số CCCD
- ✨:  + Trường hợp tài khoản đăng nhập không hợp lệ, sẽ tìm theo tài khoản được cấu hình theo khoa, và theo bệnh viện trên Danh mục Nhân viên
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/565
>>>>>>> 320f8894a66e4d701e5c4dcec35b483d54ca6c04
## [v.3.24.0808.0]()

- 🐛: Sửa lỗi: XML 4210 tính sai tiền BNCCT và BHTT (BV Tim Mạch AG).
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/124
## [v.3.24.0712.0]()

- ✨: Sổ TT/PT theo [Mô tả thực hiện Thủ thuật/Phẫu thuật đối với Cận lâm sàng](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20th%E1%BB%B1c%20hi%E1%BB%87n%20Th%E1%BB%A7%20thu%E1%BA%ADt-Ph%E1%BA%ABu%20thu%E1%BA%ADt%20%C4%91%E1%BB%91i%20v%E1%BB%9Bi%20C%E1%BA%ADn%20l%C3%A2m%20s%C3%A0ng.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/455
## [v.3.24.0710.0]()

- ✨: Mở chức năng báo cáo bệnh nhân HIV có thanh toán chi phí nguồn khác.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/462
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/121
## [v.3.24.0708.0]()

- 🐛: Sửa lỗi khi load dữ liệu mẫu 21 ngoại trú và mẫu 21 tổng hợp.
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/119
## [v.3.24.0704.0]()

- 🐛: Fix lỗi mất menu báo cáo Quý/năm đối với đơn vị sử dụng tham số tknoitru = 0.
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/118
## [v.3.24.0703.0]()

- ✨: Thay đổi cách lấy các mã địa phương sang dmxa4750.
- ☑: https://github.com/dh-hos-code/DH.ThongTinKSK/issues/7
## [v.3.24.0701.0]()

- ✨: Thực hiện theo yêu cầu chi tiết tại: Biên bản họp `NAS: \DuLieuCongTy\Van Ban Ban Hanh\Bien ban hop\BienBanHop_20240627_Nhom.pdf`.
![image](https://github.com/dh-hos/Mo-ta-he-thong/assets/112069710/6a6f56f8-f21a-48b2-8afb-2238ce21279b). Chi tiết tại mô tả: [CÁCH GHI NHẬN GIÁ TRỊ CỘT XML3.MA_BENH (cột 26, bảng 3 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/M%C3%B4%20t%E1%BA%A3%20XML4210%20-%20XML3.MA_BENH.md)
## [v.3.24.0629.0]()

- ✨: Bổ sung tiêu chí thời gian xem báo cáo. ![image](https://github.com/dh-hos/To_Lap_Trinh/assets/112069710/3d202ebc-f532-46f0-8406-83ab4faf8610)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/373
## [v.3.24.0625.0]()

- 🐛: Sửa lỗi xuất báo cáo quí năm mẫu 26aTH.
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/117
## [v.3.24.0622.0]()

- ✨: Thay đổi cách tính chi phí theo quy trình trả thuốc/VTYT người bệnh nội  trú. Theo mô tả [MÔ TẢ QUY TRÌNH TRẢ THUỐC/VTYT NGƯỜI BỆNH ĐIỀU TRỊ NỘI TRÚ](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20Quy%20tr%C3%ACnh%20tr%E1%BA%A3%20thu%E1%BB%91c-VTYT%20b%E1%BB%87nh%20%C3%A1n%20n%E1%BB%99i%20tr%C3%BA.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/406
## [v.3.24.0620.2]()

- ✨: Bổ sung form so sánh chi phí XML4210 với 4750.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/372
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
## [v.3.24.0620.1]()

- ✨: Bổ sung form so sánh chi phí XML4210 với 4750.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/372
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
<<<<<<< HEAD
## [v.3.24.0620.0]()

- ✨: Bổ sung form so sánh chi phí XML4210 với 4750.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/372
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
=======
## [v.3.24.0619.0]()
- 🐛: Fix lỗi trùng hồ sơ chuyển viện ![](https://i.imgur.com/Rw1iliX.png)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/116
## [v.3.24.0617.0]()
- 🐛: Fix lỗi chọn ngày bắt đầu và kết thúc khi chọn combo loại báo cáo
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/116
>>>>>>> 10d3ac254f31862dc56dbae3b8cdf6d7bf3f8605
## [v.3.24.0613.1]()
- 🐛: Lỗi - Danh sách chuyển viện ngoại trú thống kê phiếu chuyển viện đã xóa
- ![](https://i.imgur.com/5be5ALe.png)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/116
## [v.3.24.0613.0]()

- 🐛: Sửa lỗi lấy sai ma_lydo_vvien.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0612.0]()

- 🐛: Sửa lỗi lấy sai ma_lydo_vvien.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0611.1]()

- ✨: Thực hiện [CHỦ ĐỀ: CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md), cập nhật điều kiện xét thứ tự thứ 7
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0611.0]()

- ✨: Thực hiện [CHỦ ĐỀ: CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0606.0]()

- ✨: Fix lỗi mất logo
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/68
## [v.3.24.0529.0]()

- ✨: Thực hiện theo mô tả [CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md) để xác định MA_LYDO_VVIEN
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/12