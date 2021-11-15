# DWDM21
Data Warehouse &amp; Data Mining 2021

นางสาวสุพิชญา ตั้งกิจวานิชย์ 623020542-0

  Group Name: เทเลทับบี้
  
  1 **_นางสาวสุพิชญา ตั้งกิจวานิชย์_**
  
  2 นางสาวภัทรสร    เทพบุตร          
  
  3 นางสาวสุภาวดี    คำทุย             
  
  4 นางสาวอุมาพร   คำภิชัย       
  
  5 นางสาวพลอยบงกช   แสงโทโพธิ์       
  

  ![Coursework & Grading](DWDM21.jpg)
  
  
  # สารบัญเนื้อหา
  
 วิชา DATA WAREHOUSE AND DATA MINING (คลังข้อมูลและการทำเหมืองข้อมูล)
 
 * บทที่ 1 [introduction](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter1.pdf) ประกอบด้วย หัวข้อต่อไปนี้
   * Why Data Mining ? (ทำไมต้องมีการทำเหมืองข้อมูล)
   * What is Data Mining ? (อะไรคือการทำเหมืองข้อมูล) 
   * Knowledge Discovery (KDD) Process
   * กระบวนการจัดการข้อมูล
   * Data Mining in Business Intelligence
   * เนื้อหาหลักของ Data Mining ประกอบด้วย 3 เรื่อง 
      * Pattern Discovery (หารูปแบบที่ซ่อนในข้อมูล)
      * Classification (จำแนกข้อมูล)
      * Clustering (จัดกลุ่มข้อมูล)
   * How the data suppose to look like ประกอบไปด้วย
      * Columns(แนวตั้ง) = Attributes,Fields,Features (คำอธิบายคุณสมบัติของข้อมูล)
      * row (แถว) = Records,Data point (ข้อมูลแต่ละตัว)
   * เทคนิคของ Data Mining ประกอบด้วย 3 เรื่อง
      * Data Mining Functions:(2) Pattern Discovery
      * Data Mining Functions:(3) Classification
      * Data Mining Functions:(4) Cluster Analysis
   * [สรุป Data Warehouse](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Data%20Warehouse.pdf)
      * ความเเตกต่างของ Data Warehouse & Data Lake & Data Marts
      * ประเภทของ Data Warehouse
        * Structured 
        * Unstructured
      * OLTP & OLAP
      * ETL
      * Star Vs Snowflake Schema
      * Data Lake
      * การประมวลผลของ Data Warehouse มีทั้งหมด 2 เเบบ
        * Batch Processing
        * Streaming Processing
  * บทที่ 2 Know Your Data ประกอบด้วย หัวข้อต่อไปนี้
      * [Basic Python](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Data101_(Chapter2).ipynb)
        * Casting
        * Data Structure
          * วิธีสร้าง list ว่าง
            * การชี้ค่าใน list (Indexing)
          * list slicing
          * list + list 
            * fomat string
        * Loop
          * Nested loop (loop ซ้อน Loop)
        * Condition (if statement)
        * Function
          * Example 1
          * ลักษณะของ input (parameter,argument)
     * [Plot Data](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Data102.ipynb) 
        * Basic Data
        * การใช้ .head() .tail() ในการเรียกดูตาราง
        * Boxplot
        * Time Series Plot
     * [Visualization](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Data_Visualization.ipynb)
        * Scatter plot
        * Plot
        * Bar chart
          * Grouped Barchart
          * Stacked Barchart
        * Histogram
     * [Distance Numpy](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Distance_Numpy.ipynb)
        * Numpy Array
          * สร้าง numpy array
          * matrix transpose
          * สร้าง matrix เริ่มต้น (zeros,ones)
          * สร้าง matrix random ค่าเเบบมั่วๆ
            * matrix properties
          * Indexing & Slicing 
          * Useful functions
            * วนลูปเอง
              * summation รวมค่าทุกค่าใน array
        * Distance Matrix
          * Euclidean Distance (L2-norm)
          * Distance function
          * Manhattan Distance (L1-norm)
          * Distance of Binary Value
    * [สรุป Lecture : Chapter 2](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/HW2.1(Chapter2).pdf)
    * [สรุป Lecture : Similarity,Dissmilarity,and Proximity](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Similarity%2CDissmilarity%2Cand%20Proximity.pdf)
 * บทที่ 3 [Data Preprocessing](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb) ประกอบด้วย หัวข้อต่อไปนี้
    * Meta Data (Data ที่ใช้อธิบาย Data)
    * ชี้ข้อมูลในตาราง
      * ชี้แบบธรรมดา ใช้ [ชื่อ column][index]
      * ชี้เเบบ .iloc[] (มองข้อมูลเป็น matrix)
    * Missing Values
      * Handling Missing Value 1 (ลบค่า Missing )
      * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
      * Handling Missing Value 2 (เเทนด้วย class ใหม่(Unknown))
      * Handling Missing Value 3 (เเทนด้วย class ใหม่ (ค่าที่เหมาะสม))
      * Handling Missing Value4(เเทนด้วย ค่ากลาง)
      * Handling Missing Value 5 (เเทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
    * เติมด้วยค่าของ column ใกล้เคียง
    * Select data by values [PD]
      * สร้าง list ของ boolean
      * นำ list ของ boolean มาเลือกค่าในตาราง
      * การเรียงข้อมูล [PD]
    * Outlier
      * Pandas' looping(.iterrows)
    * การรวมตาราง Data Integration (ต่อตารางในเเนวเเกน x)
      * รวม 2 ตาราง (.merge())
      * เลือกเฉพาะ column ที่ต้องการมาเเปะ (.map())
      * ตารางรอง(ตารางข้างขวา)ต้องไม่มี index ซ้ำ*
      * Group by (pandas)
      * [PD] save ตารางเอาไปใช้ที่อื่น
      * [PD] การสร้างตาราง
    * [สรุป Lecture : Chapter 3](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter%203.pdf)
 * บทที่ 4 [Data Warehousing & OLAP & Data Cube](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter4%20Data%20cube%20%26%20OLAP.pdf) ประกอบด้วย หัวข้อต่อไปนี้
    * Metadata Repository
    * From tables and Spreadsheets to Data Cubes
    * Data Cube A Lattics of Cuboids
    * Conceptual Modeling of Data Warehouses
    * Star Schema:An Example
    * Snowflake Schema:An Example
    * Fact Constellation:An Example
    * Multidimensional Data
    * A Sample Data Cube
    * Typical OLAP Operations
    * A Star-Net Query Model
    * What is a Data Warehouse? (Data Warehouse คืออะไร ?)
    * ประเภทของ Data Warehouse
      * Data Warehouse-Subject-Oriented
      * Data Warehouse-Integrated
      * Data Warehouse-Time Variant
      * Data Warehouse-Nonvolatile
    * OLTP VS. OLAP
    * Why a Separate Data Warehouse ? 
    * Data Warehouse A Multi-Tiered Architecture
    * Three Data Warehouses Models
    * Extration,Transformation,and Loading (ETL)
* บทที่ 5 [Association Rules](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter6_Association_Rules.ipynb) ประกอบด้วย หัวข้อต่อไปนี้
    * [Q] มีประเทศสาขาของ supermarket นี้ทั้งหมดกี่ประเทศ
    * ลบ records ที่ถูก cancel ออกไป
    * เพิ่มคอลัมน์ ยอดขาย (Quantity*UnitPrice)
    * เพิ่ม column ราคารวม
    * เตรียม Data สำหรับ (Frequence Pattern) Association Rule
    * Apriori
    * [สรุป Lecture : Chapter 5](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter6_Association_Rules(Short%20Notes).pdf)
* บทที่ 6 Classifications ประกอบด้วย หัวข้อต่อไปนี้
  * [Decision Tree](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
    * Load Data
    * Train Model
      * import (เรียกใช้ algorithm ที่เราต้องการ)
      * Define (กำหนด parameters ให้กับ model)
      * train (ฝึกสอนตัวแบบ)
    * Plot Tree
    * Evaluation
      * Random
    * Advanced Tree
      * Import
      * Define
      * Train
    * TEST
    * Start here
      * Import
      * Define
      * Train
      * Evaluate
    * [สรุป Lecture : Decision Tree](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter7_Classification_Lecture.pdf)
    * [สรุป Lecture : Gini & Overfitting](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter%207%20Gini%20%26%20Overfitting(Lecture).pdf)
  * [KNN-NN](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chap_7_Classification_(KNN_NN).ipynb)
    * Load Data
    * Split Data
    * Train Model
      * Import
      * knn1
      * knn2
      * knn3
    * Retrain & Evaluate
    * Neural Network
      * Import
      * Define
      * Train-Test
      * ANN 2
      * ANN 3
    * [สรุป Lecture : Neural Network & Confusion Matrix](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chap7%20Neural%20Network%20%26%20Confusion%20Matrix.pdf)
  * [Evaluation](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
    * Load data
    * แบ่ง Data
    * สร้าง Model ทำนาย
      * Import
      * Define
      * Train
    * Evaluation
    * [สรุป Lecture : Evaluation(Sensitivity&Specificity)](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chap7%20Classification%20(Evaluation)%20Sensitivity%26Specificity.pdf)
* บทที่ 7 [Clustering](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chap8_Clustering.ipynb) ประกอบด้วย หัวข้อต่อไปนี้
  * K-means
    * Generate Data
    * Clustering
      * Import
      * Define
      * Fit-Predict
      * นับจำนวนสี
      * จัดกลุ่มสีให้เหลือ 16 สี
      * แปลงข้อมูลให้อยู่ในรูป row-column
      * ใช้ centroid เป็นตัวเเทนของสี
      * เเทนสีคืนลงไป
 * Hierarchical Clustering
 * Clustering Evaluation
 * [สรุป Lecture : Chapter 7](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Chapter%208%20Clustering%20K_mean.pdf)
* [MiniExam](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/MiniExam.ipynb)
* [โครงงาน (Project)](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/New_Project.ipynb)  
  * [สไลด์นำเสนอ](https://github.com/SupidchayaTangkidwanich/DWDM21/blob/main/Slide%20Project.pdf) 
  
  
