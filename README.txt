-------------------------------commit-01--------------------------------------------- 
change  : nav-bar
new     : category.scss
-------------------------------commit-02---------------------------------------------
add     : thêm thanh nav vào product--buy.html    
change  : thay đổi giao diện special-product, cập nhật special-product.scss
update  : update giao diện main-carousel khi rê chuột vào
-------------------------------commit-03---------------------------------------------
update  : product--buy cùng scss
-------------------------------commit-04---------------------------------------------
delete  : dots bên dưới card
fix     : subtitle viết trong 2 dòng để mang lại trải nghiệm tốt nhất
          hỉnh ảnh tự căng chỉnh linh hoạt
          phạm vi thay đổi: index.html, special-product.scss
-------------------------------commit-05---------------------------------------------
add     : giỏ hàng : product--cart.html và scss 
delete  : cart.html
-------------------------------commit-06---------------------------------------------
add     : nút đếm số
fix     : vị trí của components
-------------------------------commit-07---------------------------------------------
fix     : special-card, sale-card, normal-card category (giữ định dạng form khi sử dụng ảnh lớn và tiết title dài)
delete  : Xóa icon đăng kí trên thanh nav
        : Xóa product-item.html
        : Xóa thư mục component > Cart
        : Xóa thư mục component > hot-product
update  : Responsive chiều cao của banner khi ở chế độ di động
-------------------------------commit-08--------------------------------------------
update  : validation của checkout
new     : validator.js
update  : checkout.html, checkout.scss 
-------------------------------commit-09---------------------------------------------
fix     : giao diện (main-carousel, special-card, sale-card, normal-card)
update  : giao diện show ảnh 
update  : đưa danh mục sản phẩm trong giỏ hàng vào form
-------------------------------commit-10---------------------------------------------
fix     : giao diện sản phẩm trong category cùng vài chi tiết nhỏ
update  : nút scroll to top 
new     : link font awesome online trong các file html
-------------------------------commit-11---------------------------------------------
add     : chức năng đăng nhập + (đăng kí: chuẩn bị triển khai), thêm icon user
upadte  : thêm code LOGIN-MODAL trong tất cả các file html, 
        : cập nhật file validator.js, giờ đây tất cả các file html sẽ cần include file này  
new     : login.scss 
-------------------------------commit-12---------------------------------------------
new     : Khôi phục hot-item
new     : theme.scss, all-product.scss
update  : thay thế sale-product bằng all-item, chỉnh lại theme  (trong phạm vi index.html)
        : special card sẽ là thương hiệu, nhấp vào trỏ đến trang category(mang thương hiệu tương ứng)
          all-product có nút xem tất cả, nhấp vào trỏ đến trang category(tất cả sản phẩm)
-------------------------------commit-13---------------------------------------------
update  : product--buy (html & scss)
        : đổi màu footer(html & scss)
-------------------------------commit-14---------------------------------------------
update  : update theme
        : (phạm vi: html: index,  
                    scss: base, theme, header, footer, main-carousel, hot-product, special-product, 
                    all-product, normal-product) 
         Chủ yếu thay màu và đổi background
-------------------------------commit-15---------------------------------------------
new     : aos-animation.js, những khung chứa được set thuộc tính animation lúc scroll sẽ có thêm thuộc
          tính data-aos"" trong thẻ.
new     : <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">  
          <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
          <script src="./assets/js/bootstrap/aos-animation.js"></script>       
update  : Giao diện product--buy 
-------------------------------commit-16---------------------------------------------
update  : Giao diện product--cart
        : Giao diện checkout
        : Chỉnh lại nội dung footer 
          (chuẩn bị làm category)
-------------------------------commit-17---------------------------------------------
upadte  : Giao diện category 
        : Màu RGP động cho title trong all-product và category 
                scss: //GRADIENT-TEXT

        : Hoàn thiện form đăng ký và đăng nhập
                html: login-modal, signup-modal 
                scss: login.scss
                js  : validator.js
        : Làm lại nút mua hàng 
                html: submit-btn__wrap 
                scss:   //SUBMIT BUTTON
                        //RESPONSIVE SUBMIT BUTTON Ipad mode
-------------------------------commit-18---------------------------------------------
update  : chỉnh sửa phần responsive của product-overview và product--cart   
        : thẻ body trong base.scss thêm thuộc tính      min-height: 100vh;
                                                        display: flex;
                                                        flex-direction: column;
        : footer thêm thuộc tính margin-top: auto;
           (xử lý xong phần footer khi nội dung làm height của trang web)
        : responsive nav-icon
        : đổi màu hover cho thanh nav
        : đổi màu scroll-to-top và chỉnh opacity

new     : thanh nav cố định trên top 
        : header.scss: .header__background thêm thuộc tính      position: fixed;
                                                                z-index: 99; *chỉnh lại z-index: 9999 cho login.scss để ko bị lỗi 
                                                                height: 100px;
                                                                padding-top: 0 !important;
                                                                opacity: 90%;

        : trong basescss tạo thêm 1 lớp : .main-container       padding-top: 110px;
        : lớp mới sẽ dc thêm ở thẻ đầu tiên sau phần note <!-- MAIN----------------->(kết thúc container của header)

update  : login.scss    .login-modal    : z-index: 9999
                        .modal-content  : opaciry: 90%
-------------------------------commit-19---------------------------------------------
upadte  : thêm thuộc tính data-aos vào các thẻ để có animation load trang
-------------------------------commit-20---------------------------------------------
new     : giao diện khi không có hàng 
new     : product--null-cart.html scss

new     : nút thêm vào giỏ hàng | từ khóa: /*ADD-TO-CARD*/
update  : product--buy.html, scss
new     : addtocard-btn.js

update  : main.js | tắt tính năng lặp lại thương hiệu của special-card
-------------------------------commit-21---------------------------------------------
new     : product--cart-loginfirst.html
update  : product--cart.scss: submit-btn__wrap: margin-bottom: 20px; 
-------------------------------commit-22---------------------------------------------
new     : user.html 
        : user-dropdown.js
update  : header.scss | new     : /*USER-MODE*/
                        update  : .nav__top-signin:     display: flex;
                                                        justify-content: space-evenly;
                                                        align-items: center;
-------------------------------commit-23---------------------------------------------   
update  : header.scss | new     : container-fluid:      padding: 0;
                        update  : container--header:    width: 100%;      
                        update  : header__background:   width: 100%;                 