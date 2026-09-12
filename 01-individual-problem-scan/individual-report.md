# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Ngô Đức Chung
- Mã học viên: 2A202602985
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên mới tốt nghiệp đang tìm kiếm việc làm.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
Đi học, code, học tiếng Anh, tập thể dục.
---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |AI có thể tốt hơn |Kiểm tra lỗi code(Ví dụ: lỗi import, lỗi syntax) mỗi lần luyện leetcode |Tôi |30 phút/ lần, 3 lần/ tuần, bấm giờ để xem(quá 30 phút không sửa được thì xem giải hoặc nhờ AI sửa) |
| 2 |Tốn thời gian|Đọc và tổng hợp lại các kiến thức cần thiết từ bảng giảng trên lớp để ôn lại bài |Tôi |1,5 tiếng mỗi buổi tối, 6 ngày/tuần, tự bấm giờ để theo dõi |
| 3 |AI có thể tốt hơn |Không nhớ nghĩa, cụm từ Tiếng Anh đã học nên phải luyện lại | Tôi|Quên khoảng 30% từ và cụm từ đã học, bằng chứng là tự luyện bằng flash card và tự viết ra giấy|
| 4 |Lặp lại |Quên lịch tập gym phải note lại mỗi tuần |Tôi |Bỏ 3/5 buổi đã note lại trong 2 tuần gần đây |
| 5 |Pain từ người khác |Bạn làm cùng project hỏi lại cách chạy code, setup môi trường dù đã chỉ nhiều lần trước đó |Tôi và bạn cùng làm project |Hỏi lại 2 lần trong 1 tuần, có tin nhắn Messenger làm bằng chứng |
| 6 |AI có thể làm tốt hơn |Debug code dự án, không biết lỗi bắt nguồn từ đâu khi không hiểu lỗi từ terminal |Tôi |Mất khoảng 30 phút/ lỗi, gặp mỗi ngày|
| 7 |Tốn thời gian |Luyện nói một mình và không có ai sửa lỗi phát âm/ ngữ pháp |Tôi |Tự luyện tập khoảng 15 phút/ ngày, 3 ngày/ tuần |
| 8 |Pain từ người khác |Giáo viên nhắc làm bài tiếng Anh vì quên |Tôi |Bị nhắc 2 lần trong 3 tuần gần nhất, có bằng chứng là tin nhắn từ Zalo |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Debug code dự án, không biết lỗi bắt nguồn từ đâu khi không hiểu lỗi từ terminal|Xảy ra hằng ngày, bottleneck ở bước hiểu lỗi, actor là tôi |Chưa rõ liệu dùng AI sẽ sửa được lỗi này nhưng mà sinh ra lỗi ở chỗ khác hay không. |
| 2 |Đọc và tổng hợp lại các kiến thức cần thiết từ bảng giảng trên lớp để ôn lại bài|Tốn thời gian nhất trong tuần, bottleneck ở bước tổng hợp lại bài học |Chưa chắc chắn được rằng liệu dùng AI có tổng hợp thiếu hoặc thừa thông tin(thông tin sai) hay không.|
| 3 |Bạn làm cùng project hỏi lại cách chạy code, setup môi trường dù đã chỉ nhiều lần trước đó |Ảnh hưởng cả người khác, có bằng chứng tin nhắn |Chưa rõ vấn đề là do tài liệu gửi thiếu hay do bạn chưa đọc kỹ |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Debug lỗi terminal khi code dự án]

```text
Problem 1 câu: Debug lỗi terminal khi code dự án

Actor: Tôi

Thời điểm / bối cảnh: Khi code dự án, gặp lỗi runtime không rõ nguyên nhân

Current workflow 3-7 bước:
1. Chạy code, terminal bão lỗi (1')
2. Đọc thông báo lỗi, không hiểu lỗi gì (5')
3. Hỏi ChatGPT để xem lỗi (15')
4. Thử sửa theo gợi ý tìm được và chạy lại (5')
5. Nếu chưa đúng, quay lại bước 3 (4')

Bottleneck: Hỏi ChatGPT mất 15 phút vì không mô tả đúng lỗi ngay từ đầu.

Impact: Khoảng 30 phút/lỗi (bước 3+4+5 lặp lại), gặp gần như mỗi ngày khi code dự án, làm chậm tiến độ, đôi khi bỏ dở vì mất kiên nhẫn.

Success metric: Hiện tại mất 30 phút/ lỗi. Mục tiêu sẽ dưới 10 phút/ lỗi và sẽ tự đo bằng cách bấm giờ trong 1 tuần code dự án

Non-AI alternative: Note lại các lỗi đã gặp + cách sửa vào file riêng rồi sẽ tra lại khi gặp lỗi tương tự

AI hypothesis: Copy nguyên thông báo lỗi cũng như đoạn code liên quan cho AI ngay từ đầu. AI chỉ ra nguyên nhân lỗi và hướng dẫn sửa trong 1 lượt hỏi.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ...: __'] → [4 ...: __']  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ... review: __']  <-- human boundary

Fallback: nếu AI sai thì ...
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tổng hợp bài giảng để ôn bài]

```text
Problem 1 câu: Đọc và tổng hợp lại kiến thức từ bài giảng trên lớp để ôn bài.

Actor: Tôi

Thời điểm / bối cảnh: Sau giờ học, ôn lại bài ở nhà để chuẩn bị cho kỳ thi hoặc deadline bài tập.

Current workflow 3-7 bước:
1. Mở lại ghi chú + slide bài giảng (5')
2. Đọc lại từng phần để nhớ nội dung (30')
3. Gạch ý chính, viết tóm tắt riêng (40') 
4. Đối chiếu tóm tắt với slide xem thiếu ý không (10')

Bottleneck:Ở bước 3 -tự tóm tắt mất nhiều thời gian vì phải đọc đi đọc lại để chọn ý chính, không có cấu trúc sẵn.

Impact:  mất khoảng 1.5 tiếng/buổi, 6 ngày/tuần, chiếm nhiều thời gian rảnh, đôi khi phải cắt giờ ngủ.


Success metric: Hiện tại mất 1.5 tiếng/ buổi. Mục tiêu sau đó sẽ dưới 45 phút/ buổi, sẽ tự đo bằng đổng hồ trong 1 tuần.

Non-AI alternative: Dùng template tóm tắt cố định (mục tiêu bài - ý chính - ví dụ) để đỡ mất thời gian nghĩ cấu trúc.

AI hypothesis: Đưa slide/ghi chú cho AI, AI tóm tắt ý chính theo cấu trúc, tôi chỉ đọc lại và chỉnh sửa.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Bạn cùng project hỏi lại cách setup môi trường/chạy code]

```text
Problem 1 câu: Bạn cùng project hỏi lại cách chạy code, setup môi trường dù đã chỉ nhiều lần trước đó.

Actor: Tôi và bạn cùng làm project

Thời điểm / bối cảnh: Khi bắt đầu làm việc chung trên project, hoặc sau khi có thay đổi môi trường.

Current workflow 3-7 bước:
1. Bạn nhắn hỏi cách setup/chạy code (1')
2. Tôi nhớ lại các bước đã từng chỉ (3')
3. Tôi gõ lại hướng dẫn từng bước qua chat (10')
4. Bạn làm theo, có chỗ chưa rõ, hỏi lại thêm (5')
5. Bạn chạy được, xác nhận xong (1')

Bottleneck: Ở bước 3 - mỗi lần đều phải gõ lại hướng dẫn từ đầu vì không có tài liệu lưu sẵn.

Impact: Mỗi lần khoảng 20 phút/lần, 2 lần/tuần, mất thời gian của cả hai, đôi khi làm chậm tiến độ project vì bạn chờ hướng dẫn.

Success metric: Hiện tại khoảng 20 phút/lần trả lời. Mục tiêu dưới 5 phút/lần (chỉ gửi link tài liệu), đo bằng đếm số phút trả lời trong 2 tuần.

Non-AI alternative: Viết 1 file README setup hướng dẫn từng bước, gửi link mỗi lần được hỏi.

AI hypothesis: Dùng AI soạn README từ các đoạn hướng dẫn đã từng nhắn qua chat, tôi chỉ review lại cho đúng.

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #2 — Tổng hợp bài giảng để ôn bài

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow hiện tại 5 bước, bottleneck ở bước tự tóm tắt (40 phút) vì phải đọc đi đọc lại để chọn ý chính, không có cấu trúc sẵn. Mất khoảng 1.5 tiếng/buổi, 6 ngày/tuần, chiếm phần lớn thời gian rảnh, đôi khi phải cắt giờ ngủ. Impact lớn vì lặp lại hằng ngày, không chỉ 1 lần.

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. AI tóm tắt có đảm bảo đủ ý quan trọng cho bài thi không, hay bỏ sót chi tiết cần nhớ?
2. Nếu môn học nặng công thức, AI tóm tắt sai thì hậu quả thế nào so với môn lý thuyết?

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
