# loan_default_Prediction
#ENGLISH BELOW
Xây dựng mô hình Machine Learning dự đoán khả năng khách hàng sẽ rơi vào nhóm nợ xấu (default) dựa trên dữ liệu tài chính và lịch sử tín dụng.
Lợi ích:
- Giảm thiểu rủi ro tín dụng.
- Nâng cao hiệu quả xét duyệt khoản vay.
- Phát hiện sớm khách hàng có nguy cơ cao để đưa ra biện pháp xử lý.

Tổng Quan Dữ Liệu (Loan_default.csv):
Số lượng bản ghi: 255,347
Số cột: 18
Cột mục tiêu: Default (0: Không nợ xấu, 1: Nợ xấu)
Dữ liệu không có giá trị null (thiếu)

Các Cột Dữ Liệu Chính:
•	LoanID: ID khoản vay.
•	Age: Tuổi khách hàng.
•	Income: Thu nhập hàng năm (VNĐ).
•	LoanAmount: Số tiền vay.
•	CreditScore: Điểm tín dụng (thang điểm).
•	MonthsEmployed: Số tháng làm việc.
•	NumCreditLines: Số lượng khoản tín dụng hiện tại.
•	InterestRate: Lãi suất khoản vay (%).
•	LoanTerm: Thời hạn khoản vay (tháng).
•	DTIRatio: Tỷ lệ nợ trên thu nhập (Debt-to-Income Ratio).
•	Education: Trình độ học vấn.
•	EmploymentType: Tình trạng việc làm.
•	MaritalStatus: Tình trạng hôn nhân.
•	HasMortgage: Có thế chấp không (Yes/No).
•	HasDependents: Có người phụ thuộc không (Yes/No).
•	LoanPurpose: Mục đích vay (Auto, Business, Other...).
•	HasCoSigner: Có người đồng ký vay không.
•	Default: Nhãn mục tiêu (0 hoặc 1).

Kế Hoạch Xây Dựng Dự Án Dự Đoán Nợ Xấu:
1.	Làm sạch và chuẩn hóa dữ liệu.
2.	Phân tích dữ liệu (EDA) để khám phá mối quan hệ giữa các biến và nợ xấu.
3.	Xây dựng mô hình Machine Learning (Logistic Regression, Random Forest, XGBoost).
4.	Đánh giá hiệu suất mô hình.

5. Kết Quả Kỳ Vọng
•	Accuracy: > 85%.
•	Recall: > 80% (Phát hiện đúng khách hàng nợ xấu)

-----------------------------------------------------
# loan_default_Prediction
#ENGLISH BELOW
Build a Machine Learning model to predict the likelihood of customers falling into the bad debt group (default) based on financial data and credit history.
Benefits:
- Minimize credit risk.
- Improve loan approval efficiency.
- Early detection of high-risk customers to take action.

Data Overview (Loan_default.csv):
Number of records: 255,347
Number of columns: 18
Target column: Default (0: No bad debt, 1: Bad debt)
Data does not have null values ​​(missing)

Main Data Columns:
• LoanID: Loan ID.
• Age: Customer age.
• Income: Annual income (VND).
• LoanAmount: Loan amount.
• CreditScore: Credit score (scale).
• MonthsEmployed: Number of months employed.
• NumCreditLines: Number of current credit lines.

• InterestRate: Loan interest rate (%).

• LoanTerm: Loan term (months).

• DTIRatio: Debt-to-Income Ratio.

• Education: Education level.

• EmploymentType: Employment status.

• MaritalStatus: Marital status.

• HasMortgage: Does it have a mortgage (Yes/No).

• HasDependents: Does it have dependents (Yes/No).

• LoanPurpose: Loan purpose (Auto, Business, Other...).

• HasCoSigner: Does it have a co-signer.

• Default: Target label (0 or 1).

Bad Debt Prediction Project Plan:
1. Clean and standardize data.

2. Analyze data (EDA) to explore the relationship between variables and bad debt.
3. Build Machine Learning model (Logistic Regression, Random Forest, XGBoost).

4. Evaluate model performance.

5. Expected Results
• Accuracy: > 85%.
• Recall: > 80% (Correctly detect bad debt customers)

