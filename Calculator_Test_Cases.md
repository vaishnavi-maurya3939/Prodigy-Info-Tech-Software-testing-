# Test Cases for Calculator

---

## **1. Basic Arithmetic Operations**

### **Test Case ID:** TC-01  

**Test Description:** Addition  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 5  
2. Press +  
3. Enter 3  
4. Press =  
**Expected Results:** Display 8  

---

### **Test Case ID:** TC-02  

**Test Description:** Subtraction  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 9  
2. Press -  
3. Enter 4  
4. Press =  
**Expected Results:** Display 5  

---

### **Test Case ID:** TC-03  

**Test Description:** Multiplication  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 6  
2. Press *  
3. Enter 7  
4. Press =  
**Expected Results:** Display 42  

---

### **Test Case ID:** TC-04  

**Test Description:** Division  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 8  
2. Press /  
3. Enter 2  
4. Press =  
**Expected Results:** Display 4  

---

### **Test Case ID:** TC-05  

**Test Description:** Division by Zero  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 5  
2. Press /  
3. Enter 0  
4. Press =  
**Expected Results:** Infinity  

---

## **2. Decimal Operations**

### **Test Case ID:** TC-06  

**Test Description:** Decimal Addition  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 2.5  
2. Press +  
3. Enter 1.5  
4. Press =  
**Expected Results:** Display 4.0  

---

### **Test Case ID:** TC-07  

**Test Description:** Decimal Subtraction  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 5.7  
2. Press -  
3. Enter 2.3  
4. Press =  
**Expected Results:** Display 3.4  

---

### **Test Case ID:** TC-08  

**Test Description:** Decimal Multiplication  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 2.5  
2. Press *  
3. Enter 4.2  
4. Press =  
**Expected Results:** Display 10.5  

---

### **Test Case ID:** TC-09  

**Test Description:** Decimal Division  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 6.0  
2. Press /  
3. Enter 2.0  
4. Press =  
**Expected Results:** Display 3.0  

---

## **3. Complex Operations**

### **Test Case ID:** TC-10  

**Test Description:** Mixed Operations  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 2  
2. Press +  
3. Enter 3  
4. Press *  
5. Enter 4  
6. Press =  
**Expected Results:** Display 20

---

### **Test Case ID:** TC-11  

**Test Description:** Negative Numbers  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 5  
2. Press +  
3. Enter -3  
4. Press =  
**Expected Results:** Display 2  

---

### **Test Case ID:** TC-12  

**Test Description:** Multiple Operations  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 5  
2. Press *  
3. Enter 2  
4. Press +  
5. Enter 10  
6. Press /  
7. Enter 2  
8. Press =  
**Expected Results:** Display 10  

---

## **4. Edge Cases**

### **Test Case ID:** TC-13  

**Test Description:** Leading Zeros  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 0004  
2. Press +  
3. Enter 2  
4. Press =  
**Expected Results:** Display 6  

---

### **Test Case ID:** TC-14  

**Test Description:** Large Numbers  
**Preconditions:** Calculator supports large numbers  
**Test Steps:**  

1. Enter 9999999  
2. Press *  
3. Enter 2  
4. Press =  
**Expected Results:** Display 19999998  

---

### **Test Case ID:** TC-15  

**Test Description:** Long Decimal Numbers  
**Preconditions:** Calculator supports decimal numbers  
**Test Steps:**  

1. Enter 0.00001  
2. Press +  
3. Enter 0.00002  
4. Press =  
**Expected Results:** Display 0.00003  

---

### **Test Case ID:** TC-16  

**Test Description:** Clear Button  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Enter 5  
2. Press +  
3. Enter 3  
4. Press C  
**Expected Results:** Display 0 or clear the screen  

---

## **5. UI Testing**

### **Test Case ID:** TC-17  

**Test Description:** Button Functionality  
**Preconditions:** Calculator is open  
**Test Steps:**  

1. Click all calculator buttons  
**Expected Results:** All buttons respond correctly  

---

### **Test Case ID:** TC-18  

**Test Description:** Display Limit  
**Preconditions:** Calculator display has a character limit  
**Test Steps:**  

1. Enter a long number exceeding the display limit  
**Expected Results:** Display truncates or scrolls correctly  

---

### **Test Case ID:** TC-19  

**Test Description:** Error Message Display  
**Preconditions:** Calculator should show error messages for invalid operations  
**Test Steps:**  

1. Enter 1  
2. Press /  
3. Enter 0  
4. Press =  
**Expected Results:** Infinity

---
