# 🇪🇬 Scroll for Arabic Version ⬇️

# 🧩 Customer Segmentation using K-Means

## 📘 Project Overview
This project applies **K-Means Clustering** to segment customers based on their **Annual Income (k$)** and **Spending Score (1–100)**.  
By identifying distinct groups, businesses can understand customer behavior, tailor marketing strategies, and improve targeting.

---

## ⚙️ Steps

### 1. Data Preprocessing
- Removed unnecessary columns such as *CustomerID* and *Name*.
- Encoded **Genre** to numerical values.
- Scaled numerical features using **StandardScaler** for better clustering performance.

### 2. Choosing Optimal K (Number of Clusters)
- Used the **Elbow Method** to determine the best number of clusters.
- The optimal value was **K = 5**, balancing compactness and separation.

### 3. Model Training
- Applied **KMeans(n_clusters=5, random_state=42)**.
- Achieved a **Silhouette Score = 0.59**, indicating **good separation** between clusters.

---

## 📊 Insights & Results

| Cluster | Characteristics | Interpretation |
|----------|-----------------|----------------|
| **Cluster 0** | Low income, low spending | Budget-conscious customers |
| **Cluster 1** | Medium income, high spending | Potential loyal customers |
| **Cluster 2** | High income, low spending | Untapped premium customers |
| **Cluster 3** | Medium income, medium spending | Average consumers |
| **Cluster 4** | High income, high spending | Ideal target group |

---

## 📈 Visualization
The scatter plot below shows customer clusters by income and spending behavior.  
Each color represents a distinct customer segment, and the **red circles** are the **cluster centers**.

---

## 🧠 Key Takeaways
- The **Silhouette Score (0.59)** indicates **strong cluster separation**.
- The model successfully identified **5 meaningful customer segments**.
- This segmentation can be used to **personalize marketing campaigns** and **allocate resources efficiently**.

---

## 🚀 Future Work
- Include more variables like **age, location, and purchase history**.
- Experiment with **hierarchical clustering** or **DBSCAN** for deeper analysis.
- Deploy the model as an **API** to predict new customer segments in real-time.

---
# 🧩 تقسيم العملاء باستخدام خوارزمية K-Means

## 📘 نظرة عامة
المشروع ده بيستخدم خوارزمية **K-Means Clustering** لتقسيم العملاء بناءً على **الدخل السنوي (بالألف دولار)** و**درجة الإنفاق (من 1 إلى 100)**.  
الهدف إننا نفهم سلوك العملاء ونحدد الفئات المختلفة عشان نحسّن التسويق والاستهداف.

---

## ⚙️ خطوات التنفيذ

### 1. معالجة البيانات
- حذفنا الأعمدة الغير ضرورية زي *CustomerID* و*Name*.
- حوّلنا **Genre** لأرقام (ذكور وإناث).
- استخدمنا **StandardScaler** لتوحيد القيم العددية وتحسين أداء التجميع.

### 2. اختيار عدد المجموعات الأنسب
- استخدمنا **طريقة Elbow** لتحديد أفضل عدد من الكلسترز.
- وطلع إن **K = 5** هو الأفضل بين التماسك والانفصال.

### 3. تدريب النموذج
- استخدمنا **KMeans(n_clusters=5, random_state=42)**.
- النتيجة كانت **Silhouette Score = 0.59**، وده معناه إن المجموعات مفصولة كويس عن بعضها.

---

## 📊 النتائج والتحليلات

| المجموعة | الخصائص | التفسير |
|-----------|----------|----------|
| **Cluster 0** | دخل منخفض، إنفاق منخفض | عملاء بميزانية محدودة |
| **Cluster 1** | دخل متوسط، إنفاق عالي | عملاء محتملين أو أوفياء |
| **Cluster 2** | دخل عالي، إنفاق منخفض | عملاء محتملين لم يُستهدفوا بعد |
| **Cluster 3** | دخل وإنفاق متوسط | مستهلكين عاديين |
| **Cluster 4** | دخل وإنفاق عالي | الفئة الذهبية أو العملاء المثاليين |

---

## 📈 التصور البياني
المخطط بيوضح توزيع العملاء حسب الدخل والإنفاق.  
كل لون بيمثل مجموعة مختلفة، والدواير الحمرا هي **مراكز المجموعات**.

---

## 🧠 الاستنتاجات
- **Silhouette Score (0.59)** معناها إن المجموعات واضحة ومفصولة كويس.
- النموذج نجح في تحديد **5 شرائح عملاء مميزة**.
- التقسيم ده يساعد الشركات في **تحسين استراتيجيات التسويق** و**زيادة ولاء العملاء**.

---

## 🚀 الخطوات القادمة
- إضافة بيانات أكتر زي **العمر والموقع وسجل الشراء**.
- تجربة خوارزميات تانية زي **Hierarchical Clustering** أو **DBSCAN**.
- نشر النموذج كـ **API** للتنبؤ بفئة العملاء الجدد بشكل مباشر.

