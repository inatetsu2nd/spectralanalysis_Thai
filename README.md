# Spectralanalysis_Thai
### Overview  

This repository contains materials for a lecture in Thailand titled *“A Practical Guide to Spectral Analysis from Fundamentals to Applications.”*  
Topics include Python-based data analysis, chemometrics, machine learning, and hyperspectral imaging.

The content is based on the Japanese book *"Spectral Analysis Practical Guide"* by Tetsuya Inagaki, Nagoya University.

**Chapters:**
- Chapter 1: Fundamentals of Spectral Analysis  
- Chapter 2: Introduction to Python Programming  
- Chapter 3: Basic Statistics with Python  
- Chapter 4: Linear Algebra with Python  
- Chapter 5: Effective Use of ChatGPT  
- Chapter 6: Basics of Chemometrics  
- Chapter 7: Applied Chemometrics  
- Chapter 8: Preprocessing of Spectral Data  
- Chapter 9: Introduction to Machine Learning  
- Chapter 10: Practical Spectral Manipulation  
- Chapter 11: Chemometrics and Machine Learning in Practice  
- Chapter 12: Hyperspectral Imaging Data Analysis

### Folder Structure
- `dataChapter03`, `dataChapter04`, ..., `dataChapter12`: Data for corresponding chapters

### File Structure
All files are named using the format: `SpeAna(ChapterNumber)_(SectionNumber)_Description.ipynb`.  
Below is a summary of each file:
- `SpeAna00_tips.ipynb`: Tips on file conversion and LLM usage  
- `SpeAna02_3-4_basic.ipynb`: Chapter 2, Sections 3–4 — Fundamentals of Python  
- `SpeAna03_1-10_statistcs.ipynb`: Chapter 3, Sections 1–10 — Basic statistics and implementation in Python  
- `SpeAna04_1-3_linearalgebraANDdataframe.ipynb`: Chapter 4, Sections 1–3 — Linear algebra and DataFrame handling  
- `SpeAna06_1_CLSandILS.ipynb`: Chapter 6, Section 1 — Classical Least Squares (CLS) and Inverse Least Squares (ILS)  
- `SpeAna07_1_PCA.ipynb`: Chapter 7, Section 1 — Principal Component Analysis (PCA)  
- `SpeAna07_2_PLS.ipynb`: Chapter 7, Section 2 — Partial Least Squares Regression (PLS)  
- `SpeAna08_1-4_pretreatment.ipynb`: Chapter 8, Sections 1–4 — Preprocessing of spectral data  
- `SpeAna08_5_modules.ipynb`: Chapter 8, Section 5 — How to use Python modules  
- `SpeAna09_1-6_machinelearning.ipynb`: Chapter 9, Sections 1–6 — Applications of machine learning  
- `SpeAna10_1-9_practicaluse.ipynb`: Chapter 10, Sections 1–9 — Practical spectral manipulation techniques  
- `SpeAna11_1-6_practicaluse.ipynb`: Chapter 11, Sections 1–6 — Practical applications of chemometrics and machine learning  
- `SpeAna12_1_Imaging.ipynb`: Chapter 12, Section 1 — Applications to imaging data


### Library Installation
Use the `requirements.txt` file:

```bash
cd C:\Users\YourUsername\Documents\PythonProjects\MyProject
pip install -r requirements.txt
```
- `requirements.txt`  
After downloading this file, open the Anaconda Prompt and navigate to the directory where the `requirements.txt` file is located.  
For example, suppose the file is located in `C:\Users\YourUsername\Documents\PythonProjects\MyProject`.  
You can install the listed libraries by following these steps:

1. Open the Anaconda Prompt and use the `cd` command to move to the directory containing `requirements.txt`:  
`cd C:\Users\USERNAME\Documents\PythonProjects\MyProject`

2. Run the following command to install all libraries listed in the file:  
`pip install -r requirements.txt`

### Downloading the Data
Click the green `< > Code` button on the top right of this page and select **Download ZIP**.

### How to Use
Ensure Python 3.x and all required libraries are installed.  
Open files starting with `SpeAna` in Jupyter Notebook to run the code.

### If You Cannot Download Files
Please contact:  
`inatetsu@agr.nagoya-u.ac.jp`

### Author
- [Tetsuya Inagaki](https://researchmap.jp/inatetsu25/)

# Spectralanalysis_Thai
### ภาพรวม

ที่เก็บนี้ประกอบด้วยเนื้อหาสำหรับการบรรยายในประเทศไทยในหัวข้อ *“คู่มือการวิเคราะห์สเปกตรัมเชิงปฏิบัติ ตั้งแต่พื้นฐานถึงการประยุกต์ใช้”*  
หัวข้อครอบคลุมการวิเคราะห์ข้อมูลด้วย Python, เคโมเมตริกส์, การเรียนรู้ของเครื่อง และการประยุกต์ใช้กับภาพไฮเปอร์สเปกตรัม

เนื้อหานี้อ้างอิงจากหนังสือภาษาญี่ปุ่นชื่อ *"Spectral Analysis Practical Guide"* โดย ศ. Tetsuya Inagaki จากมหาวิทยาลัยนาโกย่า

**สารบัญบท:**
- บทที่ 1: พื้นฐานของการวิเคราะห์สเปกตรัม  
- บทที่ 2: บทนำเกี่ยวกับการเขียนโปรแกรม Python  
- บทที่ 3: สถิติพื้นฐานด้วย Python  
- บทที่ 4: พีชคณิตเชิงเส้นด้วย Python  
- บทที่ 5: การใช้ ChatGPT อย่างมีประสิทธิภาพ  
- บทที่ 6: พื้นฐานของเคโมเมตริกส์  
- บทที่ 7: เคโมเมตริกส์ขั้นประยุกต์  
- บทที่ 8: การเตรียมข้อมูลสเปกตรัมเบื้องต้น  
- บทที่ 9: พื้นฐานของการเรียนรู้ของเครื่อง  
- บทที่ 10: การประมวลผลสเปกตรัมเชิงปฏิบัติ  
- บทที่ 11: เคโมเมตริกส์และการเรียนรู้ของเครื่องเชิงปฏิบัติ  
- บทที่ 12: การวิเคราะห์ข้อมูลภาพไฮเปอร์สเปกตรัม

### โครงสร้างโฟลเดอร์
- `dataChapter03`, `dataChapter04`, ..., `dataChapter12`: ข้อมูลที่ใช้ในแต่ละบท

### โครงสร้างไฟล์
ไฟล์ทั้งหมดถูกตั้งชื่อตามรูปแบบ: `SpeAna(ChapterNumber)_(SectionNumber)_Description.ipynb`  
ด้านล่างนี้คือสรุปเนื้อหาของแต่ละไฟล์:
- `SpeAna00_tips.ipynb`: เคล็ดลับเกี่ยวกับการแปลงไฟล์และการใช้งาน LLM  
- `SpeAna02_3-4_basic.ipynb`: บทที่ 2 ตอนที่ 3–4 — พื้นฐานของภาษา Python  
- `SpeAna03_1-10_statistcs.ipynb`: บทที่ 3 ตอนที่ 1–10 — สถิติพื้นฐานและการใช้งานด้วย Python  
- `SpeAna04_1-3_linearalgebraANDdataframe.ipynb`: บทที่ 4 ตอนที่ 1–3 — พีชคณิตเชิงเส้นและการใช้งาน DataFrame  
- `SpeAna06_1_CLSandILS.ipynb`: บทที่ 6 ตอนที่ 1 — การถดถอยแบบ Classical Least Squares (CLS) และ Inverse Least Squares (ILS)  
- `SpeAna07_1_PCA.ipynb`: บทที่ 7 ตอนที่ 1 — การวิเคราะห์องค์ประกอบหลัก (PCA)  
- `SpeAna07_2_PLS.ipynb`: บทที่ 7 ตอนที่ 2 — การถดถอยแบบ Partial Least Squares (PLS)  
- `SpeAna08_1-4_pretreatment.ipynb`: บทที่ 8 ตอนที่ 1–4 — การเตรียมข้อมูลสเปกตรัมเบื้องต้น  
- `SpeAna08_5_modules.ipynb`: บทที่ 8 ตอนที่ 5 — การใช้งานโมดูลของ Python  
- `SpeAna09_1-6_machinelearning.ipynb`: บทที่ 9 ตอนที่ 1–6 — การประยุกต์ใช้การเรียนรู้ของเครื่อง  
- `SpeAna10_1-9_practicaluse.ipynb`: บทที่ 10 ตอนที่ 1–9 — เทคนิคการจัดการสเปกตรัมในทางปฏิบัติ  
- `SpeAna11_1-6_practicaluse.ipynb`: บทที่ 11 ตอนที่ 1–6 — การประยุกต์ใช้เคโมเมตริกส์และการเรียนรู้ของเครื่องในทางปฏิบัติ  
- `SpeAna12_1_Imaging.ipynb`: บทที่ 12 ตอนที่ 1 — การประยุกต์ใช้กับข้อมูลภาพ

### การติดตั้งไลบรารี
ใช้ไฟล์ `requirements.txt` ดังนี้:

```bash
cd C:\Users\YourUsername\Documents\PythonProjects\MyProject
pip install -r requirements.txt
```
### การติดตั้งไลบรารี (`requirements.txt`)
หลังจากดาวน์โหลดไฟล์นี้ ให้เปิด **Anaconda Prompt** และไปยังโฟลเดอร์ที่เก็บไฟล์ `requirements.txt`  
ตัวอย่างเช่น หากไฟล์อยู่ที่ `C:\Users\YourUsername\Documents\PythonProjects\MyProject`  
คุณสามารถติดตั้งไลบรารีทั้งหมดที่ระบุไว้ได้โดยทำตามขั้นตอนนี้:

1. เปิด Anaconda Prompt และใช้คำสั่ง `cd` เพื่อไปยังไดเรกทอรีที่มีไฟล์:
`cd C:\Users\USERNAME\Documents\PythonProjects\MyProject`

2. รันคำสั่งต่อไปนี้เพื่อติดตั้งไลบรารีทั้งหมดที่ระบุไว้ในไฟล์:  
`pip install -r requirements.txt`

### การดาวน์โหลดข้อมูล
คลิกปุ่มสีเขียว `< > Code` ที่มุมขวาบนของหน้านี้ แล้วเลือก **Download ZIP**

### วิธีการใช้งาน
ตรวจสอบให้แน่ใจว่าได้ติดตั้ง **Python 3.x** และไลบรารีที่จำเป็นทั้งหมดแล้ว  
เปิดไฟล์ที่ขึ้นต้นด้วย `SpeAna` ใน **Jupyter Notebook** เพื่อรันโค้ด

### หากไม่สามารถดาวน์โหลดไฟล์ได้
กรุณาติดต่อ:  
`inatetsu@agr.nagoya-u.ac.jp`

### ผู้เขียน
- [Tetsuya Inagaki](https://researchmap.jp/inatetsu25/)


