# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

---
## ⚠️ NGÔN NGỮ / LANGUAGE REQUIREMENT

**QUAN TRỌNG - IMPORTANT:**
- **Luôn trả lời bằng TIẾNG VIỆT trong mọi trường hợp**
- **Tất cả nội dung, báo cáo, kịch bản, kế hoạch phải viết bằng TIẾNG VIỆT**
- **Chỉ sử dụng tiếng Anh cho: tên biến, tên file, code, technical terms khi cần thiết**
- **Always respond in VIETNAMESE for all communications**
- **All content, reports, scripts, plans must be written in VIETNAMESE**
- **Use English only for: variable names, file names, code, technical terms when necessary**

---

## Project Overview

TikTok Shop affiliate marketing workspace — quản lý sản phẩm, kịch bản video, research, data và vận hành đội nhóm.

## Cấu trúc thư mục

```
TiktokAffiliateProject/
├── san-pham/                   # Mỗi sản phẩm có 1 folder riêng
│   └── _template/              # Template để copy khi thêm sản phẩm mới
│       ├── README.md           # Thông tin sản phẩm (hoa hồng, link, đánh giá...)
│       ├── research.md         # Phân tích đối thủ, pain point, hashtag
│       └── scripts/            # 5 kịch bản theo công thức HOOK→PROBLEM→SOLUTION→DEMO→CTA
│           ├── 01-unboxing.md
│           ├── 02-review.md
│           ├── 03-before-after.md
│           ├── 04-tutorial.md
│           └── 05-storyline.md
├── ideas/                      # Pool ý tưởng sản phẩm
│   ├── dang-xem-xet.md         # Chưa test, có khung chấm điểm WIN
│   └── da-loai.md              # Đã loại (để không test lại)
├── research/                   # Market intelligence
│   ├── competitor-spy.md       # Theo dõi affiliate đối thủ
│   ├── trending.md             # Cập nhật hàng tuần
│   └── seasonal-calendar.md    # Lịch thời vụ cả năm
├── data/                       # Tracking performance
│   ├── weekly-report.md        # Báo cáo tuần (template)
│   └── product-performance.csv # Raw data từng video
├── ads/campaigns/              # Quản lý quảng cáo
│   └── _template-campaign.md   # Template theo dõi Spark Ads / VSA
├── brand-relations/            # Quan hệ brand/shop
│   └── contacts.md             # Danh sách + template đề xuất Target Collaboration
└── sop/                        # Quy trình vận hành
    ├── quy-trinh-hang-tuan.md  # Checklist theo ngày trong tuần
    └── checklist-video.md      # Checklist trước/sau đăng video
```

## Workflow thêm sản phẩm mới

1. Copy `san-pham/_template/` → `san-pham/[ten-san-pham]/`
2. Điền thông tin vào `README.md` (hoa hồng, link, đánh giá, target audience)
3. Hoàn thiện `research.md` (spy đối thủ, pain points, hashtag)
4. Viết 5 kịch bản trong `scripts/` theo công thức HOOK→PROBLEM→SOLUTION→DEMO→CTA
5. Ghi vào `data/product-performance.csv` sau mỗi video đăng

## Quy tắc quan trọng

- **Sản phẩm WIN**: Hoa hồng ≥ 20%, đánh giá ≥ 4.5 sao, giá 100K-500K VND
- **Quy tắc 80/20**: 80% thời gian quay sản phẩm đã chứng minh bán được, 20% test mới
- **Dừng sản phẩm** khi: 3 video liên tiếp < 500 views hoặc conversion giảm > 50%
- **Chạy Spark Ads** chỉ sau khi có video organic > 10,000 views và xác nhận có đơn

## Cấu trúc video chuẩn

Mọi kịch bản trong `scripts/` theo cấu trúc: **HOOK (0-3s) → PROBLEM (3-8s) → SOLUTION (8-15s) → DEMO (15-40s) → CTA (40-60s)**

5 format kịch bản: (1) Unboxing + First Impression (2) Honest Review sau dùng (3) Before/After hoặc So sánh (4) Tutorial/Hướng dẫn (5) Storyline/Đời thường

## Khung chấm điểm WIN (tổng 100 điểm)

| Tiêu chí | Điểm |
|----------|------|
| Hoa hồng ≥ 20% | 30 |
| Đánh giá ≥ 4.5 sao | 20 |
| Giá 100K-500K VND | 15 |
| Bestseller rank cao | 15 |
| Free sample available | 10 |
| Visual appeal (dễ quay video) | 10 |

- ≥ 70 điểm → Ưu tiên test
- < 50 điểm → Loại hoặc chờ
- Kiểm tra thêm: NRR (< 2x trung bình danh mục), wow factor, niche fit với kênh

## Thuật toán TikTok 2026

Tín hiệu xếp hạng (theo thứ tự ưu tiên):
1. **Shares** — mạnh nhất 2026
2. **Saves** — giữ video trên FYP nhiều ngày
3. **Completion Rate & Watch Time**
4. **Comments & Likes**
5. **Video Information** (captions, sounds, hashtags)

Content mix tối ưu: 70% giá trị/giải trí, 20% tương tác cộng đồng (Duets/Stitches), 10% quảng bá trực tiếp

Creator Health Rating (CHR): Từ 01/2026, mỗi creator bắt đầu 200 điểm. Post 5+ video non-interactive/7 ngày → bị giới hạn posting.

## Spark Ads & VSA

- Chỉ boost video organic > 10,000 views VÀ đã có đơn
- Video raw/authentic convert tốt hơn video chuyên nghiệp
- ROAS > 2x → tăng budget | 1-2x → giữ, tối ưu | < 1x sau 3 ngày → dừng
- VSA conversion rate: 10%+ (standard ads chỉ 0.46-2.4%)

## Livestream selling

- Chuẩn bị 3 tầng sản phẩm: Loss-leader (giá rẻ), Mid-range (lợi nhuận), Premium (high-margin)
- Dành 5-10 phút/sản phẩm, trả lời comment real-time, dùng countdown timer
- Conversion LIVE: 3-5x video thường, sales lift 200-300% trong 24h sau

## KPIs theo dõi

- **Hàng ngày**: GMV, Revenue, Order volume, AOV
- **Hàng tuần**: CAC, CTR (target 5-8%), Video views, Retention graphs
- **Hàng tháng**: Top-performing posts, Audience patterns, Efficiency metrics
- **Báo cáo tuần**: Tổng views/đơn/GMV, Top 3 video, Sản phẩm cần dừng, Quyết định tuần tới

## Lịch thời vụ Việt Nam

- **Q1**: Tết Nguyên Đán (chuẩn bị từ T12), Valentine 14/2, 8/3
- **Q2**: 30/4-1/5, Ngày của Mẹ, Hè (chống nắng, du lịch, giải nhiệt)
- **Q3**: Back to School (T8-9), Trung Thu
- **Q4**: 20/10, 11.11, 12.12, Giáng Sinh — MÙA VÀNG

Chuẩn bị content trước mỗi dịp ít nhất 2-3 tuần.

## Chính sách TikTok Shop VN 2026

- Platform commission: 3-4% (standard), 5.78-7.7% (Shop Mall)
- Order Processing Fee: 3,000 VND/đơn
- Sản phẩm < 100K VND chịu thêm ~3%
- Tuân thủ: Không bán sản phẩm cấm, claim phải đúng sự thật
