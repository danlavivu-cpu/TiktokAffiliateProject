# WIN Scoring Framework — Chi tiết

## Bảng chấm điểm (Tổng 100)

### 1. Hoa hồng (30 điểm)

| Commission | Điểm |
|-----------|------|
| ≥ 30% | 30 |
| 20-29% | 25 |
| 15-19% | 15 |
| 10-14% | 10 |
| < 10% | 0 |

**Lý do trọng số cao nhất**: Revenue trực tiếp. Commission thấp = cần volume cực lớn để có lãi.

### 2. Đánh giá sản phẩm (20 điểm)

| Rating | Điểm |
|--------|------|
| ≥ 4.8 sao | 20 |
| 4.5-4.7 | 15 |
| 4.0-4.4 | 10 |
| < 4.0 | 0 |

**Kiểm tra thêm**: NRR (Negative Review Rate) = % đánh giá 1-2 sao trong 30 ngày. NRR > 2x trung bình danh mục → loại.

### 3. Giá bán (15 điểm)

| Giá | Điểm | Lý do |
|-----|------|-------|
| 150K-350K | 15 | Sweet spot: impulse buy + margin tốt |
| 100K-149K hoặc 351K-500K | 10 | Vẫn ổn nhưng không lý tưởng |
| 50K-99K | 5 | Margin thấp, phí platform ăn nhiều |
| > 500K hoặc < 50K | 0 | Quá đắt hoặc quá rẻ cho affiliate |

### 4. Bestseller rank (15 điểm)

| Rank | Điểm |
|------|------|
| Top 10 trong danh mục | 15 |
| Top 50 | 10 |
| Top 100 | 5 |
| Ngoài Top 100 hoặc N/A | 0 |

### 5. Free sample (10 điểm)

| Trạng thái | Điểm |
|-----------|------|
| Có free sample | 10 |
| Giá sample giảm | 5 |
| Không có | 0 |

### 6. Visual appeal (10 điểm)

| Mức độ | Điểm | Ví dụ |
|--------|------|-------|
| Rất visual | 10 | Before/after rõ, màu sắc đẹp, demo dễ |
| Trung bình | 5 | Cần effort để quay đẹp |
| Khó quay | 0 | Sản phẩm vô hình, khó demo |

## Quy trình chấm điểm

```
Bước 1: Thu thập 6 data points
Bước 2: Chấm từng tiêu chí theo bảng trên
Bước 3: Tính tổng
Bước 4: Check NRR, wow factor, niche fit
Bước 5: Quyết định
```

## Decision Matrix

| Tổng điểm | NRR OK? | Wow Factor? | Quyết định |
|-----------|---------|-------------|-----------|
| ≥ 70 | Yes | Yes | TEST NGAY — ưu tiên cao |
| ≥ 70 | Yes | No | TEST — nhưng cần angle content đặc biệt |
| ≥ 70 | No | — | SKIP — NRR cao = hoàn hàng nhiều |
| 50-69 | Yes | Yes | CÂN NHẮC — test nếu có angle tốt |
| 50-69 | Yes | No | CHỜ — tìm sản phẩm tốt hơn |
| < 50 | — | — | LOẠI — ghi vào da-loai.md |

## Ví dụ chấm điểm

### Sokfarm Mật Hoa Dừa
- Hoa hồng: Chưa rõ → 0 (cần update)
- Đánh giá: Chưa rõ → 0 (cần update)
- Giá 132K: 10 điểm
- Bestseller: Chưa rõ → 0
- Free sample: Chưa rõ → 0
- Visual appeal: Chai thủy tinh đẹp, mật vàng hổ phách → 10 điểm
- **Tạm tính: 20/100** → Cần update data để chấm chính xác

### Colgate Whitening
- Hoa hồng: Chưa rõ → 0
- Đánh giá: Chưa rõ → 0
- Giá ~60-70K: 5 điểm (dưới 100K)
- Bestseller: Brand lớn → ước 10 điểm
- Free sample: Không → 0
- Visual appeal: Before/after răng trắng rõ → 10 điểm
- **Tạm tính: 25/100** → Cần update data hoa hồng và đánh giá
