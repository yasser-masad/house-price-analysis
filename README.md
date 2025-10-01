🏠 مشروع تحليل وتنبؤ بأسعار المنازل (House Price Analysis & Prediction)
🌟 نظرة عامة على المشروع (Project Overview)

هذا المشروع عبارة عن تحليل معمق للبيانات العقارية، يهدف إلى تأسيس بيانات نظيفة وموثوقة كقاعدة لبناء نماذج التنبؤ بأسعار المنازل. يغطي المشروع المراحل الأساسية للتحليل الاستكشافي للبيانات (EDA)، بما في ذلك التحقق من القيم المفقودة، اكتشاف العلاقات بين المتغيرات، و تنظيف البيانات من القيم الشاذة، قبل الانتقال إلى بناء نماذج التعلم الآلي المتقدمة.


This project is an in-depth analysis of real estate data, focused on establishing a clean and reliable dataset as the foundation for house price prediction models. The work covers the essential stages of Exploratory Data Analysis (EDA), including missing value verification, discovering relationships between variables, and data cleansing from outliers, before moving to build advanced Machine Learning models.

🛠️ أبرز الإنجازات في معالجة البيانات (Key Data Processing Achievements)


فحص الجودة والامتلاء: تم إجراء تحقق شامل من البيانات للتأكد من عدم وجود قيم مفقودة (Missing Values)، مما يضمن جاهزية مجموعة البيانات للاستخدام مباشرة دون الحاجة لمعالجات الإكمال.

اكتشاف العلاقات: تم تحليل العلاقات الارتباطية (Correlations) بين الميزات والمتغير التابع (price) لاكتشاف أي تبعيات قوية، مما ساعد في اختيار أفضل الميزات للنموذج.

تنقية البيانات: تم تنفيذ عملية شاملة لإزالة القيم الشاذة (Outliers) من المتغيرات الرئيسية (price, area) لضمان أن النماذج تعكس الأنماط العامة للسوق بدقة.

جاهزية النموذج: تم استخدام البيانات النظيفة والمُنقّاة مباشرة لبناء وتقييم نماذج الانحدار الخطي وتصنيف شجرة القرار.


Quality and Completeness Check: A thorough verification was conducted to confirm the absence of missing values, ensuring the dataset was ready for direct use without the need for imputation or complex handling.

Relationship Discovery: Correlations between features and the target variable (price) were analyzed to identify strong dependencies, which aided in selecting the optimal features for the model.

Data Refinement: A comprehensive process was implemented to remove Outliers from key variables (price, area), ensuring that subsequent models accurately reflect general market trends.

Model Readiness: The clean, refined data was used directly to build and evaluate Linear Regression and Decision Tree Classification models.


📂 محتويات المستودع (Repository Contents)

data_cleaning_and_eda.ipynb: ملف مراحل تنظيف البيانات ومعالجة القيم الشاذة.

modeling_and_prediction.ipynb: ملف مراحل النمذجة والتدريب والتقييم النهائي.

housing_data_cleaned.csv: البيانات النظيفة والنهائية للمشروع. هذه النسخة هي المدخل المباشر لخطوة النمذجة.


🚀 كيفية تشغيل المشروع (How to Run the Project)

لإعادة إنتاج النتائج، اتبع الخطوات التالية:

المتطلبات (Requirements): تأكد من تثبيت مكتبات pandas, numpy, و scikit-learn (يمكن تثبيتها عبر pip install -r requirements.txt إذا كان لديك هذا الملف).

الاستنساخ (Clone): استنسخ المستودع: git clone https://github.com/yasser-masad/house-price-analysis.git

التنفيذ (Execution): افتح ملف 02_modeling_and_prediction.ipynb في بيئة Jupyter أو Colab، وقم بتشغيل الخلايا بالتسلسل.


To reproduce the results, follow these steps:

Requirements: Ensure required libraries like pandas, numpy, and scikit-learn are installed.

Clone: Clone the repository: git clone https://github.com/yasser-masad/house-price-analysis.git

Execution: Open the 02_modeling_and_prediction.ipynb file in a Jupyter or Colab environment and run the cells sequentially.


🎯 ملخص النتائج الرئيسية (Key Results Summary)

حقق المشروع أداءً جيدا وموثوقًا عبر مقاييس الانحدار والتصنيف، حيث تم الوصول إلى افضل أداء بفضل تغيير وتعديل بعض معاملات ودوال شجرة القرار لتحقيق الكفاءة القصوى.

في الانحدار (توقع السعر): تم تحقيق معامل تحديد (R2) يصل الى [0.62] مما يمثل جودة التنبؤ بالقيمة الفعلية للمنزل 

في تصنيف سعر المنزل (غالي/رخيص): كان الأداء قويًا بشكل خاص في اكتشاف المنازل الغالية، حيث وصلت الدقة (Accuracy) إلى [80%]، ووصل الـ Recall إلى [81%].


The project achieved strong and reliable performance across both regression and classification metrics. The best performance was reached by modifying and tuning specific parameters and functions within the Decision Tree model to achieve maximum efficiency.

In Regression (Price Prediction): We achieved an R2 (Coefficient of Determination) of up to 0.62, which represents the quality of the prediction for the home's actual value.

In Home Price Classification (Expensive/Cheap): Performance was particularly robust in detecting expensive homes. Accuracy reached 80%, and Recall reached 81%



👤  (Author)

 (Name): [ياسر مسعد المطرفي]
 
 GitHub: [@yasser-masad]
 
LinkedIn: [https://bit.ly/42j8wQG]
