##Báo cáo học chuổi  
 
[IKhái Niệm Chuỗi Con Trỏ](#Chuỗi_con_trỏ)  
[II.Thao tác của chuỗi](#Thao_tác_của_chuỗi)  
[III.Mảng Và Chuỗi Ký Tự](#Mảng_và_chuỗi_ký_tự)  

<a name Chuỗi_con_trỏ><a\>  
###I.Khái Niệm Chuỗi Con Trỏ  
**1.Khái niệm**  
- chuỗi là 1 dãy kí tự
- kiểu char
- \0 = null = kết thúc chuỗi.Thực tế, bạn không đặt ký tự null tại vị trí cuối cùng của biến hằng số. Bộ biên dịch C tự động thêm.  

**2.Khai báo**  
``` `Char tên[]` hoặc `Char *tên` ```  
  
<a name Thao_tác_của_chuỗi><a\>  
###II.Thao Tác Của Chuỗi  
**Sử dụng các hàm chuẩn trong thư viện**    
- **Hàm strlen:** `int strlen(char s[])`  
*Trả về độ dài của chuỗi s, chính là chỉ số của ký tự NULL trong chuỗi.*  
- **Hàm strcpy:** `strcpy(char dest[], char source[])`  
*Sao chép nội dung chuỗi source vào chuỗi dest.*  
- **Hàm strchr:** `char *strchr(char s[], char c)`  
*Tìm lần xuất hiện đầu tiên của ký tự c trong chuỗi s, trả về địa chỉ của ký tự này.*  
- **Hàm strncpy:** `strncpy(char dest[], char source[], int n)`    
*Sao chép n ký tự trong chuỗi source vào chuỗi dest.*  
- **Hàm strcat:** `strcat(char ch1[], char ch2[])`  
*Nối chuỗi ch2 vào cuối chuỗi ch1. Sau lời gọi hàm này độ dài chuỗi ch1 bằng tổng độ dài của cả hai chuỗi ch1 và ch2 trước lời gọi hàm.*  - **Hàm strncat:** `strncat(char ch1[], char ch2[],int n)`  
*Nối n ký tự đầu tiên của ch2 vào ch1*  
- **Hàm strstr:** `char *strstr(char s1[], char s2[])`  
*Tìm kiếm chuỗi s2 trong chuỗi s1, Trả về địa chỉ của lần xuất hiện đầu tiên của s2 trong s1 hoặc NULL khi không tìm thấy.*  
- **Hàm strcmp:** `int strcmp(char ch1[], char ch2[])`  
*So sánh hai chuỗi ch1 và ch2. Nguyên tắc so sánh theo kiểu từ điển.*  
Giá trị trả về:  
  + = 0 nếu chuỗi ch1 bằng chuỗi ch2.  
  + > 0 nếu chuỗi ch1 lớn hơn chuỗi ch2.  
  + < 0 nếu chuỗi ch1 nhỏ hơn chuỗi ch2.  
- **Hàm stricmp:** *tương tự hàm strcmp nhưng không phân biệt chữ hoa và thường*  
- **Hàm strincpm:** *tương tự hàm strncpm nhưng không phân biệt hoa, thường*  

<a name Mảng_và_chuỗi_ký_tự><a\>  
###III.Mảng Và Chuỗi Ký Tự   
**1.Khái niệm**    
Một dạng sử dụng con trỏ đặc biệt là việc sử dụng một mảng các biến con trỏ.  
**2.Khai báo:**  
`type *pointer_array[size];`  
VD: char *p[100]; 






