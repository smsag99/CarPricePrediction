# Final Project of the Introductory School of Data Science and Artificial Intelligence

## Project Goal
To develop a machine learning model that estimates the price of vehicles based on their various features.

---

## Dataset Description
- **Training Dataset (Train):** Contains the features of vehicles along with the announced price.
- **Test Dataset (Test):** Contains the features of vehicles without price information.

---

## Data Features
- **title:** Brand and model of the car
- **year:** Year of manufacture
- **mileage:** Mileage (kilometers driven)
- **transmission:** Type of gearbox
- **fuel:** Fuel consumption
- **body_color:** Body color
- **inside_color:** Interior color
- **body_status:** Body condition
- **description:** Ad description text
- **body_type:** Body type
- **volume:** Engine volume
- **engine:** Engine specifications
- **acceleration:** Acceleration (0 to 100 km/h)
- **price:** Announced price (available only in training data)

---

## Key Points for Solving the Problem
1. **Data Processing (EDA):** Analyze and process the training dataset to remove noise and invalid entries.
2. **Utilizing Text Features:** Effectively analyze and use the ad description text to improve predictions.
3. **Feature Engineering:** Create and extract new features from the data.
4. **Model Evaluation:** Predict vehicle prices in the test dataset and evaluate model accuracy.

---

## Evaluation Metrics
1. **Median Absolute Percentage Error (MAPE):**
   \[
   MAPE = Median \left( \frac{|y_{true} - y_{pred}|}{y_{true}} \right) \times 100
   \]

2. **R² (Coefficient of Determination):**
   A statistical measure representing the model’s accuracy in predicting the actual outcomes.

---

## Final Score
The weighted average of the two mentioned metrics is calculated as follows:
\[
Final Score = \frac{(1 - MAPE) + R²}{2} \times 100
\]

---

## How to Submit the Solution
1. Train your model using the training dataset.
2. Predict the prices of the vehicles in the test dataset.
3. Prepare your results as a `csv` file, preserving the record order.
4. Upload the prepared file to the platform and view your score.

---

# پروژه پایانی مدرسه مقدماتی علم داده و هوش مصنوعی

## هدف پروژه
ساخت یک مدل یادگیری ماشین که با دریافت ویژگی‌های مختلف خودروها، یک تخمین قابل قبول برای قیمت آن‌ها محاسبه کند.

---

## توضیحات داده‌ها
- **مجموعه داده آموزشی (Train):** شامل ویژگی‌های خودروها به همراه قیمت اعلام شده.
- **مجموعه داده تست (Test):** شامل ویژگی‌های خودروها بدون اطلاعات قیمت.

---

## ویژگی‌های داده
- **title:** برند و مدل ماشین
- **year:** سال ساخت
- **mileage:** کیلومتر کارکرد
- **transmission:** نوع گیربکس
- **fuel:** میزان مصرف سوخت
- **body_color:** رنگ بدنه
- **inside_color:** رنگ داخلی
- **body_status:** وضعیت بدنه
- **description:** متن توضیحات آگهی
- **body_type:** نوع بدنه
- **volume:** حجم موتور
- **engine:** مشخصات موتور
- **acceleration:** زمان صفر تا صد
- **price:** قیمت اعلام شده (فقط در داده آموزشی)

---

## نکات مهم برای حل مسئله
1. **پردازش داده‌ها (EDA):** بررسی و تحلیل داده‌های آموزشی برای حذف نویزها و مقادیر نامعتبر.
2. **استفاده از ویژگی‌های متنی:** تحلیل و استفاده بهینه از متن توضیحات برای بهبود پیش‌بینی.
3. **مهندسی ویژگی‌ها (Feature Engineering):** ایجاد و استخراج ویژگی‌های جدید.
4. **ارزیابی مدل‌ها:** پیش‌بینی قیمت خودروهای مجموعه تست و محاسبه دقت مدل.

---

## متریک‌های ارزیابی
1. **میانه درصد خطا (Median Absolute Percentage Error - MAPE):**
   \[
   MAPE = Median \left( \frac{|y_{true} - y_{pred}|}{y_{true}} \right) \times 100
   \]

2. **R² (Coefficient of Determination):**
   مقدار آماری که نشان‌دهنده تطابق پیش‌بینی‌های مدل با واقعیت است.

---

## امتیاز نهایی
میانگین وزنی دو متریک ذکر شده به صورت زیر محاسبه می‌شود:
\[
Final Score = \frac{(1 - MAPE) + R²}{2} \times 100
\]

---

## نحوه ارسال پاسخ
1. مدل خود را بر روی داده‌های آموزشی آموزش دهید.
2. پیش‌بینی قیمت خودروهای مجموعه تست را انجام دهید.
3. پاسخ خود را در قالب فایل `csv`، با حفظ ترتیب رکوردها، آماده کنید.
4. فایل آماده‌شده را در پلتفرم بارگذاری کرده و امتیاز خود را مشاهده کنید.
