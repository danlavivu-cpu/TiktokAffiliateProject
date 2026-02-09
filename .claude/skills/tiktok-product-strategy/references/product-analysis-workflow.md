# Product Analysis Workflow — Quy trình phân tích sản phẩm A-Z

## Phase 1: Thu thập thông tin cơ bản

### Checklist data cần có
- [ ] Tên sản phẩm + ngành hàng
- [ ] Giá bán (VND)
- [ ] % Hoa hồng affiliate
- [ ] Link TikTok Shop
- [ ] Đánh giá sao + số lượng đánh giá
- [ ] Bestseller rank trong danh mục
- [ ] Free sample có/không
- [ ] Điểm mạnh sản phẩm (3-5 điểm)
- [ ] Vấn đề sản phẩm giải quyết
- [ ] Đối tượng mục tiêu

### Nguồn data
- TikTok Shop: Giá, đánh giá, rank, hoa hồng
- Kalodata/Metric: Volume bán, trend
- Comment đối thủ: Pain points thật
- Google Trends: Nhu cầu tìm kiếm

## Phase 2: Chấm điểm WIN

Áp dụng khung 100 điểm (xem `win-scoring-framework.md`).

Output: Bảng điểm + kết luận (Test / Skip / Cần data).

## Phase 3: Phân tích đối thủ

### Template bảng phân tích

| Creator | Video | Views | Góc tiếp cận | Điểm học được |
|---------|-------|-------|--------------|---------------|
| @ | Link | K | Unboxing/Review/... | Hook gì, CTA gì |

### Câu hỏi cần trả lời
- Có bao nhiêu creator đang bán sản phẩm này?
- Video top views dùng hook gì?
- CTA nào convert tốt?
- Có angle nào chưa ai làm?

## Phase 4: Research pain points

### Nguồn pain points
1. **Comments video đối thủ**: Câu hỏi, complaints, wishes
2. **Reviews sản phẩm**: Đánh giá 1-3 sao = pain points rõ nhất
3. **Forums/Groups**: Facebook groups, Reddit threads
4. **Google "sản phẩm + review"**: Blog reviews

### Phân loại pain points

| Pain point | Mức độ | Content angle |
|-----------|--------|---------------|
| Functional | Cao | Tutorial, Before/After |
| Emotional | Cao | Storyline, Review |
| Price | Trung bình | So sánh giá trị |
| Convenience | Thấp | Unboxing |

## Phase 5: Hashtag & trending angles

### Hashtag strategy (5-10 tags/video)
- 2-3 hashtags sản phẩm/brand
- 2-3 hashtags niche/audience
- 2-3 hashtags trending (#fyp #tiktokvietnam)
- 1-2 hashtags CTA (#savelai #linktronggio)

### Trending angles
Xác định 3-5 góc content dựa trên:
- Pain points mạnh nhất
- Angle đối thủ chưa làm
- Seasonal relevance
- Target audience segment

## Phase 6: Quyết định & Action

### Test → Setup folder sản phẩm
```
1. Copy san-pham/_template/ → san-pham/[ten-san-pham]/
2. Điền README.md
3. Hoàn thiện research.md
4. Viết 5 kịch bản scripts/
5. Lên lịch quay + đăng
```

### Skip → Ghi lại
```
1. Ghi vào ideas/da-loai.md: Tên, Lý do, Ngày, Ghi chú
2. Không test lại trừ khi có thay đổi lớn
```

### Cần data → Action items
```
1. Liệt kê data còn thiếu
2. Gán deadline thu thập
3. Quay lại chấm điểm sau khi có đủ
```

## Phase 7: Theo dõi sau test

### Tuần 1-2 (Test phase)
- Đăng 5-10 video (5 format khác nhau)
- Theo dõi: Views, CTR, Orders mỗi video
- Không chạy ads

### Tuần 3+ (Evaluate)
- 3 video liên tiếp < 500 views → DỪNG
- Conversion giảm > 50% → ĐỔI ANGLE hoặc DỪNG
- Có video > 10K views + đơn → SCALE (Spark Ads)
- Winning ổn định → 80% effort vào đây

### Data tracking
Ghi vào `data/product-performance.csv`:
```
Ngay,San pham,Video type,Views,Likes,Comments,Shares,CTR,Don hang,GMV,Hoa hong,Ghi chu
```
