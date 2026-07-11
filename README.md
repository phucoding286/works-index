## 📄 CHÀO MỪNG TỚI REPO QUẢN LÝ CÁC DỰ ÁN, HOẶC NHỮNG ĐIỀU QUAN TRỌNG CỦA TÔI.

### **Lưu ý**
- Đây chỉ là một kho lưu trữ chứa các link điều hướng và nhóm các dự án quan trọng của tôi.
- Nó không có mục đích công khai hay khoe thành tích hoặc dùng để làm profile xin việc, mục đích chủ yếu là để quản lý và kiểm soát tiến độ và dự án.
- Phần lớn có thể ở trạng thái `private (Truy cập sẽ gây lỗi 404)` hoặc một số sẽ `public (Có thể truy cập)`.
- Các index được sắp xếp theo đường dẫn phân tầng, khi truy cập vào mỗi index sẽ có các đường dẫn khác bên trong, điều này giúp tối ưu quản lý.
- Nếu bạn là **người truy cập bên ngoài**, vui lòng bỏ qua hoặc liên hệ với tôi qua các nền tảng sau nếu thắc mắc về bất kỳ modules/tools/repo nào.
- Facebook: https://www.facebook.com/hoangphu020

---

## 🧾 Các mục bên dưới

---

### 1. Các dự án về trí tuệ nhân tạo 💻📊

- **NLP (Deep Learning)**
  - [Full thuật toán Tokenizer BPE được viết từ đầu bằng Python.](https://github.com/phucoding286/causal-language-model/tree/main/tokenizer) (Tự triển khai) (Bản cũ) (Có một số lỗi)
  - [Thuật toán BPE (Fix postspace to prespace).](https://github.com/phucoding286/causal-language-model/tree/main/tokenizer_fixbug_version) (Bản Fix bug) (Khuyên dùng nhất) (Tự triển khai)
  - [Full mô hình Language Model bản chuẩn hiện đại.](https://github.com/phucoding286/causal-language-model/tree/main/language_model) (Tự triển khai) (Production)
  - [Biến thể kiến trúc Self-Attention do tôi thiết kế ⚡](https://github.com/phucoding286/causal-language-model/tree/main/variants) (! Thử nghiệm)

- **Computer Vision (Deep Learning)**
  - [Mô hình U-Net gốc (2015)](https://github.com/phucoding286/u-net-2015-test-code) (Code thử nghiệm)
  - [Mô hình Vision Transformer (ViT)](https://github.com/phucoding286/vision-transformer-testcode) (Code thử nghiệm)
  - [Khối ResNet.](https://github.com/phucoding286/resnet-by-phu) (Tự triển khai)
  - [Mô hình DDPM.](https://github.com/phucoding286/denoise_diffusion_probability_model_ddpm_Project) (Tự triển khai)
  - [Mô hình VAE.](https://github.com/phucoding286/variantional_autoencoders_VAE_Project) (Tự triển khai)
  - [Notebook triển khai và huấn luyện Latent Diffusion Model (LDM)](https://colab.research.google.com/drive/1ZaDwqgKsOHqzWp1loHkIIAuuolVGSOoY?authuser=1#scrollTo=n3xpmDX898yV) (Tự triển khai)
 
- **NLP Datasets**
  - Các module xử lý dữ liệu văn bản hoặc crawl.
    - [Module đọc/ghi dữ liệu văn bản vào file json, tối ưu.](https://github.com/phucoding286/text-json-writer-for-big-dataset) (Created by Phu)
    - [Module lọc trùng lặp urls, tối ưu hóa, hổ trợ cho việc crawling.](https://github.com/phucoding286/duplicate-filter) (Created by Phu)
    - [Module data buffer, lưu dữ liệu trên ram trước khi ghi, bảo vệ disk và data.](https://github.com/phucoding286/data-buffer) (Created by Phu)
    - [Module crawl webtext content, tự trịch xuất urls, hổ trợ việc crawl webtext data.](https://github.com/phucoding286/url-extract-crawler) (Created by Phu)
    - [Công cụ giúp combine bigdata và chia ra thành từng file con, phục vụ xử lý data khủng.](https://github.com/phucoding286/patch-combiner-datasets) (Created by Phu)

  - Bộ datasets NLP dành cho việc train Language Model.
    - [Các bộ dữ liệu NLP nhỏ demo pretraining cho Langugae Model.](https://github.com/phucoding286/text-datasets-demo-for-training-language-model) (Tự crawl)
    - [Các bộ dữ liệu lớn dành cho việc pretraining Language Model nghiêm túc, kèm chương trình crawl.](https://github.com/phucoding286/datasets-for-train-language-model) (Tự crawl)


---

### 2. Các dự án về tài chính, kiếm tiền online 📈📉

- **Tool kiếm tiền**
  - [Công cụ TDS/Golike Facebook](https://github.com/phucoding286/golike-facebook-tool) (`NetCode: MEMUNET`) (Created by Phu)
  - [Công cụ Golike Tiktok MEMUNET version](https://github.com/phucoding286/golike-tiktok-memunet) (`NetCode: MEMUNET`) (Created by Phu) (Không dùng được nữa)
  - [Công cụ Golike Tiktok](https://github.com/phucoding286/golike-tiktok-tool) (Created by Phu) (Không dùng được nữa)
  - [Giải thích về mã Memunet](https://github.com/phucoding286/memunet)
    - Mô tả ngắn: Mã MEMUNET dùng để định danh các tools dùng chung tài nguyên máy ảo MEMU.
  - [Bộ công cụ tài chính, tín hiệu giao dịch.](https://github.com/phucoding286/finance-algo)

- **Tư duy & Chiến lược Giao dịch 💰**
  - [Các mô hình prices action cơ bản và cách trade cơ bản.](https://github.com/phucoding286/basic-pricesaction-models) (Tổng hợp từ nhiều nguồn)
  - [Các khóa học prices action nâng cao và tài nguyên dành cho newbie trở thành pro trader.](https://github.com/phucoding286/advanced-priceactions-models-and-resoures) (Tổng hợp)

---

### 3. Dự án web, micro tools, tiện ích.
- [Dự án (phát triển theo thời gian)](https://github.com/phucoding286/my-web-project)
