📦 assignment_1_polymorphism
 ┣ 📜 main.py        # Python code with Smartphone + Vehicles
 ┣ 📜 README.md      # Documentation
# 📘 Assignment 1 & Activity 2 – Object-Oriented Programming (OOP)

## 👩‍💻 Overview
This project demonstrates **Object-Oriented Programming (OOP)** concepts in Python:  
- **Classes & Objects**  
- **Constructors (`__init__`)**  
- **Attributes & Methods**  
- **Inheritance**  
- **Encapsulation**  
- **Polymorphism**  

It contains two parts:  
1. **Smartphone Class (with inheritance from Device)**  
2. **Vehicles Polymorphism Challenge**

---

## 🏗️ Assignment 1: Smartphone Class
- A **Device** base class defines general device attributes (brand, model).  
- A **Smartphone** class inherits from Device and adds:  
  - `storage` (GB)  
  - `battery` (%)  
- Methods include:  
  - `charge(amount)` → increases battery  
  - `use_storage(amount)` → decreases storage if enough available  
  - `__str__()` → clean display of phone details  

### ✅ Example:
```python
phone1 = Smartphone("Apple", "iPhone 15", 256, 80)
print(phone1)  
phone1.charge(15)  
phone1.use_storage(50)
vehicles = [Car(), Plane(), Boat()]
for v in vehicles:
    v.move()

=== Assignment 1: Smartphones ===
Apple iPhone 15 | Storage: 256GB | Battery: 80%
🔋 Apple iPhone 15 charged to 95%
📂 Apple iPhone 15 used 50GB, 206GB left
Samsung Galaxy S24 | Storage: 512GB | Battery: 50%
⚠️ Samsung Galaxy S24 does not have enough storage!

=== Activity 2: Polymorphism with Vehicles ===
🚗 The car is driving on the road.
✈️ The plane is flying in the sky.
🚤 The boat is sailing on water.
