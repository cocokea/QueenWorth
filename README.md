# QueenWorth

## Tổng Quan
QueenWorth là plugin giúp người chơi xem giá vật phẩm và bán item thông qua GUI.

Economy Core Server.

---

## Thông Tin Plugin
- Phiên bản: 1.0.0  
- Tác giả: maris7  
- Tương thích: Paper / Folia (1.21+)  
- Java: 21  
- Database: H2 / SQLite / MySQL  

---

## Lệnh

### Người chơi
/sell            - Mở GUI bán  
/worth           - Mở GUI xem giá  
/worth <item>    - Xem giá vật phẩm  
/sellhistory     - Xem lịch sử bán  
/sellmultip      - Xem hệ số bán  

### Admin
/sell reload     - Reload plugin  

---

## Quyền (Permissions)
queenworth.sell  
queenworth.worth  
queenworth.sellhistory  
queenworth.sellmultip  
queenworth.admin  
queenworth.toggleworth  

---

## Cấu Hình

### config.yml
settings:
  locale: "vi"        # vi / en
  inject-lore: true   # hiển thị giá trên item
  actionbar-worth: true

database:
  type: H2

---

## Ngôn Ngữ
Plugin hỗ trợ:
- locales/messages_vi.yml
- locales/messages_en.yml

---

## GUI
- guis/vi/*.yml  
- guis/en/*.yml  

---

## Hiển thị giá vật phẩm

- Hiển thị giá trực tiếp trên item trong inventory người chơi  

---

## PlaceholderAPI
%queenworth_totalsold%  
%queenworth_name_<pos>%  
%queenworth_value_<pos>%  

---

## Ghi chú
Nếu gặp lỗi hiển thị:
inject-lore: false

---

## License
All rights reserved.
