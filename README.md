# **Government Property Compliance Visualization**

## **Project Overview**  
This project provides interactive data visualizations to analyze and monitor compliance with **FAR 52.245-1** and **DFARS 252.245-7005** guidelines for government property management. The solution helps stakeholders track contractor performance, identify audit issues, and optimize asset management using powerful insights.

**Note**: This project uses a **synthetic, fake dataset** generated for demonstration purposes only. No proprietary or sensitive information was used in the creation of this project.

![image](https://github.com/user-attachments/assets/d77d3b70-a286-4d2f-8c33-6ecadc909dfd)


---

## **Key Features**  
- 📊 **Compliance Score Tracking**: Visualize trends in compliance scores over time to monitor performance.  
- 🔍 **Contractor Performance Heatmap**: Compare audit issues, lost assets, and compliance scores across contractors.  
- 🖋 **Lost vs. Damaged Assets Analysis**: Evaluate inventory health to identify discrepancies.  
- ✅ **Audit Compliance Overview**: Highlight compliant vs. non-compliant contractors.  
- ⚡ **Interactive Dashboard**: Drill down into detailed metrics for actionable insights.  

---

## **Technologies Used**  
- **Python**: Data preprocessing and analysis using Pandas and Matplotlib.  
- **Power BI**: Interactive dashboards for stakeholder engagement.  
- **Seaborn**: Heatmap and detailed performance visuals.  
- **Excel/CSV**: Data storage for audit and inventory data.  

---

## **Data Sources**  
- **audit_data.csv**: Contains contractor audit records with `Audit_Issues` and `Audit_Status`.  
- **inventory_data.csv**: Tracks total assets, lost assets, and inventory accuracy per contractor.

### **Sample Columns**  
1. `Contractor_ID`  
2. `Total_Assets`  
3. `Lost_Assets`  
4. `Damaged_Assets`  
5. `Audit_Issues`  
6. `Compliance_Score`  

---

## **Visualizations**  
Key dashboards and charts include:  
1. **Compliance Score Over Time**: Line chart showing trends.  
2. **Contractor Heatmap**: Compare metrics like `Audit Issues` and `Lost Assets`.  
3. **Damage vs. Loss Assets**: Stacked bar chart per contractor.  

---

## **Live Dashboard**  
Explore the interactive Power BI dashboard here: [Government Property Compliance Dashboard](https://govtpropertycompliance.powerappsportals.com/)

---

## **Sample Screenshots**  
1. Compliance Score Trend
![image](https://github.com/user-attachments/assets/9f441044-8b90-4273-8be3-7537d85076eb)

2. Audit Issues Over Time
![image](https://github.com/user-attachments/assets/fcd2edb9-859b-4143-adae-224eb2248197)

3. Damage vs. Loss Assets
![image](https://github.com/user-attachments/assets/c5dcb086-0309-4e08-ac5e-05238e9a42b3)


---

## **Contributing**  
Contributions are welcome! Please follow these steps:  
1. Fork the repository.  
2. Create a new branch: `git checkout -b feature-branch-name`.  
3. Commit your changes: `git commit -m "Add new feature"`.  
4. Push to the branch: `git push origin feature-branch-name`.  
5. Open a pull request.

---

## **License**  
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## **Contact**  
For any questions or suggestions, please reach out:  
- **Name**: Your Name  
- **Email**: your.email@example.com  
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)
