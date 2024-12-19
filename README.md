### **README - Patient Management System**

---

#### **Overview**
The Patient Management System is a C-based program designed to efficiently manage patient records, doctor information, and patient queues. It also supports offline data storage for persistence.

---

#### **Features**
1. **Patient Management**:
   - Add, remove, and display patient records.
   - Maintain a visit history for each patient.

2. **Doctor Management**:
   - Add doctor details, including specialties.
   - Assign doctors to patients.

3. **Queue System**:
   - Manage a waiting queue for patients.
   - Enqueue and dequeue patients as needed.

4. **Hash Map for Patient Records**:
   - Efficiently store and retrieve patient data using hashing with linear probing.

5. **Offline Data Storage**:
   - Save patient and doctor data to files.
   - Load data on program startup to ensure continuity.

---

#### **How to Run**
1. Compile the code using a C compiler:
   ```bash
   gcc patient_management_system.c -o patient_management_system
   ```
2. Run the program:
   ```bash
   ./patient_management_system
   ```

---

#### **Usage**
Follow the on-screen menu to:
- Manage patients and doctors.
- Handle patient queues.
- Save and exit the program to ensure data persistence.

---

#### **Files Used**
1. **`patients.txt`**:
   Stores patient details.
2. **`doctors.txt`**:
   Stores doctor details.

---

This project demonstrates efficient data management and modular programming in C.
