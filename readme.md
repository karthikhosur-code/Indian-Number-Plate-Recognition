Automatic Number Plate Recognition System to explore the Vulnerabilities in the VAHAN.NIC.IN portal

Automatic number-plate recognition is a technology that uses optical character recognition on images to read vehicle registration plates using OpenCV and Tesseract OCR Engine. It can be used on existing closed-circuit television, road-rule enforcement cameras, or cameras specifically designed for the task. Using Selenium web driver, number plate recognized is parsed to the government website vahan.nic.in along with the solved captcha and the vehicle details can be accessed for further Inference and analysis. The crawled information is converted to structured and unstructured data and stored in Firebase and MySQL for data analysis and live dashboard. Through the dashboard the notification triggers can be set if a vehicle defaults any of the rules , an SMS will be sent to the mobile phone of the authority. Tested on 1500 Indian Number Plates gave us a success rate of 64% which is better than the current existing systems. As well as, successfully retrieve vehicle information from secure government website with a success rate of 75%.

NOTE : THIS PROJECT IS FOR EDUCATIONAL PURPOSES ONLY. WE REPORTED THE VULNERABILITIES IN THE VAHAN.NIC.IN TO THE NATIONAL INFORMATION CENTER,INDIA. WE SHOWCASED OUR PROJECT AND THE SECURITY THREATS IN THE WEBSITE IN DETAIL. TO THE SAME WE ALSO PROVIDED SOLUTIONS. AS OF NOVEMBER 10th,2020 THE OUR SUGGESTIONS HAVE BEEN ACCEPTED AND USED IN THE LATEST UPDATE WHICH HAS IMPROVED SECURITY AND MINIMIZE THE THREAT TO THE PRIVACY OF VEHICLE AND PERSONAL INFORMATION. 

Software and Hardware Requirements:

Processor : Intel I5 2.1 Ghz.
Storage : 100GB
RAM : 8 GB
Platform: Windows/Linux/macOS
Technologies used: PyTesseract, OpenCV, Selenium, Chrome Driver, Tkinter, Pyrebase,MySQL connector


Installation and Run:

Open a terminal or command prompt
Navigate to the project folder with requirements.txt
run: pip install -r requirements.txt
You are done installing dependencies
Open main.py 


Execution : https://drive.google.com/drive/folders/1Z3Jy06cz-QxNtODW4qOmpsGFN448zbYr?usp=sharing
