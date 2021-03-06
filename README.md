# USB-BOOT
Tạo usb boot cứu hộ cho USB, ổ cứng di động

Trên mạng có rất nhiều USB boot của các tác giả khác nhau, tùy bạn thích chọn của ai cũng được!

# SOURCE TẠO USB BOOT #

**[Anhdv Boot](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EfgG7L55mpdGpQoPqu5NWDgBYplrIQDJ8HEAnIqn3pmXFA?e=9mkbzn)**

**[NasiBoot](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EXYpxe6W2DNEo0U21xzuQN4BC26MgoxdirwHHiQ_MPNm6Q?e=LpW8rK)**

**[MCboot](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EQlvuZHJAu5Ph6_St46PwWcBtTikfEbIijwWvdnZQT5zxQ?e=Wcr2Nt)**

**[Hiren Boot](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EdeQLS4YD1dPpWt56jx-hDkB_79VBYVB_vnBmZS8zlgg5g?e=OgZ3a5)**

**[NHV Boot](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EeDVbDKDngNOhW5TdDaPPHIBk8GPc8OQAmUc7pHr1iJnPA?e=THUOh2)**

**[HKBoot](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EUsXa9z3n0xOr9fPniFm9GoB6cslVjpnCbSUpqCfuVa1xw?e=2nJYE2)**

**[Một số source khác](https://bsthanh-my.sharepoint.com/:t:/g/personal/laptopxiaomi_bsthanh_tk/EYpb9TWF0HZCmIdOoofHwTcBoXS2pRHfdK_R4kjadUGDtQ?e=aBbdtm)**

# TẠO BOOT CHO USB BẰNG REFUS #

Dùng [Refus.exe](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EXuFKvk2Er9Gjzn25U7wds8BtwbexjvBw1fwNXgsI3cRLA?e=cjtZYb) tạo boot cho USB thật tiện lợi.

Bước 1: Mở Rufus, thiết lập thông số tạo USB boot, tại giao diện của Rufus, mục Device, bạn chọn USB của mình. Trong Boot selection bạn chọn Disk or ISO image, rồi nhấn SELECT để duyệt và chọn file ISO.

![1](https://user-images.githubusercontent.com/82578024/165204562-d28da8f8-28b6-4fcb-b040-c4e6796b6522.jpg)

Trong Image option, bạn chọn Standard Windows installation, trong Partition scheme thì chọn MBR hoặc GPT tùy thuộc [máy của bạn hỗ trợ BIOS hay UEFI](https://quantrimang.com/lam-the-nao-de-kiem-tra-xem-windows-khoi-dong-o-che-do-uefi-hay-legacy-bios-127546). Mục File System, hãy để là NTFS, sau đó nhấn Start để bắt đầu.

![1](https://user-images.githubusercontent.com/82578024/165204945-709c46ac-ad7c-43cc-b1f7-37e716784f2f.jpg)

![1](https://user-images.githubusercontent.com/82578024/165205028-70c4d5ee-171f-49f7-8f7d-09b7f36b3ef2.jpg)


Bước 2: Xác nhận xóa dữ liệu cũ trên USB, hộp thoại cảnh báo USB sẽ format, nếu bạn có dữ liệu quan trọng thì hãy copy vào máy tính trước. Nếu không, hãy bấm OK để tiếp tục.

![1](https://user-images.githubusercontent.com/82578024/165205177-6bacd038-6ef5-49d3-8c8c-ef101f483a5d.jpg)

Bước 3: Quá trình tạo USB cài Windows sẽ diễn ra

![1](https://user-images.githubusercontent.com/82578024/165205472-a4ceaf1a-51db-4391-91c2-0a26ec0eca30.jpg)

Bước 4: Hoàn tất quá trình tạo USB boot, khi chương trình hiện nút Ready tức là đã xong, hãy nhấn Close để kết thúc quá trình cài đặt. Bây giờ, các bạn có thể tiến hành sử dụng USB của mình được rồi.

![1](https://user-images.githubusercontent.com/82578024/165205633-294ce064-9b23-4254-8fb4-a892bf032fb7.jpg)

Như vậy, các bạn đã biết cách tạo USB cài/boot Windows bằng phần mềm Rufus rồi đấy. Có thể thấy rằng việc tạo USB boot bằng Rufus khá đơn giản đúng không nào. Để tránh gặp lỗi khi tạo USB boot với Rufus, bạn cần chọn đúng file ISO phù hợp với máy khi tải về (bản 32bit hoặc 64bit). 

# TẠO BOOT CHO Ổ CỨNG DI ĐỘNG #

![1](https://user-images.githubusercontent.com/82578024/165237549-0a3579a7-2135-47b2-aba7-ce8c6c392a10.jpg)

**Refus không thể đáp ứng trong trường hợp này, vì nó sẽ format tất cả dữ liệu trong ổ cứng di động cho dù bạn có chia nó làm nhiều đĩa**

**Đầu tiên phân ổ đĩa cứng thành một ổ nhỏ khoản 8-16G để làm Boot khởi động với định dạng FAT32 và Primery bằng cách dùng [Partition Wizard Portable 12](https://bsthanh-my.sharepoint.com/:u:/g/personal/laptopxiaomi_bsthanh_tk/ETHjOWXpzY5OgarnNd0FTY8BJ7_dgt5lyrKqtS9DRVuavA?e=4ZN1AO) nếu chưa biết dùng tham khảo [tại đây](http://thuthuatphanmem.vn/cach-chia-phan-vung-o-cung-bang-phan-mem-minitool-partition-wizard/)**

Tiếp theo: Copy tất cả những gì có trong file NHV-BOOT-2022-945-EXTREME.iso hoặc các file iso boot winPE vào ổ đó.

## NẠP BOOT CHO NÓ BẰNG BOOTICE ##

Download [Bootice64.exe](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EaFJKBx0CvNElH3axAP55u8BmlOcaKoTbp-QhokXgc12CA?e=IlA5HU) hoặc [Bootice32.exe](https://bsthanh-my.sharepoint.com/:u:/g/personal/0914678254_bsthanh_tk/EYziEj9EIMZGg3tJhGx0K_IBPE0gEMrAJhueM9k2fRBA1w?e=v7Kz2J) để nạp MBR và nạp boot cho nó

Mở Bootice lên:

![1](https://user-images.githubusercontent.com/82578024/165209316-cbf4ce94-52d2-411f-ad67-0268e1468c70.jpg)

Sổ xuống chọn ổ đĩa cần tạo boot, chọn Process MBR

![1](https://user-images.githubusercontent.com/82578024/165209756-92724e93-049f-4a34-afe9-380e1c4d9eea.jpg)

Chọn vào mục Windows NT 5.x / 6.x MBR, chọn Install /Config

Bảng thông báo hiện lên, bạn chọn Windows NT 6.x MBR, và OK để hoàn tất.

![1](https://user-images.githubusercontent.com/82578024/165209937-ed84ded5-e82c-47c4-8874-4f1f933b9717.jpg)

Nạp PBR cho usb boot uefi legacy: PBR sẽ có nhiệm vụ quản lý khả năng boot của mỗi phân vùng của thiết bị.

![1](https://user-images.githubusercontent.com/82578024/165210156-28a42ef2-3f9d-4860-ab4d-2079db3eb30f.jpg)

Khởi động BootIce, chọn Process PBR

![1](https://user-images.githubusercontent.com/82578024/165210484-fd6df592-2a8f-4147-8680-93af52ab2361.jpg)

Chọn phân vùng cần nạp PBR, trong hình trên USB của tôi đã chia làm 2 phân vùng. Vì thế tôi sẽ chọn phân vùng USB-Boot để nạp PBR. Nạp PBR cho phân vùng USB-Boot là GRUB4DOS.

![1](https://user-images.githubusercontent.com/82578024/165210735-29fa982b-cf1f-4462-ac42-92fdc06cf9db.jpg)

Bước này, bạn để mặc định và bấm OK để xác nhận. Như vậy, chúng ta đã nạp  boot cho phân vùng thành công.
